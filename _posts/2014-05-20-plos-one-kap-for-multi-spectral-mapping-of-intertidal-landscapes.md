---
layout: single
title: "kite aerial photography for spectral mapping of intertidal landscapes"
author: Mathew
toc: true
tags:
 - kites
 - rigs
 - infrared
categories: 
 - post

header:
 image: /assets/images/publiclab/Screen_Shot_2014-05-20_at_9.23.57_AM.png
 teaser: /assets/images/publiclab/Screen_Shot_2014-05-20_at_9.23.57_AM.png
 
---


An article on [two-camera NDVI in intertidal mapping from PLOS One](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0073550), using kites, [via the KAP forums](http://arch.ced.berkeley.edu/kap/discuss/index.php?p=/discussion/5035/kap-for-intertidal-landscape-mapping).

The authors use a color chart and a spectrometer to characterize the spectral response of consumer digital cameras.  I hope we can use this technique to improve our understanding of Infragram cameras. 

**To Quote:**

The spectral response functions of both cameras were determined using the procedure described in [[42](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0073550#pone.0073550-Pike1)], [[43](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0073550#pone.0073550-Finlayson1)] to provide precise information on the spectral sensitivities of the raw imagery from the red, green and blue channels of the colour camera and the near-infrared sensitivity of the converted camera (data was taken only from the red bayer channel of the images for this camera). Images of a Macbeth colour chart were captured using the raw mode of each camera under cloudless sunlight and measurements of the spectral response of each Macbeth colour panel were taken using a handheld spectroradiometer (Ocean Optics STS-VIS with an effective range from 400–800 nm), from which the response curves were estimated. Although the panels of the Macbeth colour chart are designed for use in colour calibration in the visible spectrum, it was found that the panels exhibited variations in reflectance at wavelengths around 720 nm and above, and were therefore also effective for calibrating images captured from the near-infrared converted camera. Figure 3 (a) illustrates the estimated spectral response curves for the camera.


Figure 3. Spectral calibration data.

[![journal.pone.0073550.g003.png](https://i.publiclab.org/system/images/photos/000/004/330/medium/journal.pone.0073550.g003.png)](https://i.publiclab.org/system/images/photos/000/004/330/original/journal.pone.0073550.g003.png)

(a) Spectral response functions for the colour and near-infrared converted cameras: the red, green and blue channels correspond to the three channels of the colour camera whereas the near-infrared curve corresponds to the red channel of the near-infrared converted camera, which was found to have the highest response of each of the channels for this camera. (b) Reflectance spectra for key surface coverage types in the intertidal zone measured using a handheld spectroradiometer. The reflectance spectra were used in conjunction with the camera spectral response functions to validate the measured colour of objects in the kite-based imagery.
doi:10.1371/journal.pone.0073550.g003


Mathew's notes:

The second reference (43) on this paper describing how to calibrate the cameras is "Recovering device sensitivities with quadratic programming." Graham D. Finlayson, Steven Hordley Paul M. Hubel  [Full text here.](http://www.inventoland.net/imaging/JEI/090.PDF)

to quote:
Our approach requires only, that we can record the response of
the device to a number of objects of known surface re-
flectance (for example a Macbeth Color Checker Chart)
under known illumination conditions.
As we will show, the responses of a device (typically a
set of RGB values) are linearly related to the spectral sur-
face reflectance data, and furthermore this relationship is
defined by the sensor response functions. It follows that
we should be able to solve for the sensors by a simple lin-
ear regression. However a a regression of this kind leads to
very poor estimates of the sensors. This poor performance
is due to the limited dimensionality of surface reflectance
functions, which leads to sensor estimates which are highly
sensitive to noise in the device responses. To overcome this
problem we incorporate into the problem formulation a
number of natural constraints; sensitivity functions should
be positive, have limited modality, and be band-limited.
We then solve for the sensor functions by a constrained
regression. The fact that all the constraints are linear al-
lows us to pose the regression in a quadratic programming
form


I have access to the first reference, but it's paywalled.  contact me if you need it.

Using digital cameras to investigate animal colouration: estimating sensor sensitivity functions
    Thomas W. Pike
    Behavioral Ecology and Sociobiology
    Vol. 65, No. 4 (April 2011) (pp. 849-858)
    Page Count: 10

The color target he uses is a [X-Rite Digital ColorChecker](http://www.amazon.com/X-Rite-Color-Checker-Exposure-Aid/dp/B0000ALKEJ/ref=pd_sim_pc_2?ie=UTF8&refRID=0TB4PFPC25NHRBSFFT3C), but the paper on creating such a target is <a href="https://i.publiclab.org/system/images/photos/000/004/361/original/mccamy1976.pdf"><i class="icon icon-file"></i> mccamy1976.pdf</a>

here's a [$10 calibration card.](http://www.amazon.com/DGK-Color-Tools-Balance-Calibration/dp/B00AWT2QCE/ref=pd_cp_p_2)  The DGK Color Tools DKK

### discussion


[@wward1400](https://publiclab.org/profile/wward1400):

Posted in [plots-infrared March 2014](https://groups.google.com/forum/#!searchin/plots-infrared/multispectral/plots-infrared/hZUkVMkUb4M/Y1xu4LkVSF4J)

[Data & Results](http://www-personal.acfr.usyd.edu.au/m.bryson/bryson_etal_2013.html) were included on Mitch Bryson's page.

mathew: 

nice- beat me to it by a bit.

thanks for the link to the data repository

clayton: 

Wouldn't you still need a spectrometer with you to calibrate the panel every time you go out into the field to account for varying lighting conditions?

 
{: .notice} 
Archived 4th of March 2018 [from Publiclab.org](https://publiclab.org/notes/mathew/05-20-2014/plos-one-kap-for-multi-spectral-mapping-of-intertidal-landscapes).

*[CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)*

