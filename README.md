# BNC-ifier User Guide

## Usage

To connect your Basler camera to the BNC-ifier you should have a cable with the connector of your camera on one end and open pins on the other end.
If you do not know which of the open pins refer to which of the pins of the camera connector, please refer to this [section](#finding-out-the-connections-of-the-cable).

You can find the pin numbering of your camera by going to the image your camera in the pin_numbering folder.
To find out which Camera pin has to be connect to which Bnc-ifier pin please refer to this [site](https://ibehave-cadre.github.io/BNC-ifier). You can also find out which how the camera pins are numbered there.
If this site does not work, please refer to the `cameras.csv` file in this repository.

1. Connect the camera pin to the corresponding pin of the BNC-ifier Box.
2. Unscrew the top of the BNC-ifier and open the lid.
3. You can see multiple pin headers. There is a pin header for each line. It selects what ground to use for the pin. Please set them to the corresponding ground found in the table for each line.
> [!TIP]
> If there is no ground (GND) for the line in the table it does not matter how the pin header is set.
4. If you want to connect more cameras to a trigger signal you can select which line gets send to the output of the BNC-ifier via the pin header at the output. Please also select the corresponding ground. It should be the same as the line you selected.
5. Place the lid back on the BNC-ifier and screw it on.


## Finding out the connections of the cable

> [!NOTE]
> Your cable should have come with some documentation to tell you, which color corresponds to which pin.

To find which pins of the connector correspond to which open pin on the other end of the cable you will need to have a multimeter.

1. Set the multimeter to Continuity Mode. It should beep when you touch the probes together.
2. Connect one of the probes to the first pin. With the other probe touch each of the open pins until you hear the multimeter beep. Write down the which color corresponds to the pin number.
3. Repeat for all pins.

> [!TIP]
> Some pins might be unconnected.

## Commercial Parts List

| Item | Quantity | Notes | Product Example Link |
| :---: | :---: | :---: | :---: |

## Stackable Case Parts

| Item | Quantity | Notes | Product Example Link |
| :---: | :---: | :---: | :---: |

## Rack Mounting Case Parts

| Item | Quantity | Notes | Product Example Link |
| :---: | :---: | :---: | :---: |



Wiring Diagram
--------------------

<p align="center">
  <img src="./Images/Wiring_Diagram.png" width="800">
</p>

