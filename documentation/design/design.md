# Design

- [Design](#design)
  - [Requirements](#requirements)
    - [Application](#application)
      - [Image Marker](#image-marker)
    - [Tabernacle](#tabernacle)

AR Tabernacle will display a life sized tabernacle using augmented reality based on a location marker.

## Requirements

There are two main components - the application and the model of the tabernacle.

### Application

The prime focus of the application is the display of the tabernacle. No user customization or extra features are required.

The application must run on iOS devices. Android and Windows devices are not yet required. 

When the application loads, the user should first locate the image marker. Once located, the tabernacle should be displayed based on the location and orientation of the marker. The image marker should correspond to the center of the altar.

#### Image Marker

The following image[^1] should be used as the marker:

![Image Marker](images/image_marker.png)

[^1]: QR Code generated using https://www.qrcode-monkey.com/

### Tabernacle

The tabernacle will be represented using a 3D model. The model should be based on the description as found in the Bible book of Exodus chapters 25-27, 30, 36-38 and 40.

The measurements will be based on a cubit being 44.5cm in length.

See [here](tabernacle.md) for designs of the tabernacle.
