

## Disclaimer
This project is intended for educational and research purposes only. It should be used responsibly and only in environments where you have permission to transmit infrared signals.
##
I created a PCB created that sends IR signals to TVs. You click a button and it uses TV-B-Gone firmware to cycle through all IR signals until a TV turns off. A custom 3d printed shell goes around it hiding the pcb. All kicad files and 3d print files linked. I had created this project because I was playing around with my flipper zero and thought how funny it was to when I turned the tv off when my dad was watching. It gave me motiavtion to create something of my own, so which i did. Overall I hope you enjoy playing around with my desgin!
PCB fits through my 3d printed shell and should fit there tightly but shouldn't fall out. Its diamater is 13mm and its 133mm in height. 
##
Firmware created by Mitch Altman and adafruit [TV-B-Gone](https://github.com/adafruit/TV-B-Gone-kit)
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
- Downloadable CSV up top
##


<img width="1920" height="1243" alt="Screenshot 2026-05-26 at 2 52 33 PM" src="https://github.com/user-attachments/assets/a79d61ec-33b2-4797-a138-3cb624aef762" />








<img width="1920" height="1243" alt="Screenshot 2026-05-26 at 11 50 53 AM" src="https://github.com/user-attachments/assets/32a7bac0-3cbe-4502-9f4a-1d0c15e3476d" />
<img width="863" height="600" alt="Screenshot 2026-05-27 at 10 30 16 PM" src="https://github.com/user-attachments/assets/f663e532-cd38-442f-bdd8-42e96c2d6e1c" />
