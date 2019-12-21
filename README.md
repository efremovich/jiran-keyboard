# Jiran Keyboard
Jiran is a 6x4 matrix ergo keyboard with additional 3 thumb and 1 pinky keys. 

Based on the [Jian keyboard](https://docs.google.com/forms/d/e/1FAIpQLSdwGvwtzIbPnHGXDWHnTBHZ2Rppxo7zm2IfQFo6qOxk6CD4sg/viewform).

<img src="https://raw.githubusercontent.com/Ladniy/jiran-keyboard/master/Pcb/Design/Pcb.png" data-canonical-src="Render" height="300"/>

* __Layout:__ [keyboard-layout-editor.com](http://www.keyboard-layout-editor.com/#/gists/0547cd126f61f8c3f76b0a9952901da4)
* __Hardware Availability:__ open source, t.me/ladniys
* __Link to firmware:__ not available yet
* __Building guide:__ not available yet
* __BOM:__

| Name           | Value         | Package           | Count        | Optional  | Comment            |
| :------------- | ------------: | :---------------- | -----------: | :-------- | :----------------- |
| Pro micro      | 5V 16MHz      |     17.78x33.02mm | 2            |           |                    |
| Switch         |               | MX/Alps/Choc      | 56           |           |                    |
| Diode          | 1N4148        | THT/SMD (SOD-123) | 56           |           |                    |
| Resistor       | 4.7k          | THT/SMD (0805)    | 2            |           | Must be placed on the master half |
| TRRS jack      |               | PJ-320A           | 2            |           | Optional if you're building only one half  
| Tact switch    |               | DIP 3X6X4,3mm     | 2            |  yes      |                    |
| Mosfet         | 2N7002        | SOT-123           | 2            |  yes      | Optional for LED's |
| Resistor       | 10k           | THT/SMD (0805)    | 2            |  yes      | Optional for LED's |
| Resistor       | 330           | THT/SMD (0805)    | 56           |  yes      | Optional for LED's |
| LED            |               | THT 1.8mm         | 56           |  yes      | Optional           |
