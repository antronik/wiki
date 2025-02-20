# OpenIPC Wiki
[Table of Content](../index.md)

Supported devices
-----------------

Unfortunately, we cannot provide you a long list of devices that are undoubtedly
compatible with our firmware. Camera manufacturers tend to change hardware
design and swap components even within the same model line, without any notice.

Below, we listed some of the cameras we had in our possession, but again, there
is no guarantee that if you'll buy one of those cameras today you won't end up
with an unsupported hardware on your hands.

Somewhat working method to determine if your camera is supported by the recent
version of our firmware is to open[^1] the camera case and take a look at the
chip markings. Then look up your chip in the [list of supported hardware][1]
and check its development status.

If you still have your doubts, take hi-res pictures of the hardware close-ups
and ask for help in one of our Telegram groups.

[^1]: Attention! Doing so, you are taking full responsibility for your actions.
Most likely, opening the case will void the warranty of the device. We cannot
be held liable for any damage to the camera, yourself, your house, your pets,
or anything else. If you don't feel comfortable around hardware, this project
may not be right for you.

_If you have another supported device to add, please do it [here][2]._

| Brand    | Model              | Processor   | Sensor | Flash Memory | LAN | WLAN       | USB  | Card |
|----------|--------------------|-------------|--------|--------------|-----|------------|------|------|
|          |                    |             |        |              |     |            |      |      |
| Anjoy    | MS-J10             | SSC335      | IMX307 |              | Yes | No         | Yes  | No   |
| Anjoy    | YM-J10D            | SSC337      | IMX307 |              | Yes | No         | Yes  | No   |
|          |                    |             |        |              |     |            |      |      |
| Chacon   | [IPCAM-RI01][3]    | HI3518EV300 | JXF23  | XM25QH128A   | No  | RTL8188FTV | WiFi | Yes  |
|          |                    |             |        |              |     |            |      |      |
| LTV      | CNE-724 48         | HI3516EV200 |        |              | Yes | No         | No   | Yes  |
|          |                    |             |        |              |     |            |      |      |
| Rotek    | Switcam HS303 (v1) | HI3518EV200 |        |              | No  | RTL8188FU  | WiFi | Yes  |
| Rotek    | Switcam HS303 (v2) | HI3518EV200 | OV9732 | GD25Q128CSIG | No  | RTL8188EU  | WiFi | Yes  |
| Rotek    | Switcam HS303 (v3) | HI3518EV200 |        |              | No  | RTL8188EU  | WiFi | Yes  |
|          |                    |             |        |              |     |            |      |      |
| Xiaomi   | MJSXJ02HL          | HI3518EV300 |        |              | No  |            |      | Yes  |
|          |                    |             |        |              |     |            |      |      |
| XM       | BLK18EV-0062-0035  | HI3518EV200 | JXH62  |              | Yes |            |      | Yes  |
|          |                    |             |        |              |     |            |      |      |
| Zenotech | HI3516D_MB_V13_RA  | HI3516DV100 | OV9689 | GD25Q128CSIG | Yes | No         |      | No   |



| Processor   | Sensor           | Vendor     | SKU          | Board identification            |
|-------------|------------------|------------|--------------|---------------------------------|
| Hi3516Cv100 | IMX222_spi_dc    | XM         |              | [BLK18C-0222-38X38_S-V1.03][1]  |
| Hi3516Cv100 | OV2710_i2c_dc    | Jovision   |              | IPG5020A-H-V1.0                 |
|             |                  |            |              |                                 |
| Hi3516Cv200 | IMX323_i2c_dc    | XM         |              | BLK16CV-0323-38X38-V1.01        |
| Hi3516Cv200 | IMX323_i2c_dc    | JVT        | S323H16VF    | IPS323-H16V-38X38-V2            |
| Hi3516Cv200 | IMX323_i2c_mipi  | XM         |              |                                 |
|             |                  |            |              |                                 |
| Hi3516Cv300 | AR0237_i2c_dc    | XM         |              | BLK16CV3-0237P-38X38-S-V1.01    |
| Hi3516Cv300 | IMX307_i2c_lvds  | Raysharp   |              | RS-CM-188D 2018-03-16 E150111   |
| Hi3516Cv300 | IMX323_i2c_dc    | Longse/HS  |              | HI3516CV300-IMX323-POE-TF V1.1  |
| Hi3516Cv300 | IMX323_i2c_dc    | Sunywo     | ZB6323       | IPG5020A-T-N6-V0.1              |
| Hi3516Cv300 | IMX323_i2c_dc    | XM         |              | IVG-HP201Y-AE                   |
| Hi3516Cv300 | IMX291_i2c_lvds  | XM         |              | IVG-HP203Y-AE                   |
| Hi3516Cv300 | IMX323_spi_dc    | JVT        | S323H16XF    | IPS323-H16X-38X38-V2/V3         |
| Hi3516Cv300 | JXF22_i2c_dc     | XM         |              | BLK16CV3-0022-38X38-S-V1.01     |
|             |                  |            |              |                                 |
| Hi3516Ev100 | IMX323_i2c_dc    | XM         |              | BLK16E-0323-38X38-B-V1.01       |
| Hi3516Ev100 | SC2235P_i2c_dc   | XM         | 80HE20PS-S   | BLK16E-0235-38X38-S-V2.03       |
|             |                  |            |              |                                 |
| Hi3516Ev200 | IMX307_i2c_mipi  | XM         |              | IVG-85HF20PY-S                  |
| Hi3516Ev200 | SC4239P_i2c_mipi | XM         |              | IVG-85HF30PS-S                  |
|             |                  |            |              |                                 |
| Hi3516Ev300 | IMX335_i2c_mipi  | XM         |              | IVG-85HG50PYA-S                 |
|             |                  |            |              |                                 |
| Hi3518Ev100 | OV9712_i2c_dc    | CamHi/Xin  |              | IPC18E_9712_V2.0/V3.1           |
|             |                  |            |              |                                 |
| Hi3518Ev200 | AR0130_i2c_dc    | XM         |              | BLK18EV-0732-0035-38X38-V1.01   |
| Hi3518Ev200 | JXF22_i2c_dc     | XM         |              | BLK18EV-0002-2035-38X38-V1.01   |
| Hi3518Ev200 | JXF22_i2c_dc     | XM         |              | BLK18EV-0022-0130-38X38-V1.01   |
| Hi3518Ev200 | OV2735_i2c_dc    | Dahua      | DH-IPC-C22P  | E305654 JX02 94V-0              |
| Hi3518Ev200 | OV9732_          | XM         |              | BLK18EV-0732-0035-38X38-V1.01   |
| Hi3518Ev200 | OV9732_i2c_dc    | Longse/HS  | LS-IP100/40  | 3518EV200-OV9732-V1.0           |
| Hi3518Ev200 | OV9732_i2c_dc    | Rostelecom | QVC-IPC-136W | E305654 JX02 94V-0              |
| Hi3518Ev200 | SC2135_i2c_dc    | XM         |              | BLK18EV-0035-0042-38X38_S-V1.01 |
| Hi3518Ev200 | SC2235_i2c_dc    | XM         |              | BLK18EV-0235-38X38-B-V1.01      |
|             |                  |            |              |                                 |
|             |                  |            |              |                                 |
| SSC335      | SC3335           | Uniview    |              | Uniview                         |



[1]: https://github.com/OpenIPC/firmware#current-development-status-
[2]: https://github.com/OpenIPC/wiki/blob/master/en/guide-supported-devices.md
[3]: https://github.com/OpenIPC/wiki/blob/master/en/device-chacon-ipcam-ri01.md
