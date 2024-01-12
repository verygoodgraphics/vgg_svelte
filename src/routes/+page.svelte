<script lang="ts">
	import VGGRender from '../../dist/index.js';
</script>

<main>
	<div class="flex">
		<div class="relative">
			<div class="absolute top-2 w-full flex justify-center item-center">
				<h2 class="bg-violet-500 rounded-md px-2 py-1 text-white text-sm font-semibold">
					VGGRender Component
				</h2>
			</div>
			<VGGRender
				src="https://s3.vgg.cool/test/vgg.daruma"
				runtime="https://s3.vgg.cool/test/runtime/latest"
				canvasStyle="width: 50vw; height: 100vh"
			/>
		</div>
	</div>
</main>

<style>
</style>
