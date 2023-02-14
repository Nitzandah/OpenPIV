# OpenPIV

basics of OpenPIV in Python are in the documentation and examples: 
  - https://openpiv.readthedocs.io/en/latest/
  - https://github.com/OpenPIV/openpiv-python-examples

The best book on this topic is https://link.springer.com/book/10.1007/978-3-540-72308-0 - we have a copy in the lab

we keep a list of good stuff about PIV https://github.com/alexlib/awesome_piv 

## OpenPIV-Python development options

### Optical flow algorithm 

adding optical flow algorithm to openpiv-python. The idea is to understand the methods used in Matlab and Python for PIV specifically and implement them in the way native for openpiv users. There is a list of repos that might be useful:

- https://github.com/alexlib/openpiv-opticalflow  
- Main one: https://github.com/Tianshu-Liu/OpenOpticalFlow - this is a good Matlab representation that we want to understand most  
- A more updated copy of the same one: https://github.com/Tianshu-Liu/OpenOpticalFlow_PIV_v1  and there is a paper about it https://openresearchsoftware.metajnl.com/article/10.5334/jors.326/ 
- Good Python implementation but a bit more generic, less PIV-related https://github.com/rfezzani/pyimof - we try to use it in ultrasound PIV analysis, it requires some adjustments

### Stereoscopic PIV 

PIV is a two-dimensional method. There is a stereoscopic option for two camera systems, e.g. see here https://velocimetry.net/stereo_principles.htm or whatch here https://www.youtube.com/watch?v=T1J0HcdQUmE also here https://cdn.intechopen.com/pdfs/32254/InTech-Overview_on_stereoscopic_particle_image_velocimetry.pdf 

- Theo Kaufer started some work on this https://github.com/TKaeufer/Open_PIV_mapping but stopped
- I think this software does a great job - https://foss.heptapod.net/fluiddyn/fluidimage/ - also for the optical flow, so take a look. We want a bit simpler implementation, I think. 

