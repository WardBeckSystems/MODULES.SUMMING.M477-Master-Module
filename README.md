# M477 · Summing

Ward-Beck Systems M477, 1979|12. Wiki page: [M477 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M477.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 21 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 189 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 3 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 6 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 42 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [15 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1979 - M477 - Master Module.pdf](MANUALS/1979%20-%20M477%20-%20Master%20Module.pdf) page 5 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 8 dB ±0.5 dB (with fader in 15 dB in-hand&quot; position) |
| **Frequency response** | ±0.25 dB from 20 Hz to 20 kHz. |
| **Noise** | 80 dB below +8 dBm nomina ] output Teve] (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.25% from 30 Hz to 20 kHz at +24 dBm output or Tess (Typica]y Tess than 0.05% across Most of band - width.) |
| **Source impedance** |  |
| &nbsp;&nbsp;Summing | 30,000 ohms baLanced. |
| **Input impedance** |  |
| &nbsp;&nbsp;Summing | Less than 5 ohms |
| **At 8-1094 output pins 14 /R** | Les 5 than 100 ohms At outputs #1 and #2: 600 ohms At MONITOR output: 1 200 ohms At METERInG output: 1,200 ohms |
| **Load impedances** | At insertion Point and outputs #1 and #2: 600 ohms balanced At MoNiTOR output: 1,200 ohms At METERING output: 1,200 ohms |
| **Output levels** |  |
| &nbsp;&nbsp;At insertion point | 0 dBm nomina] +30 dBm maximuM At outputs #1 and #2: +8 dBm nomina 1 +24 dBm maximum |
| **Phasing** | Input and output termina ] s designated by numbers are in phase. |
| **Power requirements** | 125 volts dc, 60 ma nominal 200 MA maximum. |
| **Ambient temperature** | 0 to 6 0 degrees Celsius |
| **Dimensions** | 1.6&quot; wide X 7&quot; high X 6,5&quot; deep (41 mm X 178 MM X 165 mm) |

## Circuit description

From [1979 - M477 - Master Module (2).pdf](MANUALS/1979%20-%20M477%20-%20Master%20Module%20(2).pdf) pages 6-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M477 1s designed to receive the mixed feeds fro. either.ixing channel inputs or sub.ast er inputs. These combined ~i gnlls are a.p llf ied tost and a r d line levels and there after fed to the main program outputs of the console sy s t e•. Input and Sum.lng Amplifier The signal o rl gi natlng fro. the external IIh ing network is ap pl led t o the summlng current nodes oft he input amplifier via edge COnnector pln s l / A.

Ql through Q8 form a summing amplifier comp rl s l ng a balanced input and an unbalanced out put. to correct for small system level variations. trim pot R7 i sin cor por ated as part of the pr e amplifier. The differential balance adjustment control R6 serves t o minimize common mode type signals orig 1nat ing ahead of the ampl i f 1e r. e12 couples the output Oft he summing amplifier t o a low-pass filter consisting of R22. R23, R24, e 13, C14. C15 and 21. The 3 dB roll off point 15 loc. ted at approximately 40 kHz.

The output of 21 1s coupled through CIS tot he output amplifier 8-I 09A.

