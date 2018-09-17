# Novità rilevanti introdotte nella 3.4 LTR

## Nuovi gruppi funzioni nel calcolatore di campi
![](/img/novita_34/neo_gruppi.png)

## Nuove funzioni
* [**raster_value()**](./gr_funzioni/rasters/funzioni/raster_value.md) - PR [#7487](https://github.com/qgis/QGIS/pull/7487) 
* [**line_substring**](./gr_funzioni/geometria/funzioni/line_substring.md) - PR [#7587](https://github.com/qgis/QGIS/pull/7587)
* [**array_foreach**](./gr_funzioni/array/funzioni/array_foreach.md) -PR [#7628](https://github.com/qgis/QGIS/pull/7628)
* [**generate_series**](./gr_funzioni/arrays/funzioni/generate_series.md) - PR [#7655](https://github.com/qgis/QGIS/pull/7655)
* [**array_filter**](./gr_funzioni/array/funzioni/array_filter.md) - PR [#7688](https://github.com/qgis/QGIS/pull/7688)
* [**to_dm**](./gr_funzioni/conversioni/funzioni/to_dm.md) - PR [#7593](https://github.com/qgis/QGIS/pull/7593)
* [**to_dms**](./gr_funzioni/conversioni/funzioni/to_dms.md) - PR [#7593](https://github.com/qgis/QGIS/pull/7593)
* [**hstore_to_map**](./gr_funzioni/maps/funzioni/hstore_to_map.md) -PR [#7884](https://github.com/qgis/QGIS/pull/7884)
* [**json_to_map**](./gr_funzioni/maps/funzioni/json_to_map.md) -PR [#7884](https://github.com/qgis/QGIS/pull/7884)
* [**map_to_hstore**](./gr_funzioni/maps/funzioni/map_to_hstore.md) -PR [#7884](https://github.com/qgis/QGIS/pull/7884)
* [**map_to_json**](./gr_funzioni/maps/funzioni/map_to_json.md) -PR [#7884](https://github.com/qgis/QGIS/pull/7884)

## Completamento codice per il costruttore di espressioni - PR [#7835](https://github.com/qgis/QGIS/pull/7835)
![](/img/novita_34/completa_field_calc.gif)

## Cambiata la rappresentazione di array e map nelle espressioni - PR [#7692](https://github.com/qgis/QGIS/pull/7692)

* **array rappresentazione:**

prima → `ora`

array: 1, 2, 3 → `[ 1, 2, 3 ]`

![](/img/novita_34/arrays.png)

* **map rappresentazione:**

prima → `ora`

map: one: 1, two: 2, 3: three → `{'one': 1, 'two': 2, 3: 'three'}`

![](/img/novita_34/map.png)