# Plants
Raw photos and report files for automatic morphometry algorithm [Morley](https://github.com/dashabezik/Morley).


## Experimental groups

* [4-, 5-, 6- and 7-day seedlings of wheat](https://github.com/dashabezik/plants/tree/main/wheat_4567days_old). It is the group of untreated 4-, 5-, 6- and 7-day seedlings of Truticum Aestivum L. illustrating the difference between different days of growth.
* [The germination test of P. sativum seeds](https://github.com/dashabezik/plants/tree/main/peas_germination_test).It is the group of untreated 3-, 4-, 5-, 6- and 7-day seedlings of P. sativum seeds illustrating the difference between different days of growth.

All the data were obtained with the following parameters:

**Table 1**

||Wheat 4-7 days|Peas 3-7 days|
| ---------|-------------------|-----------------------|
|Blurring |Morph = 5, gauss = 5, canny_top = 139|Morph = 11, gauss = 5, canny_top = 71|
|Leaves color|h:(0, 113); s:(0,255); v:(105,255)|h:(0, 53); s:(0,135); v:(94,244)|
|Roots color|h:(50, 255); s:(0,255); v:(120,255)|h:(94, 255); s:(0,255); v:(98,255)|
|Seed color|h:(0, 20); s:(86,255); v:(101,255)|h:(0, 26); s:(80,255); v:(83,255)|


You can see all the parameters in configuration files, that are placed in each group folder. 