8·I09A Output Amplifier and IHS(RT The S-109A amplifier raises the nominal signal level to 0 dSm. The output is actively balanced and fed to the -insert po intI t pins 14/R.

Pins 14/R Ire usually connected to I nor.alled set or insert jacks. with the output side connected tot he sub master fader. The (Id e r output i s returned t o the. odul eon pins 8/ J. a-109E BOOSTER Amplifier Th ls amplifier operates a t again of 29 dS. It recovers the

I S dB -i nha nd&quot; loss incurred by the lIi xi n9 fader.nd provides

.ddition. l g.i n resulting i n • no~i n.l 11ne level of +8 dBm

.ft er p.s sing through. 6 dB, 600 ohm Is o1. t ion network.

**H4 77 HASTER MODULE**

Outputs Two 600 oh• • balanced outputs are provided, on pins 17/U and 16/T respectively, each with a. axi.u. output capability o f i24 dB.. A monitor output is available at pins 15/S to feed the input t o the &quot; 475. oni tor.o dule s. Pins 11/ H provide the feed fora standard vu. et e r circuit.

Solo Out put The solo output i s fed via SW10 t o pins 7/H. The solo control appears on pins 18/ V.

Power Supply Decouplin9 An active powers uppl y decoup l ing net wo r l Consisting of Q9 through 014 provides isolation between the module and the t2 5 volt sup ply rails. Transistors Q13 and Q14 monitor the supply current. Int he event of excessive power supply demandS. such as from component failure or amplifier overdrive, the current flowing through Qll and 012 w111 be limited.

**H4 77 &quot;ASTER &quot; DOULE**

PART OESCRIPTIOH MFG Hf G PART HUMB ER

Capacitor 330 !I f 16, Ke.e t

T390f337H006AS

ca • delete

CS • 10 p F Ph1l 1 ps 2222-638-1 0109

C7 &quot; 15 p F • 2222-638-10 159 C8 &quot; 3.3 pf • 2222-6 3B-093 38

10 u F/ 2 5, • Kellet

33 uf /l 150 0 pf

xse t ce

**CQ92 - HC-152 H**

C1 ' &quot; 220 pf Phfl fps 2222-6 30 -032 2 1 C15 &quot; 100 pF &quot; 2222 -638 -7 010 1

C16 &quot; 10 pF &quot; 22 22 -638-10109 C17 &quot; 4.7 PF • 2222-638-09478 C18 • 33 uf /l O v Ke llet T39 003 36&quot;,0 10AS C19 • delete

C21 • 0.022 !IF Ase lco CQ 92MC-22 3&quot; C22 • 22 uF/ 25 V Ph1l 1p s 426ETF 22

CR) delete CR2 Diode Motor oh l N40 0 3

01 Transistor Hat 1 anal 2N4401

Q3 &quot; &quot; PM36 45

O' &quot; &quot; 2M440 1

J· l

WARD - BECK SYSTEM BLT D.

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKemd2cnNnT0EzUmc/view?resourcekey=0-CB59LqXSO8f_rLIXly7_sw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKemd2cnNnT0EzUmc&resourcekey=0-CB59LqXSO8f_rLIXly7_sw" width="240" alt="1979 - M477 - Master Module.jpg"></a><br><sub>1979|12 · Master Module</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1979|12 · Master Module_small](https://drive.google.com/file/d/0B0yR0b5T78SKUmdtd1lUOHdVeE0/view?resourcekey=0-UH4UYFmbodOfQj9bdkm_kg) · [1979|12 · wbsps - module - m477 master module_small](https://drive.google.com/file/d/0B0yR0b5T78SKQVdpNE5rRjNUd1k/view?resourcekey=0-eFEx_n0tJTlt47tOLDx2XA)

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKczExdjFhV1lwNEk/view?resourcekey=0-WUvWqQ0zOOb30G0fheoUDg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKczExdjFhV1lwNEk&resourcekey=0-WUvWqQ0zOOb30G0fheoUDg" width="240" alt="1979 - M477 - P18 - Front Panel.jpg"></a><br><sub>1979|12 · P18 - Front Panel</sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOHQzbFE5WGJCZUE/view?resourcekey=0-WGIzE2CGxLVXEPPasDAfMA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOHQzbFE5WGJCZUE&resourcekey=0-WGIzE2CGxLVXEPPasDAfMA" width="240" alt="1979 - M477 - 477-01-001 - OHM MONITOR OUTPUT METERING OUTPUT SOLO SOLO SUMMING.jpg"></a><br><sub>1979|12 · 477-01-001 - OHM MONITOR OUTPUT METERING OUTPUT SOLO SOLO SUMMING · <a href="SCHEMATICS/1979%20-%20M477%20-%20477-01-001%20-%20OHM%20MONITOR%20OUTPUT%20METERING%20OUTPUT%20SOLO%20SOLO%20SUMMING%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbXQ1TjQtUzhjY3c/view?resourcekey=0-nxpQYeh-laEENIHLPJjy0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbXQ1TjQtUzhjY3c&resourcekey=0-nxpQYeh-laEENIHLPJjy0Q" width="240" alt="1979 - M477 - 477-06-001 - MASTER MODULE COMPONENT LAY.jpg"></a><br><sub>1979|12 · 477-06-001 - MASTER MODULE COMPONENT LAY · <a href="SCHEMATICS/1979%20-%20M477%20-%20477-06-001%20-%20MASTER%20MODULE%20COMPONENT%20LAY%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZm9uSzNYWUo3UGc/view?resourcekey=0-xyWe7DjvPwI4WJ2nGfHO7g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZm9uSzNYWUo3UGc&resourcekey=0-xyWe7DjvPwI4WJ2nGfHO7g" width="240" alt="1979 - M477 - 8-109-02-002 - OUTPUT AMPLIFIER SCHEMATIC.jpg"></a><br><sub>1979|12 · 8-109-02-002 - OUTPUT AMPLIFIER SCHEMATIC</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOGhLR29fbzBpS0E/view?resourcekey=0-pJosVqFAc1L8QC4rh0ZuNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOGhLR29fbzBpS0E&resourcekey=0-pJosVqFAc1L8QC4rh0ZuNQ" width="240" alt="1979 - M477 - BOOSTER AMPLIFIER SCHEMATIC.jpg"></a><br><sub>1979|12 · BOOSTER AMPLIFIER SCHEMATIC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbm42MURaYk1iWHc/view?resourcekey=0-cYIAVpjIWJQ_jBDIBTkiPw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbm42MURaYk1iWHc&resourcekey=0-cYIAVpjIWJQ_jBDIBTkiPw" width="240" alt="1979 - M477 - P20 - Schematic.jpg"></a><br><sub>1979|12 · P20 - Schematic</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekUzcTBPckZ2RW8/view?resourcekey=0-w5ZAe9bnin86wQYO-jmoNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekUzcTBPckZ2RW8&resourcekey=0-w5ZAe9bnin86wQYO-jmoNQ" width="240" alt="1979 - M477 - P24 - 8-109-Output Amp Layout.jpg"></a><br><sub>1979|12 · P24 - 8-109-Output Amp Layout</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOHhZaGQ2OXh3c3c/view?resourcekey=0-z32ewZtq8y1T6HHgS4pbZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOHhZaGQ2OXh3c3c&resourcekey=0-z32ewZtq8y1T6HHgS4pbZA" width="240" alt="1979 - M477 - P27 - 8-109E-Booster Amp Layout.jpg"></a><br><sub>1979|12 · P27 - 8-109E-Booster Amp Layout</sub></td></tr>
</table>

Not on Google Drive yet: `1979 - 477-06-001 - MASTER MODULE COMPONENT LAYOUT - DRN MRW - ISS 6.jpg`, `M477 - P20 - Schematic.jpg`, `M477 - P25 - Component Layout.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRHZ4V3FmWGQyYTQ/view?resourcekey=0-WEpF_q0wAghcE0btKigGfA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRHZ4V3FmWGQyYTQ&resourcekey=0-WEpF_q0wAghcE0btKigGfA" width="240" alt="1979 - M477 - P22 - Pin Out.jpg"></a><br><sub>1979|12 · P22 - Pin Out</sub></td></tr>
</table>

Not on Google Drive yet: `M477 - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 12 of 14 contacts; 2 to check (`conflicts`). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- disagree P1-J: kept ATT OUT (out); RTO-144 sheet says Insert Return - (in)
- disagree P1-R: kept OUTPUT AMP OUT (out); RTO-144 sheet says Insert Return + (in)

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | INPUT | in | INPUT | high |
| 2 | SHIELD | shield |  | high |
| 3 | IC (INTERNALLY CONNECTED) | other |  | high |
| 4 | IC (INTERNALLY CONNECTED) | other |  | high |
| 5 | IC (INTERNALLY CONNECTED) | other |  | high |
| 6 | IC (INTERNALLY CONNECTED) | other |  | high |
| 7 | SOLO OUT | out | SOLO OUT | high |
| 8 | ATT OUT | out | ATT OUT | high |
| 9 | IC (INTERNALLY CONNECTED) | other |  | high |
| 10 | IC (INTERNALLY CONNECTED) | other |  | high |
| 11 | METER OUTPUT | out | METER OUTPUT | high |
| 12 | IC (INTERNALLY CONNECTED) | other |  | high |
| 13 | IC (INTERNALLY CONNECTED) | other |  | high |
| 14 | OUTPUT AMP OUT | out | OUTPUT AMP OUT | high |
| 15 | MONITOR OUT | out | MONITOR OUT | high |
| 16 | OUTPUT 2 | out | OUTPUT 2 | high |
| 17 | OUTPUT 1 | out | OUTPUT 1 | high |
| 18 | CONTROL COMMON | ground |  | high |
| 19 | -25 V | power |  | high |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS GND | ground |  | high |
| A | INPUT | in | INPUT | high |
| B | SHIELD | shield |  | high |
| C | IC (INTERNALLY CONNECTED) | other |  | high |
| D | IC (INTERNALLY CONNECTED) | other |  | high |
| E | IC (INTERNALLY CONNECTED) | other |  | high |
| F | IC (INTERNALLY CONNECTED) | other |  | high |
| H | SOLO OUT | out | SOLO OUT | high |
| J | ATT OUT | out | ATT OUT | high |
| K | IC (INTERNALLY CONNECTED) | other |  | high |
| L | IC (INTERNALLY CONNECTED) | other |  | high |
| M | METER OUTPUT | out | METER OUTPUT | high |
| N | IC (INTERNALLY CONNECTED) | other |  | high |
| P | IC (INTERNALLY CONNECTED) | other |  | high |
| R | OUTPUT AMP OUT | out | OUTPUT AMP OUT | high |
| S | MONITOR OUT | out | MONITOR OUT | high |
| T | OUTPUT 2 | out | OUTPUT 2 | high |
| U | OUTPUT 1 | out | OUTPUT 1 | high |
| V | SOLO CONTROL | control_in | SOLO CONTROL | high |
| W | IC (INTERNALLY CONNECTED) | other |  | high |
| X | IC (INTERNALLY CONNECTED) | other |  | high |
| Y | IC (INTERNALLY CONNECTED) | other |  | high |
| Z | IC (INTERNALLY CONNECTED) | other |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVVVTcUlKWXlBa2c/view?resourcekey=0-gLHchMLDCAYz9Zta_Z6esw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVVVTcUlKWXlBa2c&resourcekey=0-gLHchMLDCAYz9Zta_Z6esw" width="240" alt="1979 - M477 - Master Module (2).pdf"></a><br><sub>1979|12 · Master Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkp6enNrTmtJVjQ/view?resourcekey=0-lk6rYUw5neumGtQ6F3cS9w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkp6enNrTmtJVjQ&resourcekey=0-lk6rYUw5neumGtQ6F3cS9w" width="240" alt="1979 - M477 - Master Module.pdf"></a><br><sub>1979|12 · Master Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZWNQN0lKOF9MclE/view?resourcekey=0-eapUDm9imlDvPifpEggMtw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZWNQN0lKOF9MclE&resourcekey=0-eapUDm9imlDvPifpEggMtw" width="240" alt="1979 - M477 - P01 - Cover.jpg"></a><br><sub>1979|12 · P01 - Cover</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlBNcUZBdXpPZjA/view?resourcekey=0-1qoEDWMw4xHbIx4mPMO3pw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlBNcUZBdXpPZjA&resourcekey=0-1qoEDWMw4xHbIx4mPMO3pw" width="240" alt="1979 - M477 - P02.jpg"></a><br><sub>1979|12 · P02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWVEtTHUtaWtIS0k/view?resourcekey=0-HcYER5a52zfSZiHYVP4MHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWVEtTHUtaWtIS0k&resourcekey=0-HcYER5a52zfSZiHYVP4MHQ" width="240" alt="1979 - M477 - P03 - TOC.jpg"></a><br><sub>1979|12 · P03 - TOC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNE50em5nVWx2Q0E/view?resourcekey=0-krL2deC21YkQ3V3cQ6pHWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNE50em5nVWx2Q0E&resourcekey=0-krL2deC21YkQ3V3cQ6pHWg" width="240" alt="1979 - M477 - P04.jpg"></a><br><sub>1979|12 · P04</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR3FxZDVhWHdwUXM/view?resourcekey=0-GAIYKUiu0IKn8W6cc04aQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR3FxZDVhWHdwUXM&resourcekey=0-GAIYKUiu0IKn8W6cc04aQA" width="240" alt="1979 - M477 - P05 - 1-1.jpg"></a><br><sub>1979|12 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaDlnNEp3dVdUNDg/view?resourcekey=0-ZbB3H0GyJ3tJ6oQ-3Aq9Cg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaDlnNEp3dVdUNDg&resourcekey=0-ZbB3H0GyJ3tJ6oQ-3Aq9Cg" width="240" alt="1979 - M477 - P06 - 2-1.jpg"></a><br><sub>1979|12 · P06 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYnVfRnJuS0QyWkE/view?resourcekey=0-yKWejjRA2jRv1IxGSNE3mQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYnVfRnJuS0QyWkE&resourcekey=0-yKWejjRA2jRv1IxGSNE3mQ" width="240" alt="1979 - M477 - P07 - 2-2.jpg"></a><br><sub>1979|12 · P07 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZnBrZmZXWThxSjg/view?resourcekey=0-5HC6cofyVc0JyVhhiG44FA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZnBrZmZXWThxSjg&resourcekey=0-5HC6cofyVc0JyVhhiG44FA" width="240" alt="1979 - M477 - P07 - 3-1.jpg"></a><br><sub>1979|12 · P07 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHpwUnhXU3VRMzg/view?resourcekey=0-q9pS33pAipbh-Cc1Klqs8Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHpwUnhXU3VRMzg&resourcekey=0-q9pS33pAipbh-Cc1Klqs8Q" width="240" alt="1979 - M477 - P08 - 3-2.jpg"></a><br><sub>1979|12 · P08 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYkkwMV8tYkxfclE/view?resourcekey=0-ak8Mw99JAi3NXwU9b72K5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYkkwMV8tYkxfclE&resourcekey=0-ak8Mw99JAi3NXwU9b72K5Q" width="240" alt="1979 - M477 - P09.jpg"></a><br><sub>1979|12 · P09</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUUlmcmR6WGM1T2M/view?resourcekey=0-WyggI9THqsYVJMT9KvMzfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUUlmcmR6WGM1T2M&resourcekey=0-WyggI9THqsYVJMT9KvMzfQ" width="240" alt="1979 - M477 - P10 - 8-109-1-1.jpg"></a><br><sub>1979|12 · P10 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN2JBd2NDVXdXNlE/view?resourcekey=0-Bdcr9RxVTdbRxWTqJHTB3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN2JBd2NDVXdXNlE&resourcekey=0-Bdcr9RxVTdbRxWTqJHTB3g" width="240" alt="1979 - M477 - P11 - 8-109-1-2.jpg"></a><br><sub>1979|12 · P11 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUzRBQkljQnhhSEU/view?resourcekey=0-7L6P97oyo-_2NyFMDcDXhA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUzRBQkljQnhhSEU&resourcekey=0-7L6P97oyo-_2NyFMDcDXhA" width="240" alt="1979 - M477 - P12 - 8-109-1-3.jpg"></a><br><sub>1979|12 · P12 - 8-109-1-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlFTczRrRTBxaDg/view?resourcekey=0-J2-jgB9ja4dar07ws9_xVA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlFTczRrRTBxaDg&resourcekey=0-J2-jgB9ja4dar07ws9_xVA" width="240" alt="1979 - M477 - P13 - 8-109-2-1.jpg"></a><br><sub>1979|12 · P13 - 8-109-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcG1fMVV6S2RlaEk/view?resourcekey=0-AkxZBkaYCIfXIIf_t_obsw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcG1fMVV6S2RlaEk&resourcekey=0-AkxZBkaYCIfXIIf_t_obsw" width="240" alt="1979 - M477 - P14 - 8-109-2-2.jpg"></a><br><sub>1979|12 · P14 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT2Z2Q2dwYWFHcWM/view?resourcekey=0-EVY9gJVPtj2l2ZZDSdOrRw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT2Z2Q2dwYWFHcWM&resourcekey=0-EVY9gJVPtj2l2ZZDSdOrRw" width="240" alt="1979 - M477 - P15 - 8-109-2-3.jpg"></a><br><sub>1979|12 · P15 - 8-109-2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSmd1eDZWZEhyeVE/view?resourcekey=0-mXn3ZGgPYc1N4RTgp-Pm7w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSmd1eDZWZEhyeVE&resourcekey=0-mXn3ZGgPYc1N4RTgp-Pm7w" width="240" alt="1979 - M477 - P16 - 8-109-2-4.jpg"></a><br><sub>1979|12 · P16 - 8-109-2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGdMeUt0MGo4T0U/view?resourcekey=0-MZNcrRh6YzuDQ-ZOj0y3sg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGdMeUt0MGo4T0U&resourcekey=0-MZNcrRh6YzuDQ-ZOj0y3sg" width="240" alt="1979 - M477 - P17 - 8-109-2-5.jpg"></a><br><sub>1979|12 · P17 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkhXLWEwUTljVXM/view?resourcekey=0-b9n2IVef2O4jjW76Rkhzkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkhXLWEwUTljVXM&resourcekey=0-b9n2IVef2O4jjW76Rkhzkg" width="240" alt="19xx - M477 - DOC - L2042 - P04.jpg"></a><br><sub>19xx - M477 - DOC - L2042 - P04</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKemF4RnJvbzJwaGs/view?resourcekey=0-Srr78vm02U_h1rwCcxG1pQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKemF4RnJvbzJwaGs&resourcekey=0-Srr78vm02U_h1rwCcxG1pQ" width="240" alt="19xx - M477 - DOC - L2042 - P08.jpg"></a><br><sub>19xx - M477 - DOC - L2042 - P08</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa1RnVXFCRU9UeDA/view?resourcekey=0-HstK7E0Mu-VZp59Y7Wdh1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa1RnVXFCRU9UeDA&resourcekey=0-HstK7E0Mu-VZp59Y7Wdh1w" width="240" alt="19xx - M477 - DOC - L3242 - P04.jpg"></a><br><sub>19xx - M477 - DOC - L3242 - P04</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUkpDVUItak9tLTA/view?resourcekey=0-PK_H3bgtXK52v08Lfj-8rQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUkpDVUItak9tLTA&resourcekey=0-PK_H3bgtXK52v08Lfj-8rQ" width="240" alt="19xx - M477 - DOC - L3242 - P08.jpg"></a><br><sub>19xx - M477 - DOC - L3242 - P08</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZzU5S3owVE1UdWM/view?resourcekey=0-LPjgcvMP4PiETfpcI_m6lg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZzU5S3owVE1UdWM&resourcekey=0-LPjgcvMP4PiETfpcI_m6lg" width="240" alt="19xx - M477 - DOC - STEREO L SERIES - P005.jpg"></a><br><sub>19xx - M477 - DOC - STEREO L SERIES - P005</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1_P_Z0K0APxS1Ngvfo4PyGCjkwzW8txn2/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1_P_Z0K0APxS1Ngvfo4PyGCjkwzW8txn2" width="240" alt="19xx - M477 - DOC - WBSps.ca 20210320 - Scans.jpg"></a><br><sub>19xx - M477 - DOC - WBSps.ca 20210320 - Scans</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1RfSw2kLEkjmzn61B4MBmvmmEhPNKtRw2/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1RfSw2kLEkjmzn61B4MBmvmmEhPNKtRw2" width="240" alt="19xx - M477 - DOC - WILMA - Aux and main summing.jpg"></a><br><sub>19xx - M477 - DOC - WILMA - Aux and main summing</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1979 - M477 - 477-01-001 - OHM MONITOR OUTPUT METERING OUTPUT SOLO SOLO SUMMING.kicad_sch](KICAD/1979%20-%20M477%20-%20477-01-001%20-%20OHM%20MONITOR%20OUTPUT%20METERING%20OUTPUT%20SOLO%20SOLO%20SUMMING.kicad_sch)
- [1979 - M477 - Master Module (2) p17.kicad_sch](KICAD/1979%20-%20M477%20-%20Master%20Module%20(2)%20p17.kicad_sch)
- [1979 - M477 - Master Module p20.kicad_sch](KICAD/1979%20-%20M477%20-%20Master%20Module%20p20.kicad_sch)
- [1979 - M477 - Master Module p21.kicad_sch](KICAD/1979%20-%20M477%20-%20Master%20Module%20p21.kicad_sch)
- [1979 - M477 - Master Module p23.kicad_sch](KICAD/1979%20-%20M477%20-%20Master%20Module%20p23.kicad_sch)
- [M477.kicad_sym](KICAD/M477.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
