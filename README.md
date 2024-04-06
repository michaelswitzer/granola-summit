# Summit by Granola Arcade

![Summit fightstick](/Images/summit.jpg "Summit fightstick")

The Summit is a button box style arcade controller by Granola Arcade.

You can buy the Summit at https://granola.games

## License
The Raindrop is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>. In simple terms, this means you are welcome to use or remix these designs to build your own controller free of cost. You are *not* permitted to sell the Summit commercially. You also can't republish the designs without attribution and without carrying this license forward into your new designs. For more information see the license file in this repository.

## How to build
To build your own Summit, import the PCB designs and bill of materials using KiCAD. I provided a list of parts that use JLCPCB's part assembly services, since that is the company I use to manufacture the PCB. You can use these files as a starting point for building your own PCB.

The .step file for the case is optimized for FDM 3D printers. I recommend PLA with at least 15% infill but you can use any material you wish. The case has designed break-away supports that you will remove after printing. It should already be aligned in the correct orientation.

The keycap files are also included, for use with Kailh Choc V2 stems (MX style). You may need to adjust the x-y hole and contour compensation values in your slicer for proper fitment.

You will need to source your own key switches. The Summit uses Kailh low-profile Choc keyboard switches.

Once you have the case, switches and keycaps, you simply slide the PCB into the top of the case and then attach the switches and keycaps to assemble. Then plug the controller into your PC and upload the firmware.

## Firmware
The Summit is designed to use the <a rel="GP2040-CE firmware" href="https://github.com/OpenStickCommunity/GP2040-CE">GP2040-CE firmware</a>.

## Credits
The Raindrop was designed by Michael Switzer. The GP2040-CE firmware is maintained by <a href="https://github.com/OpenStickCommunity">OpenStickCommunity</a>. This project was inspired by the <a href="https://github.com/jfedor2/flatbox">Flatbox</a>.