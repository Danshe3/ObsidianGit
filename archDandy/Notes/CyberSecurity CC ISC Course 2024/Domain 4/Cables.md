#section4 #cybersecurity 

## Networking Cables:
When it comes to networking cables, most people think RJ45 Copper Ethernet cables, many more types are used though.
	- **Crosstalk** is the signal crossing from one cable to another, this can be confidentiality issue.
	- **Attenuation** is the signal getting weaker the farther it travels.

___
All cable measurements are in metric system (m/km).

| 1 Kbps | Kilobit per second |
| ------ | ------------------ |
| 1 Mbps | Megabit per second |
| 1 Gbps | Gigabit per second |
| 1 Tbps | Terabit per second |
| 1 Pbps | Petabit per second |
**UTP Categories – Copper Ethernet Cables**

| CAT1    | Up to 1Mbps   |      | Twisted Pair | Old phone cable                           |
| ------- | ------------- | ---- | ------------ | ----------------------------------------- |
| CAT2    | Up to 1Mbps   |      | Twisted Pair | Token Ring network                        |
| CAT3    | Up to 10Mbps  | 100m | Twisted Pair | Token Ring & 10BASE T                     |
| CAT4    | Up to 16Mbps  | 100m | Twisted Pair | Token Ring network                        |
| CAT5    | Up to 100Mbps | 100m | Twisted Pair | Ethernet, Fast Ethernet, Token Ring       |
| CAT5e   | Up to 1Gbps   | 100m | Twisted Pair | Ethernet, Fast Ethernet, Gigabit Ethernet |
| CAT6/6a | Up to 10Gbps  | 100m | Twisted Pair | Gigabit Ethernet, 10G Ethernet (55m)      |
| CAT7    | Up to 10Gbps  | 100m | Twisted Pair | Gigabit Ethernet, 10G Ethernet (100m)     |
**Multi-mode Fiber Ethernet Cables**

| FDDI      | 160 / 500 MHz   | 1Gbps 220m, 10Gbps 26m                   |
| --------- | --------------- | ---------------------------------------- |
| OM1       | 200 / 500 MHz   | 1Gbps 275m, 10Gbps 33m                   |
| OM2       | 500 / 500 MHz   | 1Gbps 550m, 10Gbps 82m                   |
| OM3       | 1500 / 2000 MHz | 1Gbps 550m, 10Gbps 300m, 40/100Gbps 100m |
| OM4       | 3500 / 4700 MHz | 1Gbps 550m, 10Gbps 400m, 40/100Gbps 150m |
| All Fiber |                 | 100BASE-FX 2000m, 1000BASE-SE-LX 550m    |
**Single-mode Fiber Cables**
1Pbps 50km, 69.1Tbps 240km
___

<span class="red-bg">EMI (Electromagnetic Interference):</span> Magnetism that can disrupt data availability and integrity.

### Twisted Pair Cables:
**UTP (Unshielded Twisted Pair):** Pairs of twisted pairs of cables.
Twisting them makes them less susceptible of EMI.
1 cable sends and 1 receives data.
**STP (Shielded Twisted Pair):** Has extra metal mesh shielding around each pair of cables, making them less susceptible to EMI, but also making the cables thicker, stiffer, and more expensive.

## Fiber Optic Cables:
Use light to carry data (vs. electricity for copper cables):
**PROS:** Speed 1 Petabit per second, 35miles/50km over a single fiber.
	- Distance, it has no attenuation like copper
	- Not susceptible to EMI.
**CONS:** Price, more difficult to use, you can break the glass in the cable if you are not careful.

**Single-Mode fiber** A single strand of fiber carries a single mode of light (down the center), used for long distance cables (Often used in IP-Backbones).
**Multi-Mode fiber** Uses multiple modes (light colors)
 to carry multiple data streams simultaneously, this is done with WDM (Wavelength Division Multiplexing).