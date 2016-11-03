
<!-- README.md is generated from README.Rmd. Please edit that file -->
rmapzen
-------

rmapzen is a client for the Mapzen API. For more information, see <https://mapzen.com/documentation/>.

So far, all of the services in [Mapzen search](https://mapzen.com/documentation/search/) have been implemented. Search functions:

-   `mz_search`
-   `mz_reverse_geocode`
-   `mz_autocomplete`
-   `mz_place`

All of the search functions return a `geo_list` object. These can be used directly in the `leaflet` package (and possibly others?), and can be converted to `sp` objects via the package [geojsonio](https://github.com/ropensci/geojsonio).

Additionally, `mz_geocode` is convenient function to geocode an address, utilizing the more general `mz_search` function.
