# Equirectangular-toolbox
#### Handy toolbox for equirectangular images  

## Equirectangular to Gnomonic projection
[`nfov.py`](https://github.com/NitishMutha/equirectangular-toolbox/blob/master/nfov.py)
- A tool to extract a normal field of view of any given center point from any given equirectangular image/frame.
- Highly optimized implementation to compute every pixel projection mapping at once, with bilinear interpolation for smoother image.
- References: [mathworld.wolfram.com](http://mathworld.wolfram.com/GnomonicProjection.html), [wikipedia](https://en.wikipedia.org/wiki/Gnomonic_projection)

#### DEMO  
##### Input equirectangular image:
![360.jpg](https://github.com/NitishMutha/equirectangular-toolbox/blob/master/images/360.jpg "Equirectangular image")
^ image taken from internet

##### Normal Field of View output images:  
![nfov.jpg](https://github.com/NitishMutha/equirectangular-toolbox/blob/master/images/sample_nfov.jpg "Equirectangular image")  

![nfov.jpg](https://github.com/NitishMutha/equirectangular-toolbox/blob/master/images/sample_nfov2.jpg "Equirectangular image")

