# rlos2_application
rlos2 code applied to a microquasar jet  

torblob18dummies is the main folder of the repo. There, rlos code resides, using param file no 253. A 254 version now exists, but the added feature at the end is about nemiss, not rlos (nemiss also uses that param file). 

This application is about depicting apparent acceleration of a blob, on the sky plane. This is produced automatically by rlos2, using back in time los integration tecnique. rlos2 ryns on PLUTO data. PLUTO sets the twin jet orientation, in order to facilitate rlos2 calc. 

**How to run**

First, run PLUTO, using the 3 files residing in the main folder: pluto.ini, init.c, definitions.h. These 3 files are enough to setup a PLUTO sim. 

After PLUTO run is complete, we are ready for rlos2. Run it according to instructions. 

Do not forget to first compile and run pload.pro. Careful, our pload.pro is not the original supplied with PLUTO, it is modded according to the 18 dummies standard. 






