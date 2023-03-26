https://www.eevblog.com/forum/projects/who-makes-and-where-to-buy-usb-audio-chips/

https://de.wikipedia.org/wiki/I%C2%B2S
Unbedingt den PCM2706C oder PCM2707C (auf DigiKey nicht verfügbar) von TI nehmen (C ist wichtig, PJT folgt immer, ob R(eel) oder nicht ist egal)
Die anderen (insbesondere PCM290x) haben kein I²S
Unterschied zwischen C und nicht C Chips: https://www.ti.com/lit/an/sbfa019/sbfa019.pdf

andere chips: CM6635 (mouser, wie im schiit hel), CP2615 (24bit 48k discontinued), CS8412, CS8416 (mouser)
Gibt es Alternativen von Cirrus Logic?
http://3.bp.blogspot.com/-GhfnEOvmYFY/UG3X19q91BI/AAAAAAAAAgU/z2ZkhkYbzWM/s1600/i2s_interface.jpg

dac chips:
- PCM1753
- PCM1754
- PCM1755
- PCM1780
- PCM1781
- PCM1782
- CS4344




https://hackaday.com/2013/08/27/building-a-high-end-usb-audio-dac/

helpful: caps should be tht (especially dc blocking -> film), for resistors it doesn't matter (except output emitters)
	https://www.youtube.com/watch?v=4ZUBda5oIUo
not so helpful: https://www.youtube.com/watch?v=iJazCWnAmkM

helpful: for dc blocking and even power: use good film cap with large electrolytic in parallel (do they have to be dual polarity for dc block???)
	(0.1-0.2uF for power rails| could this be biased, because no lower value cap was paralleled beforehand?)
	https://www.youtube.com/watch?v=mCk50RTtrT0
	https://www.youtube.com/watch?v=FQOWd-mObFQ

helpful: eevblog multiple caps (especially results at 80% time, multiple can make it worse, check bode plots for all (power) caps)
	https://www.youtube.com/watch?v=BcJ6UdDx1vg

Switchmode? https://www.youtube.com/watch?v=p0fJSaVljeg

good precision current source: https://sound-au.com/ism.htm




TO WATCH/READ:
- https://www.youtube.com/watch?v=PkJqE-EsoWY
- how to design frot panels: https://www.youtube.com/watch?v=wg_J9WElvBY


TO BUY:
- USB C extender
- isolation heat pads !!!!!!!!!!!!!!!!!! (and check heat sink footprint)
- nylon isolators for screws
- gold screws for panels -> see https://www.youtube.com/watch?v=wg_J9WElvBY @ 5:05
- USB to I²S chips
- audio dacs
- output resistors
- output transistors
- vas transistors
- input transistors
- 0 ohm smd resistors
- collection of different smd resistors
- power caps
- film caps for dc blocking and power supply
- ceramic caps (smd?? closest to output transistors, miller compensation)
- button with rgb light for power button and status
- transformer
- FUUULLL BRIDGE RECTIFIAAA!
- power jack



Transformer: https://www.digikey.de/de/products/detail/triad-magnetics/VPT48-520/2090066

Mains input: https://www.digikey.de/de/products/detail/delta-electronics/06A2/3830616

USB extender: https://de.aliexpress.com/item/1005003747287943.html oder https://de.aliexpress.com/item/1005003439708042.html

USB breakout: https://www.digikey.de/de/products/detail/sparkfun-electronics/BOB-15100/9770720

use resettable fuse for power supply

diode gates: https://www.sanfoundry.com/analog-electronic-circuits-questions-answers-diode-gates-rectifiers/

case categories:
- Endelement(e)
- Geteilte Seiten und Endelement(e)
- Handformat, Endelement und Abdeckung
- Handformat, Geteilte Seiten und Endelemente
-> https://www.reichelt.de/profilgehaeuse-1455-n-220-x-103-x-53-mm-schwarz-1455n2201bk-p221380.html
-> https://www.reichelt.de/profilgehaeuse-1455-n-160-x-103-x-53-mm-schwarz-eloxiert-1455n1602bk-p221378.html
- beide gibt es auch auf Digikey, sind dort aber teurer


https://de.aliexpress.com/item/1005003917089451.html?pdp_npi=2%40dis%21EUR%21%E2%82%AC%200%2C71%210%2C70%20%E2%82%AC%21%21%21%21%21%40211b58eb16788789320772259ed6a2%2112000027461299284%21btf&_t=pvid%3Aea919be6-11cf-4aa8-99cb-08c2e62dac53&afTraceInfo=1005003917089451__pc__pcBridgePPC__xxxxxx__1678878932&spm=a2g0o.ppclist.product.mainProduct&gatewayAdapt=glo2deu

https://www.digikey.de/de/products/detail/adafruit-industries-llc/5531/16653412

for silkscreen images: see https://www.youtube.com/watch?v=hoLf8gvvXXU for min line thickness

# other dacs

## schiit LYR

https://www.schiit.com/products/lyr

- has good description of power supply

Gain: 5.7 (15dB) on high, 1.2 (1.35dB) on low

(per channel)
23 Vpeak, 39mApeak @ 600Ω, 450mW
17 Vpeak, 1Apeak @ 16Ω, 9W



- https://jlcpcb.com/help/article/16-How-to-generate-Gerber-and-Drill-files-in-KiCad-6