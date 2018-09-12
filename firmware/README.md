# TTMesh-Firmwares

## TT_DEV_RGBCW_V1.H.1.0.bin
* property BLE mesh
* default name "TT_Mesh" and password "123"
* RGB color adjustable
* Color temperature adjustable
* lightness adjustable
* color fade in/out
* auto on/off alarm

## TT_DevKit_SigMesh_CT.bin
* SIG mesh light
* color temperature adjustable
* lightness adjustable
* color fade in/out
* auto on/off alarm

## TT_DevKit_SigMesh_USB_GW.bin
* SIG mesh provisioner
* Connect PC with USB
* Support discover device,provision,bind keys
* Node control,delete

## TT_DevKit_SigMesh_UART_GW.bin
* SIG mesh provisioner
* Connect PC with UART
* Support discover device,provision,bind keys
* Node control,delete

## TT_DevKit_SigMesh_HSL.bin
* Support HSL color tuning
* Hue [0,360) ->0~0xffff
* Sat [0,100] ->0~0xffff
* Lightness [0,100] ->0~0xffff
* test command
a3 ff 00 00 00 00 02 00 ff ff 82 76 ?? ?? ?? ?? ?? ?? ??
?? replaced by following data

Black HSL(0,0,0)
00 00 00 00 00 00 00

White HSL(0,0,100)
FF FF 00 00 00 00 00

Red HSL(0,100,50)
FF 7F 00 00 FF FF 00

Lime HSL(120,100,50)
FF 7F 55 55 FF FF 00

Blue HSL(120,100,50)
FF 7F AA AA FF FF 00

YELLOW HSL(60,100,50)
FF 7F AA 2A FF FF 00

CYAN HSL(180,100,50)
FF 7F FF 7F FF FF 00

Magenta HSL(300,100,50)
FF 7F 54 D5 FF FF 00

Silver HSL(0,0,75)
FF BF 00 00 00 00 00

Gray HSL(0,0,50)
FF 7F 00 00 00 00 00

Maroon HSL(0,100,25)
FF 3F 00 00 FF FF 00

Olive HSL(60,100,25)
FF 3F AA 2A FF FF 00

Green HSL(120,100,25)
FF 3F 55 55 FF FF 00

Purple HSL(300,100,25)
FF 3F 54 D5 FF FF 00

Teal HSL(180,100,25)
FF 3F FF 7F FF FF 00

Navy HSL(240,100,25)
FF 3F AA AA FF FF 00

## Author
Contact: techturbo <ai@techturbo.io>

## License

The TTMesh-Development-Kit is available under BSD 3-Clause license. See the LICENSE file for more info.
