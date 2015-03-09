# NYC Open Data - GeoJSON Format

As part of the [New York Startup Index][github-nysi] project that was [created at hackNY][challengepost-nysi] this year, we took some of the data provided by the [NYC Open Data][nyc-open-data] initiative and plotted it on a map.  You would think this would take only a few seconds, but unfortunately data cannot be extracted in the [GeoJSON format][geojson] and as such can't easily be plotted on maps such as [Leafelet][leaflet].

So in order to make others lives easier, this repository includes already converted GeoJSON data for some data sets.  They have been sorted into different directories based on the category, with information about each data set being provided in the README file.  Check the latest commit information for the date that they were last updated.

## Want to add a new GeoJSON file? Updated an existing one?

This repository is not automatically updated when new data sets are added or updated, so it will very likely be only storing historical data.  If you have a new GeoJSON file, feel free to update the README in the category directory (create a new one if needed), add the GeoJSON file, and create a pull request to this repository on GitHub.

[challengepost-nysi]: http://challengepost.com/software/49012
[geojson]: http://geojson.org/
[github-nysi]: https://github.com/gunthercox/NewYorkStartupIndex
[leaflet]: http://leafletjs.com/
[nyc-open-data]: https://nycopendata.socrata.com/
