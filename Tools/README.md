# TTMesh-Development-Kit

## About

Here are some development tools for mesh kit. You can obtain the newest version from 
http://www.telink-semi.cn/ 
You can also contact us by email:
info@techturbo.io 

## Flash programmer
unzip wtcdb.zip
1. Only for observing memory values
2. Only support WIN7,and higher versions of Windows.

### How to use?
1. Unzip the package on windows. Run the program wtcdb.exe
2. Click "BIN" right above the window to choose the directory of your bin file.
3. Plug you target board "mesh node" or "mesh gateway" to the USB host,make sure J1 switch to 5V.
3. Click "RstMCU" to check if the target board is connected.
4. Click "EraseF" to erase the chip after chip resetting.
5. Choose the correct bin file from the left list box.
6. Click "SWB" to start program the chip.
7. You can power on the target board again or click "Reboot" to run the new program.
Please refer to wtcdb.png

## SIG Mesh PC Tools
SIG Mesh PC Tool.zip

### Preparation
1. Unzip the package on windows. Run the program sig_mesh_tool.exe
2. Choose "TT_DevKit_SigMesh_UART_GW.bin" or "TT_DevKit_SigMesh_USB_GW.bin" for you gateway board
 
### How to use gateway by UART?
1. Plug the gateway to PC's USB port
2. Make sure the switch gateway to "CH340"
3. Run the "sig_mesh_tool.exe"
4. Choose "tl_node_gateway.ini", refer to step 1
5. Click "UART", Choose the corresponding "COMx",then connect it.
6. Click "SetPro_Internal" to set the gateway when first time to use or after firmware programming.
7. Click "Scan" to get the unprovisoned mesh device, double click it to choose.
8. Click "Provision", You can manually change the unicast_addr,01 00 means 0x0001,ff 00 means 0x00ff
9. Click "bind_all" to bind all APP Key after provisioning
10. Click Mesh to see the mesh devices and control them, You can click the light on/off in the list


### How to use gateway by USB?
1. Plug the gateway to PC's USB port
2. Make sure the switch gateway to "8269"
3. 3~10 steps are the same as above

Please refer to UART_Gateway01~2.png
## Author
Jack Tian
Contact: techturbo <info@techturbo.io>

## License

The TTMesh-Development-Kit is available under BSD 3-Clause license. See the LICENSE file for more info.
