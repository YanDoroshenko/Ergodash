# Ergodash

`Note: Information as of September 2020, shipping withing the EU`

## General notes
* I decided to go with a partially assembled PCB to save myself some time (and grief) due to my lack of soldering skills.
* Parts list is for a big thumb cluster with 2 2u keys (LAYOUT_3key_2us) in [QMK configurator](https://config.qmk.fm/), you don't have to use the stabilizers and you don't need them at all if you don't have 2u keys.
* There are only 6 backlit keys in my build (Caps Lock and layer indicators), you need to have a LED and a 470RΩ resistor for each backlit key.

## Parts list
`Note: Doesn't include keycaps`

`Note: I used metal film resistors for the backlight, but it shouldn't matter`

| Name | Notes | Total Price | Shipping | Total |
|:----:|:-----:|:-----------:|:--------:|:-----:|
| [PCB](https://falba.tech/product/ergodash-partially-assembled-with-electronics-cables/?v=928568b84963) | Partially assembled and comes with a TRPS cable | 50 € | 12 € | 62 € |
| [Case](https://keycapsss.com/keyboard-parts/cases/76/ergodash-acrylic-plate-case?c=12) || 32.9 € | 8.90 € | 41.8 € |
| [Switches](https://candykeys.com/product/cherry-mx-blue-plate-m) | 100x, but you only need around 70 | 42 € | 7 € | 49 € |
| [Stabilizers](https://candykeys.com/product/genuine-cherry-mx-stabiliser-pack-plate-mount) | 4x 2u, plate mounted | 9 € | -- | 9 € |
| 2x [Mosfet](https://www.tme.eu/cz/details/irlml6344trpbf/tranzistory-s-kanalem-n-smd/infineon-irf/) | IRLML6344TRPBF | ~0.25 € | 1 € | ~1.25 € |
| 6x [LED](https://www.tme.eu/cz/details/ww03a3swq4-n2/led-diody-tht-3mm/wah-wang-holding/) | Ø 3mm | ~0.6 € | -- | ~0.6 € |
| 2x [1KΩ resistor](https://www.gme.cz/rm-1k-0207-0-6w-1)| 6.3x2.4mm, 0.6W | ~0.2 € | -- | ~0.2 € |
| 6x [470Ω resistor](https://www.gme.cz/rm-470r-0207-0-6w-1)| 6.3x2.4mm, 0.6W | ~0.6 € | -- | ~0.6 € |
| 2x [Pro Micro clone](laskarduino.cz/arduino-leonardo-pro-micro/) | It's said that you can use [Elite-C](https://keeb.io/products/elite-c-low-profile-version-usb-c-pro-micro-replacement-atmega32u4) if you want USB Type C | ~12 € | ~1.2 € | ~13.2 € |

Additionally you will need some feet, an optional [dampening foam](https://switchandclick.com/2020/08/26/the-best-dampening-foam-for-a-mechanical-keyboard/) as well as a Micro USB cable.

#### Keycaps
There are not so many sources of dedicated Ergodash keycaps. Here are the ones I've found: 
* [OhKeycaps](https://ohkeycaps.com/collections/dsa-blanks/products/dsa-pink-purple?variant=29211011711087) (small thumb cluster version)
* [FalbaTech](https://falba.tech/product/dsa-keycaps-black-blank-left-right-keyboards-redox-copy/?v=928568b84963)

## Build process

## Resources
[Official Ergodash build](https://github.com/omkbd/ErgoDash/blob/master/Doc/build-en.md)

[Ergodash build video by Daihuku Keyboard](https://www.youtube.com/watch?v=yHgvEU0NYCk)
