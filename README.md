# M462C Stereo Equalizer Module · Filters

Ward-Beck Systems M462C, 1985|18. Wiki page: [M462C on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M462C.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 33 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 10 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 294 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 13 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 45 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1985 - M462C - M462C562C - P003 - 1-1.jpg](MANUALS/1985%20-%20M462C%20-%20M462C562C%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | Unity +/-0.5 dB |
| **Frequency response** | +/-0.5 dB from Hz kHz with the equalizer inserted and the cut/hoost controls the detent position. |
| **Noise** | dBm absolute equalizer &quot;out&quot; -82 dBm absolute equalizer inserted and the cut/boose controls the detent position measured over 20 Hz kHz bandwidth. |
| **Harmonic distortion** | Less than 0.17 front Iz kllz 30 dBi output level Tess Less than 017 kHz +30 dBm output Level less |
| **Source impedance** | 600 ohms less balanced unbalanced |
| **Input impedance** | 20,' 000 ohms balanced |
| **Input level** | ~10 dBm nominal +30 dBu maximum |
| **Output impedance** | Less than 100 ohms actively balanced |
| **Load impedance** | 600 ohms greater balanced |
| **Output level** | -10 dBm nominal +30 dBm maximum |
| **Channel separation** | Greater than |
| **Phasing** | Low number the input pair phase with the low number the output pair_ with the equalizing controls the detent pos tion. |
| **Equalization tracking** | Within 0.5 dB for Level and within 105 for frequency |
| **Power requirements** | +/-25 volts 125 MA nominal, 225 niA maximuin |
| **Ambient temperature** | degrees Celsius. |

## Circuit description

From [1985 - M462C - M562C - Stereo Equalizer (2).pdf](MANUALS/1985%20-%20M462C%20-%20M562C%20-%20Stereo%20Equalizer%20(2).pdf) pages 8-13 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

C l~ ul t description d e tell.\&lt; will perl ft ln t o Ih e Left Channel. The right Chft nn el circuitry op erft leS Ina s lm l l llr manner.

The left e eeo o erIn put IIP pears lit pins 1 U 2 of Ih e module connec ~ tor and the right Channel Input Is ft t connector pins 4 (, S. Inputs hie ld connections mey b e mftd e t o pins 3 &quot;nd 6.

U1B converts Ih e left c hft n ne lIn p u l s lg n,, 1 fro nl Il balanced to &quot;n u nb&quot; l e nced mode, &quot;s well as a c lt ng as a buffer tot hoe equll tiz ing circuitry.

The ou tp u l from Ut a 15 coupled t h rough C4 10 b ypess switch SW1A and low fr e q u e n c y cut / boost control R IA. It also leeds the com bl n;n g amplifier U2B.

Amplifiers U2B, U2A and U3A are combining or m i&gt;d ng an,p llf ie rs which t llk e them n l n c h &quot; n n e laud io sl g nll l.. n d IId d Ih e oU lpu l s lrom Ih e equal i zings r ere Vll r lab l e fIlters.

Thee q uali zing e bee ec tete uc e. divides thea u d ios pe c t rum Into uve e b n nd s. The Low frequency cove rl ng frequencies from 30 Hz to ' 00 Hz. These f re qu e n c y compon en l S are m h, e d by U2B.

U2A combines lI udlo com pone n ls overt h e Mid Ire q u e n c y rang &quot;, Irom 400 Hz 10 6.'k Hz. The high frequency portion of Ih e &quot; u d ios p e c lr u mover the range of 1.6 kHz 10 2' kHz Is mixed by U3 A.

UJB forms lin 150 la llon &quot;mp ll fie r, the output of which Is coup led through C I6 10 Insertion switch SWIA.

Low FreQuency EqU lll1z er

The cu t/boo51 control R IA brld ge 5 between the Input and output of

mixIng &quot; m p l lfie r U2B.

The lIrm o f control RIA f.... d 5 II portion o f the &quot; u dlo 519 n,, 1 to a

Slate v llrl&quot;b le filter composed of WIS, U4A lind usa. C I 9 lInd Cl I along with sec tl o nsA and a off r eQu en cy control Rio, determine the

resonant freQuency oft h e ill te r,

CIRCUIT OESCr'llP T ION

The oU lpu t f r-om the fl lt e.. Is fed b&quot;ck Into the mixing amp l l f le &quot; through CS where it Is added or eve u-ee tee lrom Ih e millin signal In propor l1on 10 III millg nl tude and ph ills e.

Tn ls low fl&quot;&quot;e QUenc y fl l te&quot; maybes witched Irom II r e Son llnt Of' pellk - Ing mode to ashe lvI n g type ch a..e c te r-ta ttc. This i s d e lerm in ed Oy s wll c h SW2, which when depressed switches Ih efl tt e rf rom Its r eson&quot;n t condition to a low pass s t&quot; t &quot;.

Mld-F..e Que nc y Equal ize&quot;

Tn e left channel CUI/ooo s t control R2A o rldg&quot;s between the Input iIInd output of mixing amplifier U2A. When t n ls control Is Int he 0 det en t posItion (cen te.. po ln l) no co r..ee tt ce 0 &quot; eQu&quot; l l z lng slg n,, 1 Is fed 10 the filter net wOf'k.

The signal output from thea r m o f f&quot;\2A Is coupled t h r o u g n en 10 the mid ranges l ale variable filler, composed of U6A, U68 and U1A. Tne r e so nan l fr e q u en c y Is determined by C26, C21, C92, C9 3 and these il ing of RS sections A &quot;nd B.

Q switch SW3 A cn &quot;n ge s the filler gain by Inser ling R~6 In lo II feedback p&quot; tn oft he filter. When SW3 15 released a high Q of 4 I&quot; selected and when depressed the lif ter Q equ a l&quot; 2.

The output signal from the fl lt erIs coupled back Into summing amplifier UZA t h rough CS, where It I&quot; propo r t lonl:l l ly added Or sub t rac ted from the main Ch llnn el 5 19 &quot;,, 1. Ad dillon results In II boost conditIon while a cut 15 there s u lt of subtraction.

, High Frequency EQu &lt;'!l lzer

High frequency cu t/boos t control A3A feeds an error slg&quot;a l tot h., high fr eq u e n c y slate v e r-I.. b le fi lle rm&quot;de up o f USA, usa and U9A. These ll ing of cont r o l R6, sections A and 8 &quot; long with C32 and CJ J set In e r-e s ce.. n tor pe.. ldn g conditions to Ih e shelving or high p &quot; &quot; s f l lt e rcondi tion.

The output l rom this filter Is coupled beck to mix In !,,! an lpl lfl er U3A

through C l l, wn ere I t Is either lidded o r subtract ed from th &quot; m,,' n ch &quot;nnet signal.

The left channel output f r'&lt;!m i...s e r t switch SWI..... connects to the SAI4 _109A one weu output 8 mp ' i ' ie r.

The left tl n d right channel output tlm p l i lie rs are ell c h sep &quot;rllt e plug On card assemblies.

The left eha nne l audio output app ell rs atp ins 12 ft 13 0 ' the module edge connector, and the right channel output Is atp ins 15 &amp; 16.

P&quot;''''er SUpply Decoup llng

The -1-/-25 supply vo llage (pin s 21 ft 19 oft h e module edge con n_ ec tor) feed t h r'&lt;!u g h polarity rev er sIng diodes crn and CR 2 to these r ies decoup lers 0 1 through 04.

The nomlntll -1-/_22 volts from this d ecoup l er feeds the SAI 4_ 109..... ou tpu l IImp l l f l e r s. to limit overall power dissipation under eve r-Iced conditions II current liml lin g controls ig na l Is fed back from the 5A 14_ 109..... ampl U lers 10 the bases of 0 1 lind 0 2. When e n o lle rl oa d condition occurs the cur r en l limit control slgntl ls s h u IS down o r tu......s off the dee::oup ler s, thereby I lm l l l n g power dl s sip all on Int he module.

The -1-/-16 volts u p ply v&quot;l lag e r-ecub-ed b y the operational &quot; '&quot;p ll f ler&quot; of thee Qua l l ztl t lon circuitry Is dee::ou pled and filtered by OS t h rough Q6. These vol i llg e s are t e p p e doff the &quot; /-22 volts u p ply lines.

The powers u p ply Common r e lurn...ppe llr slit pin 20 01 the module conn eet o rand the eh e s s ls fr eme eonn ee t s l o, p l n 22,

WAR O - BECKS YB TEM S LT c.H III: I ' ' ~L.

FnEClUEUCY RESPONSE CHAFIACTER I ST I CS

**~1 46 2C STEREO EOUALI ZER '·'OOULE**

.,5- - In ? -7&lt;;

+0 - f - -\; +0 - f

OB - -o&lt;E I--

1--1l

1--1- ~~

&quot;,,'-;- &quot;H,,0&lt; 2(tJ(l 4l1.

&quot; I GII FREOUEt lCY SECT ION

+/ _ 15 dB.

**BOOST/ CUT'**

FIl EOll ENCV, 1.6 kHz 10 24 kHz

Q.. 2.

WAR O· B E C I&lt; S YBT EMS LT C.

FR EQUEIlCY RESPOtISE CHARACTER 1ST I CS

M'62C STEREO EOUAl. ' ZEn MODULE

2Oi,,1Ott

~tlO FREOUENCY SEC T1011 a c

eoost/ cut _/. l !&gt; dB.

FREOUEtl CY: 400 Hz 10 6.4 10;111.

o &quot; 2 or 4.

WAR C - BECKS VBTE M S LTC.

FREQUEtj CY RESPOUSE CHARACTER 1ST ' CS

I&gt;1462C STEREO EOUAL. l ER MOOULE

-s \ v -&quot; All &gt;

&quot;0&quot; ''''' I~ &quot;&quot;....

**LOW FREOUENCY SECT ION**

BOOST/ CUT: +/_.5 ee.

FREOUENCY, 25 Hz 10.00 Hz Q. 2.

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMndhQkZsdnNjRTg/view?resourcekey=0-T7A_hBftEhsSE6GgRHWcfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMndhQkZsdnNjRTg&resourcekey=0-T7A_hBftEhsSE6GgRHWcfQ" width="240" alt="1985 - M462C - 462-04-008 - STEREO EQUALIZER MODULE MODULE LAYOUT.jpg"></a><br><sub>1985|18 · 462-04-008 - STEREO EQUALIZER MODULE MODULE LAYOUT · <a href="MECHANICAL/1985%20-%20M462C%20-%20462-04-008%20-%20STEREO%20EQUALIZER%20MODULE%20MODULE%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkNTaXNJTEhpb3c/view?resourcekey=0-YoviFItAX3gusF2FH3RDiw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkNTaXNJTEhpb3c&resourcekey=0-YoviFItAX3gusF2FH3RDiw" width="240" alt="1985 - M462C - 462-04-008.jpg"></a><br><sub>1985|18 · 462-04-008 · <a href="MECHANICAL/1985%20-%20M462C%20-%20462-04-008%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M462C.stl`](MECHANICAL/M462C.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M462C)

- **Size:** 56.57 × 209.42 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 7 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M462C - front panel.svg`)
- the drawn panel is 0.23 wide to high, the size 0.27: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M462C.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc2tQdDEyMm52VFk/view?resourcekey=0-NMFPud-TucIiLV_VQINJnw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc2tQdDEyMm52VFk&resourcekey=0-NMFPud-TucIiLV_VQINJnw" width="240" alt="1985 - M462C - 14-109-02-002 - UNIVERSAL AMPLIFIER ASSEMBLY SCHEMATIC.jpg"></a><br><sub>1985|18 · 14-109-02-002 - UNIVERSAL AMPLIFIER ASSEMBLY SCHEMATIC · <a href="SCHEMATICS/1985%20-%20M462C%20-%2014-109-02-002%20-%20UNIVERSAL%20AMPLIFIER%20ASSEMBLY%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNEE2c1RBdUVoQUk/view?resourcekey=0-rjWVgZf_96t321UuUhg6Bg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNEE2c1RBdUVoQUk&resourcekey=0-rjWVgZf_96t321UuUhg6Bg" width="240" alt="1985 - M462C - 14-109-02-002.jpg"></a><br><sub>1985|18 · 14-109-02-002 · <a href="SCHEMATICS/1985%20-%20M462C%20-%2014-109-02-002%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT2dwaklPMU9rQWs/view?resourcekey=0-pikEFE9ma0V22CGOK4UWgQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT2dwaklPMU9rQWs&resourcekey=0-pikEFE9ma0V22CGOK4UWgQ" width="240" alt="1985 - M462C - 14-109-06-002 - UNIVERSAL AMPLIFIER ASSEMBLY COMPONENT LAYOUT.jpg"></a><br><sub>1985|18 · 14-109-06-002 - UNIVERSAL AMPLIFIER ASSEMBLY COMPONENT LAYOUT · <a href="SCHEMATICS/1985%20-%20M462C%20-%2014-109-06-002%20-%20UNIVERSAL%20AMPLIFIER%20ASSEMBLY%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeC1qZXdLcEF5a1k/view?resourcekey=0-pDLC7e1Znv-Ijl14ApsM3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeC1qZXdLcEF5a1k&resourcekey=0-pDLC7e1Znv-Ijl14ApsM3w" width="240" alt="1985 - M462C - 462-01-004 - STEREO EQUALIZER MODULE FUNCTIONAL.jpg"></a><br><sub>1985|18 · 462-01-004 - STEREO EQUALIZER MODULE FUNCTIONAL · <a href="SCHEMATICS/1985%20-%20M462C%20-%20462-01-004%20-%20STEREO%20EQUALIZER%20MODULE%20FUNCTIONAL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbzVBWEY4MENIb28/view?resourcekey=0-SFo1MS1uit1p8FNZrbklIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbzVBWEY4MENIb28&resourcekey=0-SFo1MS1uit1p8FNZrbklIg" width="240" alt="1985 - M462C - 462-01-004.jpg"></a><br><sub>1985|18 · 462-01-004 · <a href="SCHEMATICS/1985%20-%20M462C%20-%20462-01-004%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTDZsTVh5blpkWFE/view?resourcekey=0-_pvXTjGdrpFulZmsjPMHeg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTDZsTVh5blpkWFE&resourcekey=0-_pvXTjGdrpFulZmsjPMHeg" width="240" alt="1985 - M462C - 462-02-004 - LAST COUPONENT DESI COHMON CPI.jpg"></a><br><sub>1985|18 · 462-02-004 - LAST COUPONENT DESI COHMON CPI · <a href="SCHEMATICS/1985%20-%20M462C%20-%20462-02-004%20-%20LAST%20COUPONENT%20DESI%20COHMON%20CPI%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVHVYakdrVkpuMDg/view?resourcekey=0-mIOFxj9YOI-18dI-ebgC-Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVHVYakdrVkpuMDg&resourcekey=0-mIOFxj9YOI-18dI-ebgC-Q" width="240" alt="1985 - M462C - 462-02-004 - SECNED ICITORS ARE RATED.jpg"></a><br><sub>1985|18 · 462-02-004 - SECNED ICITORS ARE RATED · <a href="SCHEMATICS/1985%20-%20M462C%20-%20462-02-004%20-%20SECNED%20ICITORS%20ARE%20RATED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWUd5c3p0S0lURE0/view?resourcekey=0-MUwLjlP6bjK4f7nuXln5nw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWUd5c3p0S0lURE0&resourcekey=0-MUwLjlP6bjK4f7nuXln5nw" width="240" alt="1985 - M462C - 462-06-009 - STEREO EQUALIZER MODULE COMPONENT LAYOUT.jpg"></a><br><sub>1985|18 · 462-06-009 - STEREO EQUALIZER MODULE COMPONENT LAYOUT · <a href="SCHEMATICS/1985%20-%20M462C%20-%20462-06-009%20-%20STEREO%20EQUALIZER%20MODULE%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M462C - RTO-144 Connections.pdf`

## RTO-144 pinout

22 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | EQ IN LEFT | in | A1 + | high |
| 2 | EQ IN LEFT | in | A1 - | high |
| 4 | EQ IN RIGHT | in | A3 + | high |
| 5 | EQ IN RIGHT | in | A3 - | high |
| 12 | EQ OUT LEFT | out | A2 + | high |
| 13 | EQ OUT LEFT | out | A2 - | high |
| 15 | EQ OUT RIGHT | out | A4 + | high |
| 16 | EQ OUT RIGHT | out | A4 - | high |
| 22 | POWER SUPPLY COMMON RETURN | ground |  | medium |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ2V6aUdRWWx3aFk/view?resourcekey=0-icqDxD7PgqeNN9DtSv-IhQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ2V6aUdRWWx3aFk&resourcekey=0-icqDxD7PgqeNN9DtSv-IhQ" width="240" alt="1985 - M462C - M462C562C - P002 - 1-1.jpg"></a><br><sub>1985|18 · M462C562C - P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa3JZZVlZREEzNzA/view?resourcekey=0-55dnbh0U9eVZ3iWA89w8_g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa3JZZVlZREEzNzA&resourcekey=0-55dnbh0U9eVZ3iWA89w8_g" width="240" alt="1985 - M462C - M462C562C - P003 - 1-1.jpg"></a><br><sub>1985|18 · M462C562C - P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTlIyX1RTQVdZZHM/view?resourcekey=0-6CbaEmhCReeuYEpsMl9iRw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTlIyX1RTQVdZZHM&resourcekey=0-6CbaEmhCReeuYEpsMl9iRw" width="240" alt="1985 - M462C - M462C562C - P004 - 1-2.jpg"></a><br><sub>1985|18 · M462C562C - P004 - 1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNV9hMHdndW9xalk/view?resourcekey=0-mEm0cPanKAMLrmFL8KyyFg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNV9hMHdndW9xalk&resourcekey=0-mEm0cPanKAMLrmFL8KyyFg" width="240" alt="1985 - M462C - M462C562C - P005 - 2-1.jpg"></a><br><sub>1985|18 · M462C562C - P005 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSGxSOGVQTF9MeEE/view?resourcekey=0-AlBiR0EYx25A3CTx0107aQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSGxSOGVQTF9MeEE&resourcekey=0-AlBiR0EYx25A3CTx0107aQ" width="240" alt="1985 - M462C - M462C562C - P006 - 3-1.jpg"></a><br><sub>1985|18 · M462C562C - P006 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDlLakk4RU8tVU0/view?resourcekey=0-ab5Iqk0MZpfzToZLN_jyiA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDlLakk4RU8tVU0&resourcekey=0-ab5Iqk0MZpfzToZLN_jyiA" width="240" alt="1985 - M462C - M462C562C - P007 - 3-2.jpg"></a><br><sub>1985|18 · M462C562C - P007 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZXVGZkR2QTNoM2M/view?resourcekey=0-7rfV3Gh1HqCTRTmD06LcrA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZXVGZkR2QTNoM2M&resourcekey=0-7rfV3Gh1HqCTRTmD06LcrA" width="240" alt="1985 - M462C - M462C562C - P008 - 4-1.jpg"></a><br><sub>1985|18 · M462C562C - P008 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcG1sal82My16N2c/view?resourcekey=0-2L3B_65UMXhUiEBaTgSngw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcG1sal82My16N2c&resourcekey=0-2L3B_65UMXhUiEBaTgSngw" width="240" alt="1985 - M462C - M462C562C - P009 - 4-2.jpg"></a><br><sub>1985|18 · M462C562C - P009 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWFFJTzI4MTk1dTA/view?resourcekey=0-VIwBBB4Fj0efvKI6-ifnOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWFFJTzI4MTk1dTA&resourcekey=0-VIwBBB4Fj0efvKI6-ifnOQ" width="240" alt="1985 - M462C - M462C562C - P010 - 4-3.jpg"></a><br><sub>1985|18 · M462C562C - P010 - 4-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM0huejdkOWVHSlU/view?resourcekey=0-W9n3XIpmkBV5c58zOiAk4Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM0huejdkOWVHSlU&resourcekey=0-W9n3XIpmkBV5c58zOiAk4Q" width="240" alt="1985 - M462C - M462C562C - P011 - 5-1.jpg"></a><br><sub>1985|18 · M462C562C - P011 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKazFnVENjSS00aXc/view?resourcekey=0-i_lmcTZ4unjBi0BXyxCtfg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKazFnVENjSS00aXc&resourcekey=0-i_lmcTZ4unjBi0BXyxCtfg" width="240" alt="1985 - M462C - M462C562C - P012 - 5-2.jpg"></a><br><sub>1985|18 · M462C562C - P012 - 5-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeTdWUmZaTmRnYjA/view?resourcekey=0-wO1vxGRcBk4VX7zcAl80_A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeTdWUmZaTmRnYjA&resourcekey=0-wO1vxGRcBk4VX7zcAl80_A" width="240" alt="1985 - M462C - M462C562C - P013 - 5-3.jpg"></a><br><sub>1985|18 · M462C562C - P013 - 5-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG4taWJDQWJLTlU/view?resourcekey=0-ltZV8noXtwxYnn58daziIw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG4taWJDQWJLTlU&resourcekey=0-ltZV8noXtwxYnn58daziIw" width="240" alt="1985 - M462C - M462C562C - P014 - 6-1.jpg"></a><br><sub>1985|18 · M462C562C - P014 - 6-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV0xkMjl4NXNPLUE/view?resourcekey=0-NF7PyxgTDmpN0noPNgFEZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV0xkMjl4NXNPLUE&resourcekey=0-NF7PyxgTDmpN0noPNgFEZA" width="240" alt="1985 - M462C - M462C562C - P015 - 6-2.jpg"></a><br><sub>1985|18 · M462C562C - P015 - 6-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNkd4eS05Nl82ZUk/view?resourcekey=0--di9j9aX-xgc4JYB67tMHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNkd4eS05Nl82ZUk&resourcekey=0--di9j9aX-xgc4JYB67tMHQ" width="240" alt="1985 - M462C - M462C562C - P016 - 6-3.jpg"></a><br><sub>1985|18 · M462C562C - P016 - 6-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVFjcUdhaDl3OFU/view?resourcekey=0-dRaCDFpMHsxKB-s_9iWjfg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVFjcUdhaDl3OFU&resourcekey=0-dRaCDFpMHsxKB-s_9iWjfg" width="240" alt="1985 - M462C - M462C562C - P017 - 6-4.jpg"></a><br><sub>1985|18 · M462C562C - P017 - 6-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU0RmSFV5am9IYkk/view?resourcekey=0-2BDdQeo9hhzWgaub2QlDEg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU0RmSFV5am9IYkk&resourcekey=0-2BDdQeo9hhzWgaub2QlDEg" width="240" alt="1985 - M462C - M462C562C - P018 - 6-5.jpg"></a><br><sub>1985|18 · M462C562C - P018 - 6-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbnV4ZVNtQUdOLXM/view?resourcekey=0-MhJbLt90sFmZeFXKfYioRw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbnV4ZVNtQUdOLXM&resourcekey=0-MhJbLt90sFmZeFXKfYioRw" width="240" alt="1985 - M462C - M462C562C - P019 - 6-6.jpg"></a><br><sub>1985|18 · M462C562C - P019 - 6-6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ2Noai1xWG1fLVk/view?resourcekey=0-lMhSQIBbTThEzMHmdImiKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ2Noai1xWG1fLVk&resourcekey=0-lMhSQIBbTThEzMHmdImiKg" width="240" alt="1985 - M462C - M462C562C - P020 - 6-7.jpg"></a><br><sub>1985|18 · M462C562C - P020 - 6-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbkYyZGRPTm5DYkU/view?resourcekey=0-ohYtzy26-21RNdFvEZ19VA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbkYyZGRPTm5DYkU&resourcekey=0-ohYtzy26-21RNdFvEZ19VA" width="240" alt="1985 - M462C - M462C562C - P021 - 6-8.jpg"></a><br><sub>1985|18 · M462C562C - P021 - 6-8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTkkzbFZQdEZBZTA/view?resourcekey=0-SsjJrXafisXMoI3GAxUjtA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTkkzbFZQdEZBZTA&resourcekey=0-SsjJrXafisXMoI3GAxUjtA" width="240" alt="1985 - M462C - M462C562C - P022 - 6-9.jpg"></a><br><sub>1985|18 · M462C562C - P022 - 6-9</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKODVIbGxKUlZNM28/view?resourcekey=0-BauhJSEJklp-aJ0nUJAa8g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKODVIbGxKUlZNM28&resourcekey=0-BauhJSEJklp-aJ0nUJAa8g" width="240" alt="1985 - M462C - M462C562C - P023 - 6-10.jpg"></a><br><sub>1985|18 · M462C562C - P023 - 6-10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGhIdGNBdXVkVG8/view?resourcekey=0-HgkiJZrffU2p82XgIisJaw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGhIdGNBdXVkVG8&resourcekey=0-HgkiJZrffU2p82XgIisJaw" width="240" alt="1985 - M462C - M462C562C - P024 - 7-1.jpg"></a><br><sub>1985|18 · M462C562C - P024 - 7-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY2pPdG02eWVXN3M/view?resourcekey=0-U0JqkJ5sifvgybaGcfFI-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY2pPdG02eWVXN3M&resourcekey=0-U0JqkJ5sifvgybaGcfFI-g" width="240" alt="1985 - M462C - M462C562C - P029 - SA14-109A.jpg"></a><br><sub>1985|18 · M462C562C - P029 - SA14-109A</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNFdqV2dfcWdyem8/view?resourcekey=0-jCkovgjV0w17TPV2JS34Sg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNFdqV2dfcWdyem8&resourcekey=0-jCkovgjV0w17TPV2JS34Sg" width="240" alt="1985 - M462C - M462C562C - P030 - SA14-109A 1-1.jpg"></a><br><sub>1985|18 · M462C562C - P030 - SA14-109A 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWTVNV3d0SURYVzg/view?resourcekey=0-BsjLxqXMmP3bEqNICPV1Cw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWTVNV3d0SURYVzg&resourcekey=0-BsjLxqXMmP3bEqNICPV1Cw" width="240" alt="1985 - M462C - M462C562C - P031 - SA14-109A 2-1.jpg"></a><br><sub>1985|18 · M462C562C - P031 - SA14-109A 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMEFFSTdxdUNvME0/view?resourcekey=0-rURa1JaUUkSeJHL0TIfk-w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMEFFSTdxdUNvME0&resourcekey=0-rURa1JaUUkSeJHL0TIfk-w" width="240" alt="1985 - M462C - M462C562C - P032 - SA14-109A 3-1.jpg"></a><br><sub>1985|18 · M462C562C - P032 - SA14-109A 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMThCZS1NcGVqMVk/view?resourcekey=0-TxefOODCFY6eOAkCgc8WOg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMThCZS1NcGVqMVk&resourcekey=0-TxefOODCFY6eOAkCgc8WOg" width="240" alt="1985 - M462C - M462C562C - P033 - SA14-109A 3-2.jpg"></a><br><sub>1985|18 · M462C562C - P033 - SA14-109A 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRTJYOGZldzFYR2c/view?resourcekey=0-zy1xkOL28b3wBt5wWwCrzw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRTJYOGZldzFYR2c&resourcekey=0-zy1xkOL28b3wBt5wWwCrzw" width="240" alt="1985 - M462C - M462C562C - P034 - SA14-109A 4-1.jpg"></a><br><sub>1985|18 · M462C562C - P034 - SA14-109A 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1NGbDU4Y1B3SGs/view?resourcekey=0-DsutTwXxJX0WmSJKFPt6TA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1NGbDU4Y1B3SGs&resourcekey=0-DsutTwXxJX0WmSJKFPt6TA" width="240" alt="1985 - M462C - M462C562C - P035 - SA14-109A 4-2.jpg"></a><br><sub>1985|18 · M462C562C - P035 - SA14-109A 4-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKejRxaExNQTh6VFk/view?resourcekey=0-eIyMKmZ7pN-OST0WGHcwxA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKejRxaExNQTh6VFk&resourcekey=0-eIyMKmZ7pN-OST0WGHcwxA" width="240" alt="1985 - M462C - M462C562C - P036 - SA14-109A 4-3.jpg"></a><br><sub>1985|18 · M462C562C - P036 - SA14-109A 4-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWWZhOFE3eTFSSGM/view?resourcekey=0-jgpysHmvy5v1mBRMzWzp8Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWWZhOFE3eTFSSGM&resourcekey=0-jgpysHmvy5v1mBRMzWzp8Q" width="240" alt="1985 - M462C - M462C562C - P037 - SA14-109A 4-4.jpg"></a><br><sub>1985|18 · M462C562C - P037 - SA14-109A 4-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFMwQjZnWXVYeXM/view?resourcekey=0-7qmjyvIyPRyl1ZFhkJNZ3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFMwQjZnWXVYeXM&resourcekey=0-7qmjyvIyPRyl1ZFhkJNZ3w" width="240" alt="1985 - M462C - M562C - Stereo Equalizer (2).pdf"></a><br><sub>1985|18 · M562C - Stereo Equalizer (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdmM4WXNrWl95elE/view?resourcekey=0-Zli8HdkpylThOuD_qGydyQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdmM4WXNrWl95elE&resourcekey=0-Zli8HdkpylThOuD_qGydyQ" width="240" alt="1985 - M462C - M562C - Stereo Equalizer.pdf"></a><br><sub>1985|18 · M562C - Stereo Equalizer</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKalBKaWxCUVNSc28/view?resourcekey=0-kLeUWDOoW5nWP3JeWXud9Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKalBKaWxCUVNSc28&resourcekey=0-kLeUWDOoW5nWP3JeWXud9Q" width="240" alt="1987 - M462C - M462C562C - P001 - Title Page.jpg"></a><br><sub>1987|20 · M462C562C - P001 - Title Page</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1985 - M462C - 14-109-02-002 - UNIVERSAL AMPLIFIER ASSEMBLY SCHEMATIC.kicad_sch](KICAD/1985%20-%20M462C%20-%2014-109-02-002%20-%20UNIVERSAL%20AMPLIFIER%20ASSEMBLY%20SCHEMATIC.kicad_sch)
- [1985 - M462C - 14-109-02-002.kicad_sch](KICAD/1985%20-%20M462C%20-%2014-109-02-002.kicad_sch)
- [1985 - M462C - 462-01-004 - STEREO EQUALIZER MODULE FUNCTIONAL.kicad_sch](KICAD/1985%20-%20M462C%20-%20462-01-004%20-%20STEREO%20EQUALIZER%20MODULE%20FUNCTIONAL.kicad_sch)
- [1985 - M462C - 462-01-004.kicad_sch](KICAD/1985%20-%20M462C%20-%20462-01-004.kicad_sch)
- [1985 - M462C - 462-02-004 - LAST COUPONENT DESI COHMON CPI.kicad_sch](KICAD/1985%20-%20M462C%20-%20462-02-004%20-%20LAST%20COUPONENT%20DESI%20COHMON%20CPI.kicad_sch)
- [1985 - M462C - 462-02-004 - SECNED ICITORS ARE RATED.kicad_sch](KICAD/1985%20-%20M462C%20-%20462-02-004%20-%20SECNED%20ICITORS%20ARE%20RATED.kicad_sch)
- [1985 - M462C - M562C - Stereo Equalizer (2) p28.kicad_sch](KICAD/1985%20-%20M462C%20-%20M562C%20-%20Stereo%20Equalizer%20(2)%20p28.kicad_sch)
- [1985 - M462C - M562C - Stereo Equalizer (2) p30.kicad_sch](KICAD/1985%20-%20M462C%20-%20M562C%20-%20Stereo%20Equalizer%20(2)%20p30.kicad_sch)
- [1985 - M462C - M562C - Stereo Equalizer (2) p42.kicad_sch](KICAD/1985%20-%20M462C%20-%20M562C%20-%20Stereo%20Equalizer%20(2)%20p42.kicad_sch)
- [1985 - M462C - M562C - Stereo Equalizer p30.kicad_sch](KICAD/1985%20-%20M462C%20-%20M562C%20-%20Stereo%20Equalizer%20p30.kicad_sch)
- [1985 - M462C - M562C - Stereo Equalizer p42.kicad_sch](KICAD/1985%20-%20M462C%20-%20M562C%20-%20Stereo%20Equalizer%20p42.kicad_sch)
- [M462C.kicad_sym](KICAD/M462C.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
