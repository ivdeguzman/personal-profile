<script lang="ts">
</script>

<div class="intro h-screen w-screen grid place-items-center fixed top-0 z-50">
	<div class="loader">
		<span /><span /><span />
	</div>
</div>

<style>
	.intro {
		background: rgb(111, 111, 111);
		background: radial-gradient(
			circle,
			rgba(111, 111, 111, 1) 0%,
			rgba(73, 76, 65, 1) 100%
		);
	}
	.loader {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.loader > span {
		display: inline-block;
		background-color: rgb(223, 223, 0);
		width: 0px;
		height: 0px;
		border-radius: 50%;
		margin: 0 8px;
		transform: translate3d(0);
		animation: bounce 0.6s infinite alternate;
	}
	.loader > span:nth-child(2) {
		background-color: rgb(255, 153, 0);
		animation-delay: 0.2s;
	}
	.loader > span:nth-child(3) {
		animation-delay: 0.4s;
	}

	@keyframes bounce {
		to {
			width: 16px;
			height: 16px;
			transform: translate3d(0, -16px, 0);
		}
	}
</style>
