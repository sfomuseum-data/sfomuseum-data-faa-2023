# sfomuseum-data-faa-2023

2023 data from the FAA's Airport Status Web Service for SFO.

## Important

This is highly experiental work right now. If you are planning to try using it, for anything at all, understand that everything is in flux and subject to change and may still break along the way.

## Example

```
$> cat data/152/801/259/5/1528012595.geojson

{
  "id": 1528012595,
  "type": "Feature",
  "properties": {
    "date:cessation_lower":"2020-01-31",
    "date:cessation_upper":"2020-01-31",
    "date:inception_lower":"2020-01-31",
    "date:inception_upper":"2020-01-31",
    "edtf:cessation":"2020-01-31T07:52:54",
    "edtf:inception":"2020-01-31T07:52:54",
    "faa:credit":"http://weather.gov/",
    "faa:delay":true,
    "faa:delay_avg":"51 minutes",
    "faa:delay_count":1,
    "faa:delay_reason":"WEATHER/LOW VISIBILITY",
    "faa:last_update":"Last Updated on Jan 31 2020, 6:56 am PST",
    "faa:temperature_c":10,
    "faa:temperature_f":50,
    "faa:temperature_raw":"50.0 F (10.0 C)",
    "faa:visibility":10,
    "faa:wind_direction":"North",
    "faa:wind_raw":"North at 0.0",
    "faa:wind_speed":0,
    "geom:area":0.0,
    "geom:bbox":"-122.37,37.62,-122.37,37.62",
    "geom:latitude":37.62,
    "geom:longitude":-122.37,
    "iso:country":"US",
    "mz:hierarchy_label":1,
    "mz:is_current":0,
    "sfomuseum:placetype":"weather",
    "sfomuseum:uri":"2020/01/31/20200131T075254.json",
    "src:geom":"flysfo",
    "wof:belongsto":[
        102527513,
        85688637,
        102191575,
        85633793,
        85922583,
        102087579,
        554784711,
        102085387
    ],
    "wof:breaches":[],
    "wof:concordances":{
        "iata:code":"SFO",
        "icao:code":"KSFO"
    },
    "wof:country":"US",
    "wof:created":1580457174,
    "wof:geomhash":"6e11b039d229c1f441fd06b875619d83",
    "wof:hierarchy":[
        {
            "campus_id":102527513,
            "continent_id":102191575,
            "country_id":85633793,
            "county_id":102087579,
            "custom_id":1528012595,
            "locality_id":85922583,
            "postalcode_id":554784711,
            "region_id":85688637
        },
        {
            "campus_id":102527513,
            "continent_id":102191575,
            "country_id":85633793,
            "county_id":102085387,
            "custom_id":1528012595,
            "region_id":85688637
        }
    ],
    "wof:id":1528012595,
    "wof:lastmodified":1580493598,
    "wof:name":"FAA status for SFO, 2020-01-31T07:52:54",
    "wof:parent_id":102527513,
    "wof:placetype":"custom",
    "wof:repo":"sfomuseum-data-faa-2020",
    "wof:superseded_by":[],
    "wof:supersedes":[],
    "wof:tags":[]
},
  "bbox": [
    -122.37,
    37.62,
    -122.37,
    37.62
],
  "geometry": {"coordinates":[-122.37,37.62],"type":"Point"}
}
```

## License

This data is published under the [Community Data License Agreement – Permissive – Version 1.0](LICENSE) license, but we'd love a [shout-out](https://twitter.com/flysfo) and generally to hear what you're doing if you use the data.

## See also

* https://services.faa.gov/
* https://github.com/Federal-Aviation-Administration/ASWS
