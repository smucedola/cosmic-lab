sdss_mpajhu_catalogue.fits
---------------------------
Physical parameters of galaxies in SDSS DR8 using the MPA-JHU spectroscopic pipeline.
Details of the dataset can be found here:
https://www.sdss.org/dr14/spectro/galaxy_mpajhu/

A description of the columns:
SDSS_SpecObjID = SDSS unique spectroscopic ID
RA_degree = Right Ascension (J2000) (degrees)
Dec_degree = Declination (J2000) (degrees)
Redshift = best estimate for the redshift of the source
Log_stellar_mass_Msun = The median estimate of the log10 total stellar mass PDF using model photometry (Msun)
Log_SFR_Msun_yr = The median estimate of the log10 total SFR PDF. This is derived by combining nebular emission line measurements and model fits to the integrated photometry when emission line measurements are not possible. See Gallazzi et al (2005) and Salim et al (2007) for details. (Msun/yr)
Metallcity_nebular = The median estimate of the Oxygen abundance derived using Charlot & Longhetti models. The values are reported as 12 + Log O/H. See Tremonti et al (2004) and Brinchmann et al (2004) for details.
Redshift_flag = Redshift is reliable if this flag is 0, unreliable redshift if this flag is non-zero
Parameter_flag = Physical parameters are reliable if this flag is 1, unreliable if this flag is 0 

sdss_mpajhu_lineflux.fits
-------------------------
Fluxes and error in fluxes of the emission lines (Halpha, Hbeta, OIII_5007A, NII_6548A) of galaxies in the above SDSS DR8 MPA-JHU catalogue from Gaussian fitting in units of 10^-17 erg/s/cm2.

sdss_portsmouth_starforming_catalogue.fits
-------------------------------------------
Physical parameters of galaxies in SDSS DR8 using Spectro-Photometric Model Fitting with Kroupa IMF and Star-forming stellar population models from the Portsmouth Group.
Details of the dataset can be found here:
https://www.sdss.org/dr14/spectro/galaxy_portsmouth/

A description of the columns:
SDSS_SpecObjID = SDSS unique spectroscopic ID
RA_degree = Right Ascension (J2000) (degrees)
Dec_degree = Declination (J2000) (degrees)
Redshift = best estimate for the redshift of the source
Log_stellar_mass_Msun = Best-fit log10 stellar mass from continuum fitting (Msun)
SFR_Msun_yr = Best-fit SFR from continuum fitting (Msun/yr)
Age_Gyr = Best-fit age from continuum fitting (Gyr)
Metallcity_stellar = Best-fit stellar population metallicity. One of 4 metallicities (Z = 0.004, 0.01, 0.02, 0.04), where 0.02 is solar metallicity

sdss_portsmouth_passive_catalogue.fits
---------------------------------------
Same as above but using Passive stellar population models. The minimum age is set to be 3 Gyr.
Metallicity_stellar = COMPOSITE, i.e. 97% by mass of a solar metallicity (Z=0.02) simple stellar population (SSP) plus 3% by mass of a metal-poor SSP, both coeval

3dhst_catalogue.fits
---------------------
A catalogue with the results of the stellar population fitting run on the 3D-HST fields using the FAST code. 
The papers explaining the dataset in detail are:
https://ui.adsabs.harvard.edu/abs/2016ApJS..225...27M/abstract
https://ui.adsabs.harvard.edu/abs/2014ApJS..214...24S/abstract

A description of the columns:
ID = Unique identifier
RA_degree = Right Ascension (J2000) (degrees)
Dec_degree = Declination (J2000) (degrees)
Redshift = best estimate for the redshift of the source
Log_stellar_mass_Msun = log10 of the stellar mass (Msun)
Log_SFR_Msun_yr = log10 of the SFR (Msun/yr)
Metallcity_stellar = metallicity of the stellar population model (0.02 is solar metallcity)
Log_age_yr = log10 of the age of the SFH (yr)
Av_mag = Dust extinction in V-band (mag)
