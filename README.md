# highcharts-epub-test
Basic testing of Highcharts JS in EPUB 3 ebooks.

## To build
Add to ZIP in two stages (ensure mimetype is added first, without compression or extra metadata), and rename resulting archive to *.epub:
```
zip -X -0 highcharts-test.zip mimetype
zip -X -0 -r highcharts-test.zip META-INF OPS
```
