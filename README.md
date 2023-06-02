# 60percent

**60percent** (quite original, I know) is a 3D printed, handwired keyboard powered by [ZMK](https://zmk.dev/) inspired by the [tokyo60](https://tokyokeyboard.com/tokyo60/). If you are new to handwiring, [worry not](https://geekhack.org/index.php?topic=87689.0).

![60percent top](/images/60percent_top.jpg)
![60percent side](/images/60percent_side.jpg)
![60percent USB](/images/60percent_usb.jpg)

## Required Parts

| Part                                                                                       | Qty   | Description                                                                      |
| ------------------------------------------------------------------------------------------ | ----- | -------------------------------------------------------------------------------- |
| [Challenger 840 BLE](https://ilabs.se/product/challenger-840-ble/)                         | 1     | Micro controller board with Bluetooth LE                                         |
| MX-style switches of your choosing                                                         | 60    | I used Outemu Lemon/Limes.                                                       |
| [1N4148 Diodes](https://a.aliexpress.com/_msALIYo)                                         | 60    | You need these for handwiring                                                    |
| [Keycaps](https://a.aliexpress.com/_mt4GitK)                                               | 1 set | You will need a 7u spacebar in the set                                           |
| Cherry [stabilizers](https://a.aliexpress.com/_mOCfD7K)                                    | 1 set | Requires 1 x 7u and 2 x 2u                                                       |
| Wires                                                                                      | -     | I used wrapping wires                                                            |
| [M2 x 6mm hex female-to-female brass standoff (spacer)](https://a.aliexpress.com/_mO2uQEM) | 5     | This is what supports/holds down the plate and the case together                 |
| M2 x 12mm [countersunk screws](https://a.aliexpress.com/_msph8rW)                          | 2     | Case-side that goes with the brass standoff                                      |
| M2 x 10mm [countersunk screws](https://a.aliexpress.com/_msph8rW)                          | 3     | Case-side that goes with the brass standoff                                      |
| M2 x 6mm [flat top screws](https://a.aliexpress.com/_mqwmkN6)                              | 5     | Plate-side that goes with the brass standoff                                     |
| M2 x 6mm [countersunk screws](https://a.aliexpress.com/_msph8rW)                           | 4     | Holds the MCU down                                                               |
| M2 hex [nut](https://a.aliexpress.com/_m0uPPtO)                                            | 4     | Holds the MCU down                                                               |
| 3.7v LiPo Battery                                                                          | 1     | You'll have to source this locally, as batteries aren't shipped overseas usually |
| [JST 2.0 PH Connector](https://a.aliexpress.com/_mMpUkq8)                                  | 1     | Required if the battery doesn't come with compatible connection                  |

Note: The countersunk screws are all the same link. The screws, standoff, and the nut are from the same seller. These are all links that I bought from to build my keyboards.

## Diagrams

Below, you can find the rows and columns I wired to the Challenger 840 BLE and the way I wired my columns. I only drew the columns, probably more useful flipped (as the backside of the board is wired), which is also included. I highly encourage you to map your own columns, as I'm worried that it'll be harder to follow mine.
![Pinout diagram](/images/pinout-diagram.png)
![Row column mapping](/images/row_col.png)
![Row column mapping flipped](/images/row_col_flipped.jpg)
