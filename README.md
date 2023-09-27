# NSSL-Mobile-Mesonet
Respository for the National Severe Storms Laboratory Mobile Mesonet operating code.

This respository serves as a documentation of the Campbell Scientific CR6 data logger code needed to run the NSSL Mobile Mesonet observing system. The code utilizes a specific set of instructions designed to operate very specific instrumentation. Any deviation from the NSSL utilized instruments would require changes to the base operating code and are not guaranteed (or even likely) to work. The basic presmise of this code is to collect observations from the various in situ instruments on the NSSL Mobile Mesonet every second, process some of the necessary data and perform a number of corrections/derivations, store the data in accessible data tables, and publish the data to a locally available web page. This page can be accessed by a direct ethernet link to the logger, or wirelessly if the logger has a wifi adapter. The code and assoicated description of the NSSL mesonet can be found in Waugh (2024).


References:

Waugh, Sean, 2024: An Updated Mobile Mesonet for Meteorological Observations. Journal of Atmospheric and Oceanic Technology, (in progress).
