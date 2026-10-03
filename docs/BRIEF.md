# 5V LED indicator PCB

Create a complete PCB design project for a simple 5V LED power indicator.

Electrical requirements:
- Input: 9V to 12V DC
- Output: regulated 5V DC
- U1: LM7805 TO-220 linear voltage regulator
- J1: 2-pin through-hole screw terminal for DC input
- J2: 2-pin through-hole screw terminal for 5V output
- D1: 5mm through-hole LED
- R1: 1k ohm through-hole resistor
- C1: 10uF electrolytic capacitor on the regulator input
- C2: 10uF electrolytic capacitor on the regulator output

Schematic:
- Create an actual electrical schematic with all components and nets.
- J1 positive connects to U1 IN.
- J1 negative connects to GND.
- U1 GND connects to GND.
- U1 OUT creates the +5V net.
- J2 positive connects to +5V.
- J2 negative connects to GND.
- Connect R1 in series with D1 between +5V and GND.
- Connect C1 between U1 IN and GND.
- Connect C2 between +5V and GND.
- Add net labels: VIN, GND, +5V, LED_A, LED_K.

PCB:
- Generate an actual 2-layer PCB layout from the schematic.
- Use through-hole components.
- Place J1 and J2 along the board edge.
- Place U1 near the input connector.
- Keep C1 close to U1 input and C2 close to U1 output.
- Place the LED and resistor where they are visible.
- Route all connections.
- Use a bottom-layer GND copper pour.
- Add four M3 mounting holes.
- Board size approximately 60mm x 40mm.
- Add silkscreen labels: VIN, GND, +5V, INPUT, OUTPUT, POWER.

Deliverables:
1. Electrical schematic
2. PCB layout
3. Component/footprint assignments
4. BOM
5. Design-rule-check results
6. Connectivity/ERC validation results

Do not create a documentation-only project. The schematic and PCB must be actual design artifacts with electrical connectivity.
