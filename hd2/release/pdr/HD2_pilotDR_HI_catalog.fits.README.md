# The HD^2 Pilot Survey Extragalactic HI Source Catalog


## Description

This catalog contains 339 extragalactic HI sources detected in the pilot survey of FAST Hundred-Deg² HI Deep (HD²) Survey, corresponding to Table 5 of Xu et al. 2026 in the FITS format.

Title: The FAST Hundred-Deg^2^ HI Deep (HD^2^) Survey: 
       Early Results from the Pilot Survey 
       
Authors: Xu C., Jing Y., Wang J., Zou H., Du W., Yu N., Guo H., Liu Z., 
         Chen Q., Liang T., Hou Z., Xu Y., Li X., Hu H., Liu Z., Zhao P., 
         Fang T., Gao L., Guo Q., Gu Q., Jiang Z., Kang X., Kong X., Li C.,
         Pan J., Wang T., Zhou Y., Wang W., Wang J. 
     
Version: Pre-release (2026/05, v2.6)

Contact: For questions regarding the catalog, please contact Chen Xu (xuchen@nao.cas.cn).


## Columns

| Column       | Unit      | Description                                                     |
|--------------|-----------|-----------------------------------------------------------------|
| HGCN         | ---       | Unique identifier in Hundred-deg² Galaxy Catalog                |
| Name         | ---       | Source name; format of Jhhmmss.s +ddmmss                        |
| HIRAdeg      | deg       | Flux-weighted HI centroid right ascension (J2000)               |
| HIDEdeg      | deg       | Flux-weighted HI centroid declination (J2000)                   |
| OCRAdeg      | deg       | Right ascension of most probable optical counterpart (J2000)    |
| OCDEdeg      | deg       | Declination of most probable optical counterpart (J2000)        |
| VHel         | km/s      | Heliocentric HI velocity measured (1)                           |
| VOC          | km/s      | Heliocentric velocity of optical counterpart                    |
| Zcmb         | ---       | Redshift in the CMB reference frame                             |
| W50          | km/s      | HI line width at 50% of peak flux (1)                           |
| e_W50        | km/s      | Uncertainty in W50                                              |
| W20          | km/s      | HI line width at 20% of peak flux (1)                           |
| HIflux       | Jy km/s   | Integrated HI flux                                              |
| e_HIflux     | Jy km/s   | Uncertainty in HIflux                                           |
| Speak        | mJy       | Peak flux density                                               |
| RMS          | mJy       | RMS noise of spatially integrated HI spectrum                   |
| SNR          | ---       | Signal-to-noise ratio                                           |
| V85cog       | km/s      | HI line width enclosing 85% of total flux (2)                   |
| e_V85cog     | km/s      | Uncertainty in V85cog                                           |
| HIfluxcog    | Jy km/s   | Total HI (2)                                                    |
| e_HIfluxcog  | Jy km/s   | Uncertainty in HIfluxcog                                        |
| SNRcog       | ---       | Signal-to-noise ratio from curve-of-growth measurement          |
| Dis          | Mpc       | Distance derived from Cosmicflows-4                             |
| logMHI       | solMass   | Logarithm of HI mass in solar unit                              |
| e_logMHI     | solMass   | Uncertainty in logMHI                                           |
| HIcode       | ---       | HI detection category code; G=good, L=low S/N                   |
| OCcode       | ---       | Optical counterpart category code (3)                           |
| PbestOC      | ---       | Probability of the best optical counterpart                     |
| PbestOCRef   | ---       | Reference optical survey used for counterpart matching          |
| No.          | ---       | Internal running sequence number                                |
| sofia_id     | ---       | SoFiA source id                                                 |
| Notes        | ---       | Additional notes just for reference                             |

---

## Notes 

(1): By method given in Sp05 [2005ApJS..160..149S]. 

(2): From curve-of-growth method in Yu20 [2020ApJ...898..102Y].  

(3): G = good;
     B = bad;
     C = confused;
     U = uncertain.
     
2026/05/22, NAOC-CCG