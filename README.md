# BTHome nRF sensor template

Template for a [BTHome](https://bthome.io/) sensor in nRF52.

# Building

You need the [nRF Connect SDK](https://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/index.html) to build this sample.

Clone this repo in a folder under the samples folder in the nRF Connect SDK.
To build for the nRF52840 DK run this west build command:

```shell
west build -b nrf52840dk_nrf52840
```

To build for other devices/boards replace nrf52840dk_nrf52840 with the one you want.