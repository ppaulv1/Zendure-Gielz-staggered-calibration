# Zendure-Gielz-staggered-calibration

Additional automation to plan, test and execute calibration for 2 Zendures running through Gielz and NR proxy (Gast777).

This runs 'on top of' Gielz, which in turn runs 'on top of' the NR proxy flow created by Gast777.
All credits for the real work on the batteries goes to Gielz and Gast777.
Calibration in this context is simply charging one battery at maximum charging level to 100% SoC. In the code there's a hard coded maximum of 1200W but any other maximum, as set in the Zendure app or in Gielz is always respected.



This is all pretty new (mid November 2026) but looks promising and stable. Time will tell.



The automation keeps track of the date of the last successful calibration done by this automation for each battery separately. I do not know for sure what happens if the Zendure software itself performs a calibration or when the battery hits 100% by plain charging (which should happen regularly during the summer.



The maximum period after which a calibration is planned and executed is currently 28 days but both batteries will never be calibrated at the same day.



Further details can be found in the extensive installation and user manual (PDF).

