# ecoviz widget

This JavaScritp widget retrieves and displays air quality and noise data from Google Fusion Tables. It is invoked using an IFRAME tag as follows. Pass your table id and key accordingly.

```
<iframe id="ecoviz" width="650" height="840" scrolling="no" marginheight="0" marginwidth="0" frameborder="0" src="/widget/ecoviz.html?table=YOUR_TABLE_ID&key=YOUR_KEY">
</iframe>
```

The Google Fusion table returns the following attributes for each measurement:

* ts
* Lon
* Lat
* COx
* Noise
* NOx

The [ecotool](https://github.com/jdevoo/ecotool) script can be used to create the file.
