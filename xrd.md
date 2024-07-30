# XRD

goal for tonight: write about XRR and XRD in masters report
updated goal: only focus on what is necessary to understand xrr and organize somewhere else what im not trying to understand in more depth, whats relevant right now is usefulness

goal: understand the xrd system, understand what the alignmnent does, understand what yuming did, understand 0D detector, understand xrr and the data obtained by xrr, the meaning of the data and what i can estimate, understanding the physical compoenents used in the xrd

so whats important is understanding how the components are installed to give good data, what is the ideal system which is experimentally tried to be achieved
what determines the resolution?

todo:
- look at protoxrd emails
- look at yuming emails
- look at grazing xrd

## XRR notes
todo:
- map out the system and the parameters
- look at the bragg reflection equation and understand what it means 
- look at johns email to know what to answer as questions
- build graph of the applications of XRD, i.e. how the xrd relates to information can probe about a sample (different types of samples: crystal, powder, thin film, etc)
- look at videos for xrr alignment
1. incident optics-->Soller slit, focusing circle
2. detector and ROI
3. receiving optics (see 2.6.4 in hardware manual, the RS position width determines the resolution)
4. list all xrd parameters
5. xrr theory and setup

1. optics
2. detector
3. alignment/calibration, role of knife edge
4. grazing incidence
5. xrr theory

1. basic xrr theory
2. detector
3. alignment meaning

1. read 3.7 in cullity (peak width)
2. better understand xrr theory
3. look at xrr alignment procedure
4. look at xrr for rigaku

1. plan for using xrd tomorrow
2. understand data and whats missing from getting good data
3. write report
4. understand data analysis

**missing**
- equation for thickness of film from xrr data, or relation period with thickness
- understanding of xrr in terms of braggs law

careful not to dig to deep in useless part

* why does the beam reflect of the sample? (index of refraction, density of sample)
* xrd for thin films vs crystals
* missing what the intensity is proportional to in xrd-->see structure factor
* see if there is not some simulation i can do of xrd peaks
* what are the features of the data? (intensity, angle, gaussian shape, etc)
* need to mention specifically what i do with the model im using
* what is diffraction? (xrd==x-ray diffraction) 
	* why is it that diffractions requires the wavelength to be of the order of the slit? (missing a conceptual and physical understanding), it has to do with diffraction, so need to better understand diffraction
	* 
* why use x-rays? 
* why the peaks have a width, why not delta-fcn?
* what is the photon energy of the x-rays important for?
* what do the x-rays interact with when they are reflected?, matter interaction, type of scattering involved
* why em wave must have a wavelength at least as short as the interatomic distance for probing a crystal?
* whats the reason for the order of the optics? what if swapped DS and SS?

* why does light diverges?
* how does the beam divergence affect the peak broadening?
* given the focusing circle geometry, the beam converge to a single point on the detector, how do the divergent beam contribute to the detected beam intensity?
* given ideal convergence of the diffracted beam, does this implies peak broadening due to the beam divergence?
* why is the focusing condition important?
* need to understand the role of the width of the pixel of the detector
* what happens when you change the size of optics?
* what does the x-rays are diffracted from in xrd? (the planes, the unit cell?)
* how is refraction taken into account for xrd? (see chap. 6 in nielsen)

* what causes peak broadening?
* what peaks associated with the planes that are measured must have to do with the penetration depth and the transmission/reflectivity
* why does the Soller slit improves the beam shape?, whats the difference between using a SS and no SS

* understand the relation between xrd, planes of the crystal and unit cell

* is the role of the optics to bring the x-ray beam closer to its ideal case?

* what are braggs law assumption and how does it differ in practice? udnerstanding how a practical system differ from the theory used to interpret the data, this is mostly understanding the origin of the features in data, comparing assumptions with reality/practice 
* what has the size of the crystal to do with bragg law? (chatgpt mentionned finite size of crystal)

numerical understanding:
* what divergence angle is necessary for good resolution?
* 

ask chatgpt:
- how does beam divergence in xrd affects peak broadening?


xrr
* whats the dependence of index of refraction and reflection on density?
* see Fresnel equations
* why are the periodic oscillations indicative of the thickness of the film?
* does bragg still applies at low angles? (except for angles giving complex numbers how does it apply?)
* whats the condition for xrr to xrd transition? (try a scan from 2theta=0 to 20 deg)
* see exercise 3.1 in Nielsen

**levels of abstraction**
light-matter interaction
bragg equation level of understanding (see A&M)

structure for xrd experiments:
- approximation of bragg peaks using bragg equation (substrate and film)
- finding reference of xrd data

**Calculations, estimations and approximations**
- calculation of beam divergence using $\alpha = \frac{D+S}{L}$ (see notes)

masters report:
- starting from xrd machine, describe the functionning of the xrd machine, describe how data are acquired, describe what the data means

---
braggs law is the basis of the xrd, it tells you that the interplanar distance between planes of a crystal is dependent on the angle at which x-rays are incident on the crystal 

it tells you that the diffraction of x-rays with wavelength \lambda on some crystal with interplanar distance d, is dependent on the angle at which the incident rays are shined on the crystal

then it is beam divergence and the geometry of the system

intensity, relative intensity
angle

---
for normal scan, increase the power of the source

safe to do directly expose the detector to the source, i.e. no radiation damage, how can i know at what intensity/power setting i can damage the detector

why is saturation an issue?, detector saturation only means that cant detect more photons because the amount of photons hitting the detector is already maximal

ROI should be centered in the detector (for 640 channels, the center is 320)

**the goal is to get good XRR data**
develop a procedure to take good data
understand what the data are saying: the pattern dep on the angle, how the pattern changes as different parameters are used, 
basically, understand how the data changes when any variable is changed
-->ideally what do i want to achieve?, why are the current data bad? 
what is limiting the data im taking?
SNR
i want to increase the intensity of the reflected beam relative to the background signal
limit background by having the beam more centered on the sample, using small DS, using knife edge

maximize intensity, minimize background

1. what determines xrd resolution? (look at braggs law, detector, slits used)
2. list the possible change that can be done to the system (parameters, alignment, hardware change, modes of operation)
3. understand what the changes do to the data
4. look at XRR alignment steps


- setting the zero angle
- 0D detector mode (or setting the ROI to 1 channel)
- voltage, current of source

- divergence slit width
- knife edge

* dwell time
* step size
* ROI
* angle range

- beam alignment (DS)
- knife edge height
- height sample stage

stage concentricity (p.1)
divergence slit housing height adjustement (p.9)-->asymmetric peak broadening (peak shape)
diffracted side optics height adjustment (SPD only) (p.11)
zero angle adjustement (p.14)-->constant offset at all angles
detector distance (Dectris only) (p.17)
collecting a standard scan using LaB6 (p.18)-->allows to compare current data with properly aligned data to tell what needs alignment


**procedure**
goal-->gather quickly the minimum amount of information about the state of the system to make an adjustement and continue the loop until looks good
*requires i understand what the different patterns found in the data mean*, relate the data to the experimental setup, what pattern is an artifact of the setup?

the important question is: what can be adjusted? (and what is left fixed once the right parameter is found?)
- sample height
look into xrr alignment 

