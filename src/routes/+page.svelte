<script>
	import Map from '$lib/components/Map.svelte';
	import GazHeader from '$lib/components/common/Gaz-header.svelte';
	import Footer from '$lib/components/common/footer.svelte';
</script>

<div class="global container mx-auto">
	<GazHeader />
	<div class="map container mx-auto flex items-center justify-between">
		<script src="https://api-maps.yandex.ru/services/constructor/1.0/js/?um=constructor%3A14a8699a74a23f12eee910a144d334861168a5126e66b2c53b95f9232e9e1705&amp;width=967&amp;height=489&amp;lang=ru_RU&amp;scroll=true"></script>
	</div>
	<Footer />
</div>

<style>
</style>
