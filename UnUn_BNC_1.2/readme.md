# UnUn_BNC
a PCB for a lightweight qrp (maximum 10W SSB & CW or 5W on FT8) 1:49  (or 1:9) UnUn
derived from my UniBalun Project (https://github.com/DG1JAN/UniBalun)

This PCB has the smal avantage over the UbiBalun, that you dont need need a jumper and that the "A" Pad on top is fixed connected to GND. So you
can add there a counterpois (esp. if used as 1:9 UnUn). 

BOM:
- Amdion FT82-43 (FairRite 5943000601) or FT114-43 (FairRite 5943001001)
- 1m Enamel-coated copper wire (0.5mm to 0.7mm will be fine, on the Ft114 also 1mm will fit)
- 100pF Capaciator, e.g. TDK CC45SL3FD101JYVNA
- BNC Socket, the Footprint supports multiple options:
    - Molex 73101
    - Amphenol B6252H7 / Telegärtner J01001A0038 (or similar)
    - PCB-Edge Mount SMA (e.g.
- 4mm "gold" Bana Plug (e.g. https://www.amazon.de/gp/product/B07VYSN74H/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&th=1)

![alt text](https://github.com/DG1JAN/AntennaPlayground/blob/main/UnUn_BNC_1.2/pcb_1.2.jpg)


You can also test a combination of FairRite 59430000601 and 5943001101 Torroids (see Pictzre below), According my measuremenst this results in a ~10% improved efficency over a FT82-43 or FT114-43). If you like pls have a look to my report:
https://github.com/DG1JAN/UniBalun/blob/main/20230620_EFHW_UnUn_efficiency_meas.pdf

![alt text](https://github.com/DG1JAN/AntennaPlayground/blob/main/UnUn_BNC_1.2/example.jpg)


