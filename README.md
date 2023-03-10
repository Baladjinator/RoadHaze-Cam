# RoadHaze Cam

## The camera must have a `cam-config.json` file to work:

```
{
  "id": null | str -> initially null, after making contact with the server an id will be assigned to the device,
  "name": str -> the name of the camera,
  "s_url_init": str -> url to endpoint to initialize the device,
  "s_url": str -> url to endpoint for sending data,
  "lat": Optional[float] -> latitude of camera,
  "lon": Optional[float] -> longtitude of camera
}
```

Note: Those properties, marked with optional, are not needed if a gps module is connected to the device.

