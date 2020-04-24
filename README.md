# ecoviz widget

This JavaScript widget retrieves and displays air quality and noise data from a CSV file accessible via an URL. It is invoked using an IFRAME tag as follows.

```
<iframe id="ecoviz" width="650" height="840" scrolling="no" marginheight="0" marginwidth="0" frameborder="0" src="/widget/ecoviz.html?url=URL_TO_CSV_DATA">
</iframe>
```

The CSV file must return the following attributes for each measurement:

* ts
* Lon
* Lat
* COx
* Noise
* NOx

The [ecotool](https://github.com/jdevoo/ecotool) script can be used to create the file.
