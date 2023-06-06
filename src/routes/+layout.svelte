<script>
	import "../lib/styles.scss";
	import logo from "../lib/images/logo.png";
</script>

<div class="footer">
	<img alt="" src={logo} />

	<a href="contact/">Contact</a>
</div>
<slot />

<style lang="scss">
	@use "../lib/theme.scss" as theme;

	.footer {
		position: absolute;
		top: 0px;

		width: 100vw;
		background-color: theme.$sub;
		width: min-content;
		display: flex;

		img {
			max-height: 10rem;
			width: auto;
		}
	}
</style>
