# ThunderKILL

ThunderKILL is based on the [Thundervolt](https://github.com/mackieks/thundervolt/tree/main) by [YveltalGriffin](https://github.com/mackieks) an open source platform for undervolting the Nintendo Wiis.
ThunderKILL takes the original concept and tries to go overkill with more features explicitly not inculded in the Thundervolt.
### New features:
- USB-C Power delivery
- Battery charge controller
- Fan and temperature controller
- RGB LED controller
- Current sensing
- 5V boost regulator
- E-Fuse on the PD power in
- Resettable fuse on the battery connection

### Existing features from Thundervolt:
- 1V buck regulator
- 1.15V buck regulator
- 1.8V buck regulator
- 3.3V buck boost regulator

All regulators are I2C controlled and high efficiency (η > 90%) and can be(/will be) controllable from a homebrew app. Along with the data from the I2C current/voltage/power sensing and temperature sensing of the board and the Wii.
The ThunderKILL has significantly more output pads than the original Thundervolt, as it is designed to integrate with other boards beyond the Wii itself, supplying easily available power, along with all the new features like PD negotiation, fan and LED outputs.

### ToDo:
- Final pass on board
- Send to printing
- Solder components
- Develop firmware
- Test in isolation
- Test on Wii
- Develop homebrew app

### NOTE: ThunderKILL is still in the prototype phase, and is untested, and the firmware for it has yet to be developed. I don’t recommend manufacturing ThunderKILL PCBs until development and testing are complete. This project is currently only for reference.

(This github page is still WIP, and will change as the project continues)

## Screenshots

<img src="Images/TopRender.png" width="600" />

<img src="Images/BottomRender.png" width="600" />

<img src="Images/TraceView.png" width="600" />

## Credits

ThunderKILL hardware designed by [RoseDaggerDev](https://github.com/RoseDaggerDev)

Original Thundervolt credits:

Thundervolt hardware designed by [YveltalGriffin](https://github.com/mackieks)

Thundervolt firmware by [loopj ](https://github.com/loopj)

Thundervolt homebrew by:
- [YveltalGriffin](https://github.com/mackieks) (UI, app)
-  [loopj ](https://github.com/loopj) (I2C, app)
-  [Alex/supertazon](https://github.com/supertazon) (graphics)
-  [ShockSlayer ](https://github.com/ShockSlayer) (music)

## License

ThunderKILL hardware is licensed under Solderpad Hardware License v2.1.
