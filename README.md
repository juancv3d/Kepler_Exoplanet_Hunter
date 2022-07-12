# Kepler_Exoplanet_Hunter

# About Dataset

Context

The Kepler Space Observatory is a NASA-build satellite that was launched in 2009. The telescope is dedicated to searching for exoplanets in star systems besides our own, with the ultimate goal of possibly finding other habitable planets besides our own. The original mission ended in 2013 due to mechanical failures, but the telescope has nevertheless been functional since 2014 on a "K2" extended mission.

Kepler had verified 1284 new exoplanets as of May 2016. As of October 2017 there are over 3000 confirmed exoplanets total (using all detection methods, including ground-based ones). The telescope is still active and continues to collect new data on its extended mission.
Content

This dataset is a cumulative record of all observed Kepler "objects of interest" — basically, all of the approximately 10,000 exoplanet candidates Kepler has taken observations on.

## kepler_data

This dataset has an extensive data dictionary, which can be accessed here. Highlightable columns of note are:

    kepoi_name: A KOI is a target identified by the Kepler Project that displays at least one transit-like sequence within Kepler time-series photometry that appears to be of astrophysical origin and initially consistent with a planetary transit hypothesis
    kepler_name: [These names] are intended to clearly indicate a class of objects that have been confirmed or validated as planets—a step up from the planet candidate designation.
    koi_disposition: The disposition in the literature towards this exoplanet candidate. One of CANDIDATE, FALSE POSITIVE, NOT DISPOSITIONED or CONFIRMED.
    koi_pdisposition: The disposition Kepler data analysis has towards this exoplanet candidate. One of FALSE POSITIVE, NOT DISPOSITIONED, and CANDIDATE.
    koi_score: A value between 0 and 1 that indicates the confidence in the KOI disposition. For CANDIDATEs, a higher value indicates more confidence in its disposition, while for FALSE POSITIVEs, a higher value indicates less confidence in that disposition.

## exoplanets_discovered

    COLUMN sy_snum:        Number of Stars
    COLUMN sy_pnum:        Number of Planets
    COLUMN discoverymethod: Discovery Method
    COLUMN disc_year:      Discovery Year
    COLUMN disc_facility:  Discovery Facility
    COLUMN pl_orbper:      Orbital Period [days]
    COLUMN pl_rade:        Planet Radius [Earth Radius]
    COLUMN pl_radj:        Planet Radius [Jupiter Radius]
    COLUMN pl_bmasse:      Planet Mass or Mass*sin(i) [Earth Mass]
    COLUMN pl_bmassj:      Planet Mass or Mass*sin(i) [Jupiter Mass]
    COLUMN pl_dens:        Planet Density [g/cm**3]

# Acknowledgements

This dataset was published as-is by NASA. You can access the original table [here](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=koi). More information on the columns is available from the same source [here](https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html). Exoplanets plots [here](https://exoplanetarchive.ipac.caltech.edu/exoplanetplots/)
