https://www.reichelt.de/gehaeuse-serie-pult-216-x-130-x-76-mm-teko-363-p21188.html?&trstct=pol_88&nbc=1
https://www.reichelt.de/gehaeuse-serie-pult-161-x-97-x-60-mm-teko-362-p21187.html?&trstct=pol_56&nbc=1
https://www.reichelt.de/gehaeuse-serie-pult-160-x-96-x-59-mm-teko-103-p34065.html?&trstct=pol_85&nbc=1
https://www.reichelt.de/gehaeuse-serie-pult-110-x-70-x-46-mm-teko-102-p34064.html?&trstct=pol_32&nbc=1
https://www.reichelt.de/gehaeuse-serie-pult-85-x-56-x-35-mm-teko-101-p33380.html?&trstct=pol_2&nbc=1



https://de.wikipedia.org/wiki/I%C2%B2S
Unbedingt den PCM2706C oder PCM2707C (auf DigiKey nicht verfügbar) von TI nehmen (C ist wichtig, PJT folgt immer, ob R(eel) oder nicht ist egal)
Die anderen (insbesondere PCM290x) haben kein I²S
Unterschied zwischen C und nicht C Chips: https://www.ti.com/lit/an/sbfa019/sbfa019.pdf

andere chips: CM6635 (mouser, wie im schiit hel), CP2615 (24bit 48k discontinued), USB4715 (digikey und mouser), CS8412, CS8416 (mouser)
Gibt es Alternativen von Cirrus Logic?
http://3.bp.blogspot.com/-GhfnEOvmYFY/UG3X19q91BI/AAAAAAAAAgU/z2ZkhkYbzWM/s1600/i2s_interface.jpg



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


TO BUY:
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

https://de.aliexpress.com/item/1005003917089451.html?pdp_npi=2%40dis%21EUR%21%E2%82%AC%200%2C71%210%2C70%20%E2%82%AC%21%21%21%21%21%40211b58eb16788789320772259ed6a2%2112000027461299284%21btf&_t=pvid%3Aea919be6-11cf-4aa8-99cb-08c2e62dac53&afTraceInfo=1005003917089451__pc__pcBridgePPC__xxxxxx__1678878932&spm=a2g0o.ppclist.product.mainProduct&gatewayAdapt=glo2deu


for silkscreen images: see https://www.youtube.com/watch?v=hoLf8gvvXXU for min line thickness


# other dacs

## schiit LYR

https://www.schiit.com/products/lyr

- has good description of power supply

Gain: 5.7 (15dB) on high, 1.2 (1.35dB) on low

(per channel)
23 Vpeak, 39mApeak @ 600Ω, 450mW
17 Vpeak, 1Apeak @ 16Ω, 9W