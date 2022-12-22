# Plants
Raw photos and report files for automatic morphometry algorithm [Morley](https://github.com/dashabezik/Morley).


## Experimental groups

* [4-, 5-, 6- and 7-day seedlings of wheat](https://github.com/dashabezik/plants/tree/main/wheat_4567days_old). It is the group of untreated 4-, 5-, 6- and 7-day seedlings of Truticum Aestivum L. illustrating the difference between different days of growth.
* [Peas seedlings treated by ferric sulfate](https://github.com/dashabezik/plants/tree/main/peas_FeSO4). This group shows the inhibition of peas growth induced by 19 h ferric sulfate treatments of the seeds. $FeSO_4$ concentrations: 0%, 0.0025%, 0.01%.
* [Wheat treated with Fe nanoparticles](https://github.com/dashabezik/plants/tree/main/wheat_fe_nanoparticles). This group shows the difference in plant growth induced by NP Fe treatments of Truticum Aestivum L. seeds. Treatment groups: 1 - untreated, 2 - 10-4 % NP Fe in film-forming solution; 3 - 10-5 % NP Fe in film-forming solution; 4 - 10-6 % NP Fe in film-forming solution; 5 - film-forming solution.


All the data were obtained with the following parameters:

**Table 1**

||Wheat 4-7 days|Peas treated with ferrum salt|Wheat treated with Fe nanoparticles|
| ---------|-------------------|-----------------------|------------------------------------|
|Blurring |Morph = 5, gauss = 5, canny_top = 139|Morph = 7, gauss = 3, canny_top = 118|Morph = 5, gauss = 3, canny_top = 130|
|Leaves color|h:(0, 113); s:(0,255); v:(104,255)|h:(0, 50); s:(0,255); v:(94,255)|h:(0, 71); s:(0,255); v:(120,255)|
|Roots color|h:(52, 255); s:(0,255); v:(118,255)|h:(61, 255); s:(0,255); v:(94,255)|h:(51, 255); s:(0,255); v:(134,255)|
|Seed color|h:(0, 21); s:(88,255); v:(179,255)|h:(0, 28); s:(111,255); v:(132,255)|h:(0, 31); s:(35,255); v:(156,255)|
|Indent divider to calculate roots and sprouts width|1|10|1|


You can see all the parameters in configuration files, that are placed in each group folder. 
