# IR Pen

A PCB created to send IR signals to TVs. You click a button and it uses 
TV-B-Gone firmware to cycle through all IR signals until a TV turns off. A custom 3d printed shell will go around it hiding the pcb. All kicad files linked. 3D print desgin not out yet 

## Parts List

- **10440 Lithium Battery 3.7V** — power source that slides into pen body — [Amazon](https://www.amazon.com/dp/B0H1LNY5LW)
- **USBasp Programmer** — for flashing firmware via ISP pads — [Amazon](https://rb.gy/d68i6x)
- **Tactile Button** — trigger to fire IR codes — [DigiKey](https://www.digikey.com/en/products/detail/c-k/PTS526SM15SMTR2-LFS/10056625)
- **10µF Capacitor** — handles big voltage dips — [DigiKey](https://www.digikey.com/en/products/detail/murata-electronics/GRM155R60J106ME05D/11500166)
- **100nF Capacitor** — smooths out voltage spikes — [DigiKey](https://www.digikey.com/en/products/detail/murata-electronics/GRM155R61A104KA01D/587212?s=N4IgTCBcDaIOICUCyBGArGhA2FBBFADACwDSuBKAIiALoC%2BQA)
- **33Ω Resistor** — limits current to IR LED — [DigiKey](https://www.digikey.com/en/products/detail/yageo/RC0402JR-0733RL/726467)
- **3.3kΩ Resistor** — keeps charging at 300mA — [DigiKey](https://www.digikey.com/en/products/detail/panasonic-industry/ERA-2AEB332X/1706017)
- **10kΩ Resistors x2** — keeps ATtiny RESET and button pin stable — [DigiKey](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/RMCF0402FT10K0/1761433)
- **USB-C Connector** — charges the battery — [DigiKey](https://www.digikey.com/en/products/detail/gct/USB4085-GF-A/9859662?s=N4IgTCBcDaIOIGEAqACAqgZQEIBYAMAHAKwgC6AvkA)
- **2N7002 MOSFET** — switch that drives the IR LED — [DigiKey](https://www.digikey.com/en/products/detail/onsemi/2N7002ET1G/1792136)
- **Keystone 5223** — battery spring contact — [DigiKey](https://www.digikey.com/en/products/detail/keystone-electronics/5223/316374)
- **TSAL6400** — IR LED — [DigiKey](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/TSAL6400/1681340)
- **MCP73831T** — battery charger IC — [DigiKey](https://www.digikey.com/en/products/detail/microchip-technology/MCP73831T-2ATI-OT/964303?s=N4IgTCBcDaILIGEAKB2AzADjQRgCoFowBBXASQHoB5XEAXQF8g)
- **ATtiny85-20SU** — main microcontroller — [DigiKey](https://www.digikey.com/en/products/detail/microchip-technology/ATTINY85-20SU/735470)









![Uploading Screenshot 2026-05-26 at 11.50.06 AM.png…]()


<img width="1920" height="1243" alt="Screenshot 2026-05-26 at 11 50 53 AM" src="https://github.com/user-attachments/assets/32a7bac0-3cbe-4502-9f4a-1d0c15e3476d" />
