# 2021_Solar_Wind_Velocities

The repositories below are for the processed cometary data analysed and presented in the ***‘Solar Wind Velocities at Comets C/2011 L4 Pan-STARRS and C/2013 R1 Lovejoy derived using a New Image Analysis Technique’ paper. Submitted to JGR - Space Physics. ***

The software can be made available upon request. Please contact the author at yudish@hawaii.edu

Data can be found here: https://neo.ifa.hawaii.edu/users/yudish/2021_Solar_wind_velocities/


**Comet C/2013 R1 (Lovejoy)**

This data was collected from amateur astrophotographers from around the world and observations from the Isaac Newton Telescope undertaken by Y. Ramanjooloo and K. Birkett. The data spanned two weeks on either side of the comet’s perihelion and covers part of Carrington Rotation 2144 and 2145. 

In repository:

1. Image of comet C/2013 R1 (Lovejoy) acquired by G. Rhemann on 13 December 2013 at 03:41 UT

![Image of comet C/2013 R1 (Lovejoy) acquired by G. Rhemann on 13 December 2013 at 03:41 UT](https://neo.ifa.hawaii.edu/users/yudish/2021_Solar_wind_velocities/C2013R1/C2013R1_20131213_0341UT_Rhemann.jpg)

2. Data coverage of C/2013 R1 (Lovejoy) as observed from Earth and mapped onto the comet’s orbital plane. The Sun is at (0,0).

![Data coverage of C/2013 R1 (Lovejoy) as observed from Earth and mapped onto the comet’s orbital plane. The Sun is at (0,0).](https://neo.ifa.hawaii.edu/users/yudish/2021_Solar_wind_velocities/C2013R1/C2013R1_Data_coverage.png)

In 'Earth' directory:

3. [Processed images](https://neo.ifa.hawaii.edu/users/yudish/2021_Solar_wind_velocities/C2013R1/Earth/Processed_images/) - These are the individual fully processed data for each successfully analysed image. The images and orbits are stored in the .sav files. IDL is required to open and analyse these .sav files. 
4. [Low_orbit_plane_ang](https://neo.ifa.hawaii.edu/users/yudish/2021_Solar_wind_velocities/C2013R1/Earth/Low_orbit_plane_ang/) - These are all the images that were processed with the alternative technique to find non-radial velocity flows out of the comet’s plane.





**Comet C/2011 L4 (Pan-STARRS)**

C/2011 L4 (Pan-STARRS) was observed from both Earth and STEREO B. However, images from Earth were not used for this project due to the poor observing geometry. On the other hand, the images from STEREO B provided the highest image quality and time resolution of this comet’s ion tail evolution with the varying solar wind conditions at the head of the comet.


In repository:
1. [Animation of C/2011 L4 (Pan-STARRS) made using difference images from NASA’s STEREO B spacecraft. Each image was mapped onto the comet’s orbital plane with the Sun-comet line fixed. The Sun is to the left of the image.](https://github.com/yramanjooloo/2021a_Solar_Wind_Velocities/blob/main/C2011L4_PANSTARRS/2011l4_STB_anim_20140619.gif)


2. Difference Image of comet C/2011 L4 (Pan-STARRS) as observed by HI1 white-light imager aboard the STEREO B spacecraft. Image taken on 13 March 2013 at 12:49 UT.

![Difference Image of comet C/2011 L4 (Pan-STARRS) as observed by HI1 white-light imager aboard the STEREO B spacecraft. Image taken on 13 March 2013 at 12:49 UT.](https://github.com/yramanjooloo/2021a_Solar_Wind_Velocities/blob/main/C2011L4_PANSTARRS/C2011L4_STB_20130313_1249UT.png)

3. [Processed images](https://neo.ifa.hawaii.edu/users/yudish/2021_Solar_wind_velocities/C2011L4/Processed_images/) - These are the individual fully processed data for each successfully analysed image. These images were collected by the HI1 camera on STEREO B. The images and orbits are stored in the .sav files. IDL is required to open and analyse these .sav files. 
4. [Solar Wind velocities](https://neo.ifa.hawaii.edu/users/yudish/2021_Solar_wind_velocities/C2011L4/SW%20results/) - The SWspeed .sav file is a concatenation of every solar wind velocity derived from each image. This is stored in one file for ease of plotting. The bundlepos .sav file contains cometary positions and the velocities tracked across subsequent images. This is discussed in the Flow Vector Maps section of the paper. 



***Note:***

.sav files are saved variables processed via IDL. More info can be found here:

.sav: https://www.l3harrisgeospatial.com/docs/save.html

IDL : https://www.l3harrisgeospatial.com/



The following python package is available to process .sav files though the authors have no experience with this package.

https://docs.scipy.org/doc/scipy/reference/generated/scipy.io.readsav.html

