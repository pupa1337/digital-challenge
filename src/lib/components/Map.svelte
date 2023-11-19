<head>
	<script
		src="https://api-maps.yandex.ru/v3/?apikey=895aa12e-e219-44b8-9e6c-ace55c905677&lang=ru_RU"
	></script>
	<script>
		initMap();

		async function initMap() {
			await ymaps3.ready;

			const { YMap, YMapDefaultSchemeLayer } = ymaps3;
			const map = new YMap(document.getElementById('map12345'), {
				location: {
					center: [73.386367, 61.254662],
					zoom: 12
				}
			});
			map.addChild(new YMapDefautSchemeLayer());
		}
	</script>
</head>
<div id="map12345" style="width: 90vw; height: 80vh; padding: 30px 0"></div>
