# IR Pen

A PCB created to send IR signals to TVs. You click a button and it uses 
TV-B-Gone firmware to cycle through all IR signals until a TV turns off. A custom 3d printed shell will go around it hiding the pcb. 

## Parts List

- **10440 Lithium Battery 3.7V** — power source that slides into pen body — [Amazon](https://www.amazon.com/dp/B0H1LNY5LW)
- **USBasp Programmer** — for flashing firmware via ISP pads — [Amazon](https://rb.gy/d68i6x)
- **Tactile Button** — trigger to fire IR codes — [DigiKey](https://www.digikey.com/en/products/detail/c-k/PTS526SM15SMTR2-LFS/10056625)
- **10µF Capacitor** — handles big voltage dips — [DigiKey](https://www.digikey.com/en/products/detail/murata-electronics/GRM155R60J106ME05D/11500166)
- **100nF Capacitor** — smooths out voltage spikes — [DigiKey]([link](https://www.digikey.com/en/products/detail/murata-electronics/GRM155R61A104KA01D/587212?s=N4IgTCBcDaIOICUCyBGArGhA2FBBFADACwDSuBKAIiALoC%2BQA))
- **33Ω Resistor** — limits current to IR LED — [DigiKey](link)
- **3.3kΩ Resistor** — keeps charging at 300mA — [DigiKey](link)
- **10kΩ Resistors x2** — keeps ATtiny RESET and button pin stable — [DigiKey](link)
- **USB-C Connector** — charges the battery — [DigiKey](link)
- **2N7002 MOSFET** — switch that drives the IR LED — [DigiKey](link)
- **Keystone 5223** — battery spring contact — [DigiKey](link)
- **TSAL6400** — IR LED — [DigiKey](link)
- **MCP73831T** — battery charger IC — [DigiKey]([link](https://www.digikey.com/en/products/detail/microchip-technology/MCP73831T-2ATI-OT/964303))
- **ATtiny85-20SU** — main microcontroller — [DigiKey](link)
