# RoadHaze Cam

## The camera must have a `cam-config.json` file to work:

```
{
  "id": null | string -> initially null, after making contact with the server an id will be assigned to the device,
  "name": string -> the name of the camera,
  "s_url_init": string -> url to endpoint to initialize the device,
  "s_url": string -> url to endpoint for sending data,
  "lat": float -> latitude of camera,
  "lon": float -> longtitude of camera
}
```
