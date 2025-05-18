[日本語版 README はこちら](README-ja.md)

# Simple SCART Switch

This is a switcher that can switch between two SCART inputs.

Cheap SCART switchers sold at AliExpress for less than 1000 Japanese yen only support composite and not RGB.<br>
Most SCART switchers that support RGB have more input terminals than necessary, so they take up a lot of space and are expensive.<br>
Therefore, I designed a simple 2-input switcher that supports RGB.

![SimpleScartSwitch](doc/SimpleScartSwitch.jpg)

## How to Build

### Required Parts

- SCART plug 2 pcs
    - https://ja.aliexpress.com/item/1005006514947794.html
- SCART socket 2 pcs
    - https://ja.aliexpress.com/item/1005007196215986.html
- switch (8PDT, 1 Row) 1 pc
    - https://ja.aliexpress.com/item/4000353452952.html
    - https://www.amazon.co.jp/dp/B0D8HYP276
- pan head screw (M3, 6-15mm) 2 pcs
- pan head screw (M3, 8-15mm) 4 pcs
- cushion rubber 4 pcs

### Ordering PCBs

Upload gerber.zip to a board manufacturer's website and order the board.<br>
For JLCPCB, it is recommended to select "Yes" from the "Remove Order Number" options.

### Printing Cases

Print top.stl, bottom.stl and plug_cap.stl with a 3D printer.<br>
If the switch does not come with a cap, please also print switch_cap.stl.

### Assembly

1. Place pieces of paper between the pins of the SCART plugs and the board,<br>
   and temporarily fix the SCART plugs with cellophane tape or similar.
2. Solder the pins on both ends of the SCART plugs.
3. Remove the tape and paper and solder the remaining pins of the SCART plugs.
4. Solder the switch.
5. Solder the SCART sockets.
6. Fasten the board to the case with two screws.
7. Close the case with four screws.
8. Attach cushion rubber to the four corners of the bottom.

![1](doc/1.jpg)
![3-5](doc/3-5.jpg)

## How to Use

- Connect either the left or right plug to the output destination device.<br>
  (Do not use both left and right plugs at the same time.)<br>
  You can align the wiring direction by using the right side plug when connecting to the RetroTINK-5X Pro or the left side plug when connecting to the RetroTINK-4K Pro.
- Put the cap on the plug of the one not in use.
- Connect input sources such as game consoles to the sockets on the top.
- You can switch inputs with the switch on the front.

![3-5](doc/RT5XPRO.jpg)
