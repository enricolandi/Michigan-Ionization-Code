This is the basic IDL code to calculate he charge state composition of the solar wind. 
Interfaces naturally with CHIANTI through SolarSoft and does not run outside of it, even
in simple IDL.
Run it as

SSWIDL> wind_diagn_3,zeta[,/keywords]

where zeta is the elements' atomic number Z (e.g. Oxygen has Z=8 etc). See the header of 
the main program for more information.
