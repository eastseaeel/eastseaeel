<script>
	import "../lib/styles.scss";
</script>

<div class="footer">THIS WILL BE ON EVERY PAGE</div>
<slot />

<style lang="scss">
	@use "../lib/theme.scss" as theme;

	.footer {
		width: 100vw;
		position: absolute;
		top: 0px;
		background-color: theme.$sub;
	}
</style>
