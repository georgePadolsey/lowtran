# [INDEV] Lowtran in Python

Fork of LOWTRAN7 atmospheric absorption extinction model python bindings to add aerosol, haze and similar bindings.

Please do not currently use unless you're 100% sure what you're doing. I haven't yet made any documentation for this but plan to in the future (Dated 11 Nov 2021)[^1].

## Notes

LOWTRAN7
[User manual](http://www.dtic.mil/dtic/tr/fulltext/u2/a206773.pdf)
Refer to this to understand what parameters are set to default.
Currently I don't have any aerosols enabled for example, though it's possible to add them into the code.

Right now a lot of configuration features aren't implemented, please request those you want.

### Reference

* Original 1994 Lowtran7 [Code](http://www1.ncdc.noaa.gov/pub/data/software/lowtran/)
* `LOWFIL` program in reference/lowtran7.10.f was not connected as we had previously implemented a filter function directly in  Python.
* `LOWSCAN` spectral sampling (scanning) program in `reference/lowtran7.13.f` was not connected as we had no need for coarser spectral resolution.

[^1]: If you're viewing in >2023 I apologise I never got round to doing this!