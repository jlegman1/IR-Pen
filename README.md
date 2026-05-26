# IR Pen

A PCB created to send IR signals to TVs. You click a button and it uses 
TV-B-Gone firmware to cycle through all IR signals until a TV turns off. A custom 3d printed shell will go around it hiding the pcb. 

## Parts List

- **100nF Capacitor** — smooths out voltage spikes — [DigiKey](link)
- **33Ω Resistor** — limits current to IR LED — [DigiKey](link)
- **3.3kΩ Resistor** — keeps charging at 300mA — [DigiKey](link)
- **10kΩ Resistors x2** — keeps ATtiny RESET and button pin stable — [DigiKey](link)
- **USB-C Connector** — charges the battery — [DigiKey](link)
- **2N7002 MOSFET** — switch that drives the IR LED — [DigiKey](link)
- **Keystone 5223** — battery spring contact — [DigiKey](link)
- **TSAL6400** — IR LED — [DigiKey](link)
- **MCP73831T** — battery charger IC — [DigiKey](link)
- **ATtiny85-20SU** — main microcontroller — [DigiKey](link)
