# SatelliteObservation
This repository contains the code of:
* generating benchmark instances for the Agile Earth Satellite Observation Problem
* the approaches proposed as well as baselines to solve these instances

The instances are generated from real-world satellite orbits and random observation requests.

## Satellites data
The real-world data used for the satellites' orbits comes from the TLE files from [CelesTrack website]{https://celestrak.org/NORAD/elements/}, which provides information on each satellite's latitude, longitude and altitude at the available points in time from its historic data to calculated predictions.

To extract these information, we refer to the [`PyOrbital` package]{https://pyorbital.readthedocs.io/en/latest/}.
