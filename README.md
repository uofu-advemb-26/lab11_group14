# Lab 11 Results
## Advertising
![Activity 0 Advertising](./images/advertising.png "Activity 0 Advertising")

## Attributes, Services, & Characteristics
![Activity 1 Services](./images/services.png "Activity 1 Services")
  - Services and characteristics match those configured in `gatt_counter.gatt` and their values update correctly following `gatt_counter.c`.

![Activity 1 Device Name](./images/gap_device_name.jpg "Activity 1 Device Name")
  - iOS restricts access to the GAP service such that applications can't access its characteristics, so we were unable to read the `GAP_DEVICE_NAME` characteristic from our iOS scanner application. However, we verified its value using `bluetoothctl` on Linux, as shown above.