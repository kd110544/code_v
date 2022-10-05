Notes for Synopsys - CODE V Optical Design Software
*---*
# [CodeV in OSC Site Licensed Software](https://wp.optics.arizona.edu/helpdesk/osc-site-licensed-software/other-links/)
> password: **OSCstudent**

# [CodeV eLearning Courses - Synopsys](https://www.synopsys.com/optical-solutions/support/online-learning.html/)


# Set stop surface
> STO s1

# Set Dimension in or mm
> dim?
> dim in  
> dim mm

# wavelength 
> wl?

# Paraxial Image Distance (S: Solve)
> PIM 

# List SPECIFICATION DATA
> lis

# Rescale focal length to spec (if needed)
> SCA EFL 100;go

# Lens layout with scale bar 12.5mm
> vie;ssi 12.5;go

# Spot diagram
> spo;go

# Ray aberration curve; transverse ray aberration
> rim;go

# wavefront aberration curve; wavefront error
> rim;wfr;go

# set the scale as 2 wavefront
> rim;wfr;ssi z1 2;go

# Longitudinal Spherical Aberration
> fie;lsa;plo;go

---
## Conjugate Factor
> C = (u1+u2)/(u1-u2)
C = -1 *collimated in*
C = +1 *collimated out*

## Shaper Factor
> B = (C1+C2)/(C1-C2) = (R2+R1)/(R2-R1)


---





### Markdown Guide

> **_NOTE:_**  The note content.

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

www.google.com

