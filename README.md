# Maclock Screen Mount for Adafruit/SHARP Memory Display

<div align="center">
<img src="images/maclock_finished.png" width="50%" alt="A picture showing the finshed product, a Sharp Memory Display mounted inside the Maclock. The Macintosh 'hello' text is shown on the screen." >
</div>

This repository contains STL and FreeCAD files for a screen adapter that allows you to mount the [Adafruit SHARP Memory Display](https://www.adafruit.com/product/4694?srsltid=AfmBOop2fba985qKqFtM6lWqFD_dQ7sxt8O5NbKmIlSQCmeBmKEhnr0H) into the Maclock enclosure.

## Background

For those unaware, the Maclock is a cool little Mac-inspired clock that you can (somehow still?) buy for around $20. 

I bought one with the idea of replacing the internals with an e-paper display (and new controller board).

Finding a e-paper screen turned out to be a challenge. Most available e-paper displays are either too large or have a weird aspect ratio (I think most of the e-paper displays in this ~2.7inch size category are desinged for digital price tags).

I ended up stumbling upon the [Adafruit SHARP Memory Display Breakout - 2.7" 400x240 Monochrome](https://www.adafruit.com/product/4694?srsltid=AfmBOop2fba985qKqFtM6lWqFD_dQ7sxt8O5NbKmIlSQCmeBmKEhnr0H).

I had never heard of this type of display before, but it has a similar viewing experience to e-paper displays, and (more importantly) it fits in the Maclock!

I desinged two 3D-printable parts which can be used to mount this screen nicely into the Maclock housing with no modifications required (other than disassembly).

## Files

```
freecad/
├─ SharpDisplayV10.FCStd            - The FreeCAD project containing both parts
stl/
├─ SharpDisplayV10-Bracket.stl      - The bracket which mounts the screen to the Maclock frame.
├─ SharpDisplayV10-ScreenCover.stl  - The screen cover which fills the gaps on the screen to give a clean look.
```

Apologies in advance to any profesional CAD users who venture into the FreeCAD project.

### Bracket 

```stl
solid Mesh
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -34.250000 -8.000000 31.280001
      vertex -34.250000 -5.000000 31.280001
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -34.250000 -5.000000 31.280001
      vertex -34.250000 -5.000000 26.030001
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 26.030001
      vertex -34.250000 -8.000000 31.280001
      vertex -34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -34.250000 -8.000000 26.030001
      vertex -34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -34.250000 -9.000000 -36.849998
      vertex -34.250000 -9.000000 26.030001
      vertex -34.250000 -8.000000 26.030001
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -34.250000 -9.000000 -36.849998
      vertex -34.250000 -8.000000 26.030001
      vertex -34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -31.039919 -8.000000 27.971270
      vertex -25.000000 -8.000000 26.030001
      vertex -30.814362 -8.000000 28.171097
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -30.643181 -8.000000 28.419096
      vertex -30.814362 -8.000000 28.171097
      vertex -25.000000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -31.306744 -8.000000 27.831230
      vertex -25.000000 -8.000000 26.030001
      vertex -31.039919 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -30.536324 -8.000000 28.700855
      vertex -30.643181 -8.000000 28.419096
      vertex -25.000000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -30.500000 -8.000000 29.000000
      vertex -25.000000 -8.000000 26.030001
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -30.500000 -8.000000 29.000000
      vertex -30.536324 -8.000000 28.700855
      vertex -25.000000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -30.536324 -8.000000 29.299145
      vertex -30.500000 -8.000000 29.000000
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -30.643181 -8.000000 29.580904
      vertex -30.536324 -8.000000 29.299145
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 26.030001
      vertex -31.306744 -8.000000 27.831230
      vertex -31.599329 -8.000000 27.759113
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 26.030001
      vertex -31.599329 -8.000000 27.759113
      vertex -31.900671 -8.000000 27.759113
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 26.030001
      vertex -31.900671 -8.000000 27.759113
      vertex -32.193256 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 26.030001
      vertex -25.000000 -8.000000 26.030001
      vertex -31.306744 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -32.460079 -8.000000 27.971270
      vertex -34.250000 -8.000000 26.030001
      vertex -32.193256 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -30.814362 -8.000000 29.828903
      vertex -30.643181 -8.000000 29.580904
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -32.685638 -8.000000 28.171097
      vertex -34.250000 -8.000000 26.030001
      vertex -32.460079 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -31.039919 -8.000000 30.028730
      vertex -30.814362 -8.000000 29.828903
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -32.856819 -8.000000 28.419096
      vertex -34.250000 -8.000000 26.030001
      vertex -32.685638 -8.000000 28.171097
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -31.306744 -8.000000 30.168770
      vertex -31.039919 -8.000000 30.028730
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -32.963676 -8.000000 28.700855
      vertex -34.250000 -8.000000 26.030001
      vertex -32.856819 -8.000000 28.419096
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -31.599329 -8.000000 30.240887
      vertex -31.306744 -8.000000 30.168770
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -33.000000 -8.000000 29.000000
      vertex -34.250000 -8.000000 26.030001
      vertex -32.963676 -8.000000 28.700855
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 31.280001
      vertex -33.000000 -8.000000 29.000000
      vertex -32.963676 -8.000000 29.299145
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 31.280001
      vertex -32.963676 -8.000000 29.299145
      vertex -32.856819 -8.000000 29.580904
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 31.280001
      vertex -32.856819 -8.000000 29.580904
      vertex -32.685638 -8.000000 29.828903
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 31.280001
      vertex -32.685638 -8.000000 29.828903
      vertex -32.460079 -8.000000 30.028730
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 31.280001
      vertex -32.460079 -8.000000 30.028730
      vertex -32.193256 -8.000000 30.168770
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 31.280001
      vertex -32.193256 -8.000000 30.168770
      vertex -31.900671 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 31.280001
      vertex -31.900671 -8.000000 30.240887
      vertex -31.599329 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 31.280001
      vertex -31.599329 -8.000000 30.240887
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -8.000000 31.280001
      vertex -34.250000 -8.000000 26.030001
      vertex -33.000000 -8.000000 29.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -34.250000 -9.000000 26.030001
      vertex -25.000000 -9.000000 26.030001
      vertex -25.000000 -8.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -34.250000 -8.000000 26.030001
      vertex -34.250000 -9.000000 26.030001
      vertex -25.000000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 3.000000
      vertex -25.000000 -9.000000 26.030001
      vertex -34.250000 -9.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -11.000000
      vertex -25.000000 -9.000000 3.000000
      vertex -34.250000 -9.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -31.710081 -9.000000 -33.971272
      vertex -25.000000 -9.000000 -11.000000
      vertex -31.935638 -9.000000 -34.171097
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -31.443256 -9.000000 -33.831230
      vertex -25.000000 -9.000000 -11.000000
      vertex -31.710081 -9.000000 -33.971272
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -9.000000 -36.849998
      vertex -32.213676 -9.000000 -34.700855
      vertex -32.106819 -9.000000 -34.419098
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -9.000000 -36.849998
      vertex -32.106819 -9.000000 -34.419098
      vertex -31.935638 -9.000000 -34.171097
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -9.000000 -36.849998
      vertex -25.000000 -9.000000 -11.000000
      vertex -34.250000 -9.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -34.250000 -9.000000 -36.849998
      vertex -31.935638 -9.000000 -34.171097
      vertex -25.000000 -9.000000 -11.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -31.150671 -9.000000 -33.759113
      vertex -25.000000 -9.000000 -11.000000
      vertex -31.443256 -9.000000 -33.831230
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -32.250000 -9.000000 -35.000000
      vertex -32.213676 -9.000000 -34.700855
      vertex -34.250000 -9.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -30.849329 -9.000000 -33.759113
      vertex -25.000000 -9.000000 -11.000000
      vertex -31.150671 -9.000000 -33.759113
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -32.213676 -9.000000 -35.299145
      vertex -32.250000 -9.000000 -35.000000
      vertex -34.250000 -9.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -32.106819 -9.000000 -35.580902
      vertex -32.213676 -9.000000 -35.299145
      vertex -34.250000 -9.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -31.935638 -9.000000 -35.828903
      vertex -32.106819 -9.000000 -35.580902
      vertex -34.250000 -9.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -31.710081 -9.000000 -36.028728
      vertex -31.935638 -9.000000 -35.828903
      vertex -34.250000 -9.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -31.443256 -9.000000 -36.168770
      vertex -31.710081 -9.000000 -36.028728
      vertex -34.250000 -9.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -31.150671 -9.000000 -36.240887
      vertex -31.443256 -9.000000 -36.168770
      vertex -34.250000 -9.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -30.849329 -9.000000 -36.240887
      vertex -31.150671 -9.000000 -36.240887
      vertex -34.250000 -9.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -29.750000 -9.000000 -35.000000
      vertex -29.786324 -9.000000 -35.299145
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -29.786324 -9.000000 -35.299145
      vertex -29.893181 -9.000000 -35.580902
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -29.893181 -9.000000 -35.580902
      vertex -30.064362 -9.000000 -35.828903
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -30.064362 -9.000000 -35.828903
      vertex -30.289919 -9.000000 -36.028728
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -30.849329 -9.000000 -33.759113
      vertex -30.556744 -9.000000 -33.831230
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -30.556744 -9.000000 -33.831230
      vertex -30.289919 -9.000000 -33.971272
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -30.289919 -9.000000 -33.971272
      vertex -30.064362 -9.000000 -34.171097
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -30.064362 -9.000000 -34.171097
      vertex -29.893181 -9.000000 -34.419098
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -29.893181 -9.000000 -34.419098
      vertex -29.786324 -9.000000 -34.700855
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -29.786324 -9.000000 -34.700855
      vertex -29.750000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -25.000000 -9.000000 -11.000000
      vertex -30.849329 -9.000000 -33.759113
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -9.000000 3.000000
      vertex 34.250000 -9.000000 26.030001
      vertex 25.000000 -9.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -9.000000 -11.000000
      vertex 25.000000 -9.000000 3.000000
      vertex -25.000000 -9.000000 3.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -9.000000 -11.000000
      vertex -25.000000 -9.000000 3.000000
      vertex -25.000000 -9.000000 -11.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 0.000000 -9.000000 -36.849949
      vertex -30.849329 -9.000000 -36.240887
      vertex -34.250000 -9.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.000000 -9.000000 -36.849949
      vertex -25.000000 -9.000000 -33.000000
      vertex -30.289919 -9.000000 -36.028728
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.000000 -9.000000 -36.849949
      vertex -30.289919 -9.000000 -36.028728
      vertex -30.556744 -9.000000 -36.168770
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.000000 -9.000000 -36.849949
      vertex -30.556744 -9.000000 -36.168770
      vertex -30.849329 -9.000000 -36.240887
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 29.289919 -9.000000 -33.971272
      vertex 25.000000 -9.000000 -33.000000
      vertex 29.064362 -9.000000 -34.171097
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 28.893181 -9.000000 -34.419098
      vertex 29.064362 -9.000000 -34.171097
      vertex 25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 29.556744 -9.000000 -33.831230
      vertex 25.000000 -9.000000 -33.000000
      vertex 29.289919 -9.000000 -33.971272
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 28.786324 -9.000000 -34.700855
      vertex 28.893181 -9.000000 -34.419098
      vertex 25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 29.849329 -9.000000 -33.759113
      vertex 25.000000 -9.000000 -33.000000
      vertex 29.556744 -9.000000 -33.831230
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 29.849329 -9.000000 -33.759113
      vertex 25.000000 -9.000000 -11.000000
      vertex 25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 28.750000 -9.000000 -35.000000
      vertex 28.786324 -9.000000 -34.700855
      vertex 25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 30.150671 -9.000000 -33.759113
      vertex 25.000000 -9.000000 -11.000000
      vertex 29.849329 -9.000000 -33.759113
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 28.786324 -9.000000 -35.299145
      vertex 28.750000 -9.000000 -35.000000
      vertex 25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 30.443256 -9.000000 -33.831230
      vertex 25.000000 -9.000000 -11.000000
      vertex 30.150671 -9.000000 -33.759113
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 28.893181 -9.000000 -35.580902
      vertex 28.786324 -9.000000 -35.299145
      vertex 25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 30.710081 -9.000000 -33.971272
      vertex 25.000000 -9.000000 -11.000000
      vertex 30.443256 -9.000000 -33.831230
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 29.064362 -9.000000 -35.828903
      vertex 25.000000 -9.000000 -33.000000
      vertex 0.000000 -9.000000 -36.849949
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 29.064362 -9.000000 -35.828903
      vertex 28.893181 -9.000000 -35.580902
      vertex 25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 30.935638 -9.000000 -34.171097
      vertex 25.000000 -9.000000 -11.000000
      vertex 30.710081 -9.000000 -33.971272
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 29.289919 -9.000000 -36.028728
      vertex 29.064362 -9.000000 -35.828903
      vertex 0.000000 -9.000000 -36.849949
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 29.556744 -9.000000 -36.168770
      vertex 29.289919 -9.000000 -36.028728
      vertex 0.000000 -9.000000 -36.849949
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 29.849329 -9.000000 -36.240887
      vertex 29.556744 -9.000000 -36.168770
      vertex 0.000000 -9.000000 -36.849949
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 31.250000 -9.000000 -35.000000
      vertex 31.213676 -9.000000 -35.299145
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 31.213676 -9.000000 -35.299145
      vertex 31.106819 -9.000000 -35.580902
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 31.106819 -9.000000 -35.580902
      vertex 30.935638 -9.000000 -35.828903
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 30.935638 -9.000000 -35.828903
      vertex 30.710081 -9.000000 -36.028728
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 30.710081 -9.000000 -36.028728
      vertex 30.443256 -9.000000 -36.168770
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 30.443256 -9.000000 -36.168770
      vertex 30.150671 -9.000000 -36.240887
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 30.150671 -9.000000 -36.240887
      vertex 29.849329 -9.000000 -36.240887
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 30.935638 -9.000000 -34.171097
      vertex 31.106819 -9.000000 -34.419098
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 31.106819 -9.000000 -34.419098
      vertex 31.213676 -9.000000 -34.700855
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 31.213676 -9.000000 -34.700855
      vertex 31.250000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 25.000000 -9.000000 -11.000000
      vertex 30.935638 -9.000000 -34.171097
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 29.849329 -9.000000 -36.240887
      vertex 0.000000 -9.000000 -36.849949
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 34.250000 -9.000000 26.030001
      vertex 25.000000 -9.000000 3.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 25.000000 -9.000000 3.000000
      vertex 25.000000 -9.000000 -11.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -9.000000 -33.000000
      vertex -25.000000 -9.000000 -33.000000
      vertex 0.000000 -9.000000 -36.849949
    endloop
  endfacet
  facet normal 0.000001 0.000000 -1.000000
    outer loop
      vertex 0.000000 -9.000000 -36.849949
      vertex -34.250000 -9.000000 -36.849998
      vertex -34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000001 -0.000011 -1.000000
    outer loop
      vertex 0.000000 -9.000000 -36.849949
      vertex -34.250000 -7.000000 -36.849998
      vertex 0.000000 -7.000000 -36.849972
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 29.834871 -7.000000 24.305283
      vertex 34.250000 -7.000000 26.030001
      vertex 30.033361 -7.000000 24.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.184002 -7.000000 23.911196
      vertex 30.033361 -7.000000 24.129435
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 29.600065 -7.000000 24.428518
      vertex 34.250000 -7.000000 26.030001
      vertex 29.834871 -7.000000 24.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.278036 -7.000000 23.663248
      vertex 30.184002 -7.000000 23.911196
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 29.342590 -7.000000 24.491980
      vertex 34.250000 -7.000000 26.030001
      vertex 29.600065 -7.000000 24.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.309999 -7.000000 23.400000
      vertex 30.278036 -7.000000 23.663248
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.278036 -7.000000 23.136753
      vertex 30.309999 -7.000000 23.400000
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.184002 -7.000000 22.888805
      vertex 30.278036 -7.000000 23.136753
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.033361 -7.000000 22.670565
      vertex 30.184002 -7.000000 22.888805
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 28.110001 -7.000000 23.400000
      vertex 28.141964 -7.000000 23.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 28.141964 -7.000000 23.136753
      vertex 28.235998 -7.000000 22.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 28.235998 -7.000000 22.888805
      vertex 28.386639 -7.000000 22.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 29.342590 -7.000000 24.491980
      vertex 29.077410 -7.000000 24.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 29.077410 -7.000000 24.491980
      vertex 28.819935 -7.000000 24.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 28.819935 -7.000000 24.428518
      vertex 28.585129 -7.000000 24.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 28.585129 -7.000000 24.305283
      vertex 28.386639 -7.000000 24.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 28.386639 -7.000000 24.129435
      vertex 28.235998 -7.000000 23.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 28.235998 -7.000000 23.911196
      vertex 28.141964 -7.000000 23.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 28.141964 -7.000000 23.663248
      vertex 28.110001 -7.000000 23.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 34.250000 -7.000000 26.030001
      vertex 29.342590 -7.000000 24.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 3.000000
      vertex 28.386639 -7.000000 22.670565
      vertex 28.585129 -7.000000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 3.000000
      vertex 28.585129 -7.000000 22.494719
      vertex 28.819935 -7.000000 22.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 3.000000
      vertex 28.819935 -7.000000 22.371483
      vertex 29.077410 -7.000000 22.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 3.000000
      vertex 29.077410 -7.000000 22.308020
      vertex 29.342590 -7.000000 22.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 3.000000
      vertex 29.342590 -7.000000 22.308020
      vertex 29.600065 -7.000000 22.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 3.000000
      vertex 29.600065 -7.000000 22.371483
      vertex 29.834871 -7.000000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 3.000000
      vertex 29.834871 -7.000000 22.494719
      vertex 30.033361 -7.000000 22.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 3.000000
      vertex 25.000000 -7.000000 26.030001
      vertex 28.386639 -7.000000 22.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 3.000000
      vertex 30.033361 -7.000000 22.670565
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 29.834871 -7.000000 -26.494719
      vertex 25.000000 -7.000000 -11.000000
      vertex 30.033361 -7.000000 -26.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.184002 -7.000000 -26.888805
      vertex 25.000000 -7.000000 3.000000
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.184002 -7.000000 -26.888805
      vertex 25.000000 -7.000000 -11.000000
      vertex 25.000000 -7.000000 3.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.184002 -7.000000 -26.888805
      vertex 30.033361 -7.000000 -26.670565
      vertex 25.000000 -7.000000 -11.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 29.600065 -7.000000 -26.371483
      vertex 25.000000 -7.000000 -11.000000
      vertex 29.834871 -7.000000 -26.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.278036 -7.000000 -27.136753
      vertex 30.184002 -7.000000 -26.888805
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 29.342590 -7.000000 -26.308020
      vertex 25.000000 -7.000000 -11.000000
      vertex 29.600065 -7.000000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.077410 -7.000000 -26.308020
      vertex 25.000000 -7.000000 -11.000000
      vertex 29.342590 -7.000000 -26.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.819935 -7.000000 -26.371483
      vertex 25.000000 -7.000000 -11.000000
      vertex 29.077410 -7.000000 -26.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.585129 -7.000000 -26.494719
      vertex 25.000000 -7.000000 -11.000000
      vertex 28.819935 -7.000000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.386639 -7.000000 -26.670565
      vertex 25.000000 -7.000000 -11.000000
      vertex 28.585129 -7.000000 -26.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.235998 -7.000000 -26.888805
      vertex 25.000000 -7.000000 -11.000000
      vertex 28.386639 -7.000000 -26.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.141964 -7.000000 -27.136753
      vertex 25.000000 -7.000000 -11.000000
      vertex 28.235998 -7.000000 -26.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 34.250000 -7.000000 -36.849998
      vertex 30.278036 -7.000000 -27.136753
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -7.000000 -36.849998
      vertex 30.184002 -7.000000 -27.911196
      vertex 30.278036 -7.000000 -27.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -7.000000 -36.849998
      vertex 30.278036 -7.000000 -27.663248
      vertex 30.309999 -7.000000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -7.000000 -36.849998
      vertex 30.309999 -7.000000 -27.400000
      vertex 30.278036 -7.000000 -27.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.935638 -7.000000 -34.171097
      vertex 30.033361 -7.000000 -28.129435
      vertex 30.184002 -7.000000 -27.911196
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 30.935638 -7.000000 -34.171097
      vertex 30.184002 -7.000000 -27.911196
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.710081 -7.000000 -33.971272
      vertex 29.834871 -7.000000 -28.305283
      vertex 30.033361 -7.000000 -28.129435
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 30.710081 -7.000000 -33.971272
      vertex 30.033361 -7.000000 -28.129435
      vertex 30.935638 -7.000000 -34.171097
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 31.106819 -7.000000 -34.419098
      vertex 30.935638 -7.000000 -34.171097
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.443256 -7.000000 -33.831230
      vertex 29.600065 -7.000000 -28.428518
      vertex 29.834871 -7.000000 -28.305283
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 30.443256 -7.000000 -33.831230
      vertex 29.834871 -7.000000 -28.305283
      vertex 30.710081 -7.000000 -33.971272
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 31.213676 -7.000000 -34.700855
      vertex 31.106819 -7.000000 -34.419098
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.150671 -7.000000 -33.759113
      vertex 29.342590 -7.000000 -28.491980
      vertex 29.600065 -7.000000 -28.428518
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 30.150671 -7.000000 -33.759113
      vertex 29.600065 -7.000000 -28.428518
      vertex 30.443256 -7.000000 -33.831230
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 31.250000 -7.000000 -35.000000
      vertex 31.213676 -7.000000 -34.700855
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.849329 -7.000000 -33.759113
      vertex 29.077410 -7.000000 -28.491980
      vertex 29.342590 -7.000000 -28.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.849329 -7.000000 -33.759113
      vertex 29.342590 -7.000000 -28.491980
      vertex 30.150671 -7.000000 -33.759113
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 31.213676 -7.000000 -35.299145
      vertex 31.250000 -7.000000 -35.000000
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.556744 -7.000000 -33.831230
      vertex 29.077410 -7.000000 -28.491980
      vertex 29.849329 -7.000000 -33.759113
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.556744 -7.000000 -33.831230
      vertex 28.819935 -7.000000 -28.428518
      vertex 29.077410 -7.000000 -28.491980
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -28.585129 -7.000000 24.305283
      vertex -25.000000 -7.000000 26.030001
      vertex -28.386639 -7.000000 24.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -28.235998 -7.000000 23.911196
      vertex -28.386639 -7.000000 24.129435
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -28.819935 -7.000000 24.428518
      vertex -25.000000 -7.000000 26.030001
      vertex -28.585129 -7.000000 24.305283
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 31.106819 -7.000000 -35.580902
      vertex 31.213676 -7.000000 -35.299145
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -28.141964 -7.000000 23.663248
      vertex -28.235998 -7.000000 23.911196
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -29.077410 -7.000000 24.491980
      vertex -25.000000 -7.000000 26.030001
      vertex -28.819935 -7.000000 24.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.289919 -7.000000 -33.971272
      vertex 28.819935 -7.000000 -28.428518
      vertex 29.556744 -7.000000 -33.831230
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -28.110001 -7.000000 23.400000
      vertex -28.141964 -7.000000 23.663248
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.342590 -7.000000 24.491980
      vertex -25.000000 -7.000000 26.030001
      vertex -29.077410 -7.000000 24.491980
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 30.935638 -7.000000 -35.828903
      vertex 31.106819 -7.000000 -35.580902
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.141964 -7.000000 23.136753
      vertex -28.110001 -7.000000 23.400000
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 30.710081 -7.000000 -36.028728
      vertex 30.935638 -7.000000 -35.828903
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -7.000000 22.888805
      vertex -28.141964 -7.000000 23.136753
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.386639 -7.000000 22.670565
      vertex -28.235998 -7.000000 22.888805
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 30.443256 -7.000000 -36.168770
      vertex 30.710081 -7.000000 -36.028728
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 30.150671 -7.000000 -36.240887
      vertex 30.443256 -7.000000 -36.168770
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 29.849329 -7.000000 -36.240887
      vertex 30.150671 -7.000000 -36.240887
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.786324 -7.000000 -34.700855
      vertex 28.750000 -7.000000 -35.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.893181 -7.000000 -34.419098
      vertex 28.786324 -7.000000 -34.700855
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 29.064362 -7.000000 -34.171097
      vertex 28.893181 -7.000000 -34.419098
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 29.289919 -7.000000 -33.971272
      vertex 29.064362 -7.000000 -34.171097
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.819935 -7.000000 -28.428518
      vertex 29.289919 -7.000000 -33.971272
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 25.000000 -7.000000 -11.000000
      vertex 28.141964 -7.000000 -27.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.110001 -7.000000 -27.400000
      vertex 28.141964 -7.000000 -27.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.141964 -7.000000 -27.663248
      vertex 28.235998 -7.000000 -27.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.235998 -7.000000 -27.911196
      vertex 28.386639 -7.000000 -28.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.386639 -7.000000 -28.129435
      vertex 28.585129 -7.000000 -28.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.585129 -7.000000 -28.305283
      vertex 28.819935 -7.000000 -28.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.141964 -7.000000 -27.136753
      vertex 28.110001 -7.000000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.893181 -7.000000 -35.580902
      vertex 29.064362 -7.000000 -35.828903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.786324 -7.000000 -35.299145
      vertex 28.893181 -7.000000 -35.580902
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex 28.750000 -7.000000 -35.000000
      vertex 28.786324 -7.000000 -35.299145
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -29.342590 -7.000000 24.491980
      vertex -29.600065 -7.000000 24.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -29.600065 -7.000000 24.428518
      vertex -29.834871 -7.000000 24.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -29.834871 -7.000000 24.305283
      vertex -30.033361 -7.000000 24.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -30.033361 -7.000000 24.129435
      vertex -30.184002 -7.000000 23.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -30.184002 -7.000000 23.911196
      vertex -30.278036 -7.000000 23.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -30.278036 -7.000000 23.663248
      vertex -30.309999 -7.000000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -30.309999 -7.000000 23.400000
      vertex -30.278036 -7.000000 23.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -30.278036 -7.000000 23.136753
      vertex -30.184002 -7.000000 22.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -30.184002 -7.000000 22.888805
      vertex -30.033361 -7.000000 22.670565
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -25.000000 -7.000000 26.030001
      vertex -29.342590 -7.000000 24.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -30.033361 -7.000000 22.670565
      vertex -29.834871 -7.000000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -29.834871 -7.000000 22.494719
      vertex -29.600065 -7.000000 22.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -29.600065 -7.000000 22.371483
      vertex -29.342590 -7.000000 22.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -29.342590 -7.000000 22.308020
      vertex -29.077410 -7.000000 22.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -28.386639 -7.000000 22.670565
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -29.077410 -7.000000 22.308020
      vertex -28.819935 -7.000000 22.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -28.819935 -7.000000 22.371483
      vertex -28.585129 -7.000000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -28.585129 -7.000000 22.494719
      vertex -28.386639 -7.000000 22.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -34.250000 -7.000000 26.030001
      vertex -30.033361 -7.000000 22.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 -11.000000
      vertex 25.000000 -7.000000 3.000000
      vertex 25.000000 -7.000000 -11.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 -11.000000
      vertex -25.000000 -7.000000 3.000000
      vertex 25.000000 -7.000000 3.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 0.000000 -7.000000 -36.849972
      vertex 25.000000 -7.000000 -33.000000
      vertex 29.064362 -7.000000 -35.828903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 0.000000 -7.000000 -36.849972
      vertex 29.556744 -7.000000 -36.168770
      vertex 29.849329 -7.000000 -36.240887
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 0.000000 -7.000000 -36.849972
      vertex 29.289919 -7.000000 -36.028728
      vertex 29.556744 -7.000000 -36.168770
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 0.000000 -7.000000 -36.849972
      vertex 29.064362 -7.000000 -35.828903
      vertex 29.289919 -7.000000 -36.028728
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -28.585129 -7.000000 -26.494719
      vertex -25.000000 -7.000000 -11.000000
      vertex -28.386639 -7.000000 -26.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -28.235998 -7.000000 -26.888805
      vertex -28.386639 -7.000000 -26.670565
      vertex -25.000000 -7.000000 -11.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -28.819935 -7.000000 -26.371483
      vertex -25.000000 -7.000000 -11.000000
      vertex -28.585129 -7.000000 -26.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -28.141964 -7.000000 -27.136753
      vertex -28.235998 -7.000000 -26.888805
      vertex -25.000000 -7.000000 -11.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -29.077410 -7.000000 -26.308020
      vertex -25.000000 -7.000000 -11.000000
      vertex -28.819935 -7.000000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.342590 -7.000000 -26.308020
      vertex -25.000000 -7.000000 -11.000000
      vertex -29.077410 -7.000000 -26.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.600065 -7.000000 -26.371483
      vertex -25.000000 -7.000000 -11.000000
      vertex -29.342590 -7.000000 -26.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.834871 -7.000000 -26.494719
      vertex -25.000000 -7.000000 -11.000000
      vertex -29.600065 -7.000000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.033361 -7.000000 -26.670565
      vertex -25.000000 -7.000000 -11.000000
      vertex -29.834871 -7.000000 -26.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -7.000000 -26.888805
      vertex -25.000000 -7.000000 -11.000000
      vertex -30.033361 -7.000000 -26.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -25.000000 -7.000000 -33.000000
      vertex -28.141964 -7.000000 -27.136753
      vertex -25.000000 -7.000000 -11.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 -33.000000
      vertex -28.110001 -7.000000 -27.400000
      vertex -28.141964 -7.000000 -27.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 -33.000000
      vertex -28.819935 -7.000000 -28.428518
      vertex -28.585129 -7.000000 -28.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 -33.000000
      vertex -28.585129 -7.000000 -28.305283
      vertex -28.386639 -7.000000 -28.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 -33.000000
      vertex -28.386639 -7.000000 -28.129435
      vertex -28.235998 -7.000000 -27.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 -33.000000
      vertex -28.235998 -7.000000 -27.911196
      vertex -28.141964 -7.000000 -27.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 -33.000000
      vertex -28.141964 -7.000000 -27.663248
      vertex -28.110001 -7.000000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.064362 -7.000000 -34.171097
      vertex -28.819935 -7.000000 -28.428518
      vertex -25.000000 -7.000000 -33.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -30.289919 -7.000000 -33.971272
      vertex -28.819935 -7.000000 -28.428518
      vertex -30.064362 -7.000000 -34.171097
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.289919 -7.000000 -33.971272
      vertex -29.077410 -7.000000 -28.491980
      vertex -28.819935 -7.000000 -28.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.893181 -7.000000 -34.419098
      vertex -30.064362 -7.000000 -34.171097
      vertex -25.000000 -7.000000 -33.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -30.556744 -7.000000 -33.831230
      vertex -29.077410 -7.000000 -28.491980
      vertex -30.289919 -7.000000 -33.971272
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.556744 -7.000000 -33.831230
      vertex -29.342590 -7.000000 -28.491980
      vertex -29.077410 -7.000000 -28.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.786324 -7.000000 -34.700855
      vertex -29.893181 -7.000000 -34.419098
      vertex -25.000000 -7.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.849329 -7.000000 -33.759113
      vertex -29.600065 -7.000000 -28.428518
      vertex -29.342590 -7.000000 -28.491980
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -30.849329 -7.000000 -33.759113
      vertex -29.342590 -7.000000 -28.491980
      vertex -30.556744 -7.000000 -33.831230
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.750000 -7.000000 -35.000000
      vertex -29.786324 -7.000000 -34.700855
      vertex -25.000000 -7.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.150671 -7.000000 -33.759113
      vertex -29.834871 -7.000000 -28.305283
      vertex -29.600065 -7.000000 -28.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.150671 -7.000000 -33.759113
      vertex -29.600065 -7.000000 -28.428518
      vertex -30.849329 -7.000000 -33.759113
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.786324 -7.000000 -35.299145
      vertex -29.750000 -7.000000 -35.000000
      vertex -25.000000 -7.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.443256 -7.000000 -33.831230
      vertex -30.184002 -7.000000 -27.911196
      vertex -30.033361 -7.000000 -28.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.443256 -7.000000 -33.831230
      vertex -30.033361 -7.000000 -28.129435
      vertex -29.834871 -7.000000 -28.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.443256 -7.000000 -33.831230
      vertex -29.834871 -7.000000 -28.305283
      vertex -31.150671 -7.000000 -33.759113
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.893181 -7.000000 -35.580902
      vertex -29.786324 -7.000000 -35.299145
      vertex -25.000000 -7.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.710081 -7.000000 -33.971272
      vertex -30.184002 -7.000000 -27.911196
      vertex -31.443256 -7.000000 -33.831230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.710081 -7.000000 -33.971272
      vertex -30.278036 -7.000000 -27.663248
      vertex -30.184002 -7.000000 -27.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.064362 -7.000000 -35.828903
      vertex -29.893181 -7.000000 -35.580902
      vertex -25.000000 -7.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.935638 -7.000000 -34.171097
      vertex -30.309999 -7.000000 -27.400000
      vertex -30.278036 -7.000000 -27.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.935638 -7.000000 -34.171097
      vertex -30.278036 -7.000000 -27.663248
      vertex -31.710081 -7.000000 -33.971272
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.289919 -7.000000 -36.028728
      vertex -30.064362 -7.000000 -35.828903
      vertex -25.000000 -7.000000 -33.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -30.289919 -7.000000 -36.028728
      vertex -25.000000 -7.000000 -33.000000
      vertex 0.000000 -7.000000 -36.849972
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -32.106819 -7.000000 -34.419098
      vertex -30.309999 -7.000000 -27.400000
      vertex -31.935638 -7.000000 -34.171097
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -30.556744 -7.000000 -36.168770
      vertex -30.289919 -7.000000 -36.028728
      vertex 0.000000 -7.000000 -36.849972
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -30.849329 -7.000000 -36.240887
      vertex -30.556744 -7.000000 -36.168770
      vertex 0.000000 -7.000000 -36.849972
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -31.150671 -7.000000 -36.240887
      vertex -30.849329 -7.000000 -36.240887
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -31.443256 -7.000000 -36.168770
      vertex -31.150671 -7.000000 -36.240887
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -31.710081 -7.000000 -36.028728
      vertex -31.443256 -7.000000 -36.168770
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -31.935638 -7.000000 -35.828903
      vertex -31.710081 -7.000000 -36.028728
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -32.106819 -7.000000 -35.580902
      vertex -31.935638 -7.000000 -35.828903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -32.213676 -7.000000 -35.299145
      vertex -32.106819 -7.000000 -35.580902
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -32.250000 -7.000000 -35.000000
      vertex -32.213676 -7.000000 -35.299145
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -32.213676 -7.000000 -34.700855
      vertex -32.250000 -7.000000 -35.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -32.106819 -7.000000 -34.419098
      vertex -32.213676 -7.000000 -34.700855
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -30.309999 -7.000000 -27.400000
      vertex -32.106819 -7.000000 -34.419098
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -30.278036 -7.000000 -27.136753
      vertex -30.309999 -7.000000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -30.849329 -7.000000 -36.240887
      vertex 0.000000 -7.000000 -36.849972
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -7.000000 -36.849998
      vertex -34.250000 -7.000000 26.030001
      vertex -30.278036 -7.000000 -27.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -30.278036 -7.000000 -27.136753
      vertex -34.250000 -7.000000 26.030001
      vertex -30.184002 -7.000000 -26.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -30.184002 -7.000000 -26.888805
      vertex -34.250000 -7.000000 26.030001
      vertex -25.000000 -7.000000 -11.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -25.000000 -7.000000 -11.000000
      vertex -34.250000 -7.000000 26.030001
      vertex -25.000000 -7.000000 3.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -7.000000 -36.849998
      vertex 0.000000 -7.000000 -36.849972
      vertex 29.849329 -7.000000 -36.240887
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 -33.000000
      vertex 25.000000 -7.000000 -33.000000
      vertex 0.000000 -7.000000 -36.849972
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -34.250000 -5.000000 26.030001
      vertex -25.000000 -5.000000 26.030001
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -34.250000 -7.000000 26.030001
      vertex -34.250000 -5.000000 26.030001
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -32.460079 -5.000000 27.971270
      vertex -34.250000 -5.000000 26.030001
      vertex -32.685638 -5.000000 28.171097
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -32.856819 -5.000000 28.419096
      vertex -32.685638 -5.000000 28.171097
      vertex -34.250000 -5.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -32.193256 -5.000000 27.831230
      vertex -34.250000 -5.000000 26.030001
      vertex -32.460079 -5.000000 27.971270
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -32.963676 -5.000000 28.700855
      vertex -32.856819 -5.000000 28.419096
      vertex -34.250000 -5.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.900671 -5.000000 27.759113
      vertex -34.250000 -5.000000 26.030001
      vertex -32.193256 -5.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -33.000000 -5.000000 29.000000
      vertex -32.963676 -5.000000 28.700855
      vertex -34.250000 -5.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.599329 -5.000000 27.759113
      vertex -34.250000 -5.000000 26.030001
      vertex -31.900671 -5.000000 27.759113
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.306744 -5.000000 27.831230
      vertex -34.250000 -5.000000 26.030001
      vertex -31.599329 -5.000000 27.759113
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -5.000000 31.280001
      vertex -32.963676 -5.000000 29.299145
      vertex -33.000000 -5.000000 29.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -5.000000 31.280001
      vertex -32.856819 -5.000000 29.580904
      vertex -32.963676 -5.000000 29.299145
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -34.250000 -5.000000 31.280001
      vertex -33.000000 -5.000000 29.000000
      vertex -34.250000 -5.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -32.685638 -5.000000 29.828903
      vertex -32.856819 -5.000000 29.580904
      vertex -34.250000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -32.460079 -5.000000 30.028730
      vertex -32.685638 -5.000000 29.828903
      vertex -34.250000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -32.193256 -5.000000 30.168770
      vertex -32.460079 -5.000000 30.028730
      vertex -34.250000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.900671 -5.000000 30.240887
      vertex -32.193256 -5.000000 30.168770
      vertex -34.250000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.599329 -5.000000 30.240887
      vertex -31.900671 -5.000000 30.240887
      vertex -34.250000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 26.030001
      vertex -30.536324 -5.000000 28.700855
      vertex -30.500000 -5.000000 29.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 26.030001
      vertex -30.643181 -5.000000 28.419096
      vertex -30.536324 -5.000000 28.700855
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 26.030001
      vertex -30.814362 -5.000000 28.171097
      vertex -30.643181 -5.000000 28.419096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 26.030001
      vertex -31.039919 -5.000000 27.971270
      vertex -30.814362 -5.000000 28.171097
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 26.030001
      vertex -31.306744 -5.000000 27.831230
      vertex -31.039919 -5.000000 27.971270
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 26.030001
      vertex -34.250000 -5.000000 26.030001
      vertex -31.306744 -5.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 31.280001
      vertex -31.306744 -5.000000 30.168770
      vertex -31.599329 -5.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 31.280001
      vertex -31.039919 -5.000000 30.028730
      vertex -31.306744 -5.000000 30.168770
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 31.280001
      vertex -30.814362 -5.000000 29.828903
      vertex -31.039919 -5.000000 30.028730
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 31.280001
      vertex -30.643181 -5.000000 29.580904
      vertex -30.814362 -5.000000 29.828903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 31.280001
      vertex -30.536324 -5.000000 29.299145
      vertex -30.643181 -5.000000 29.580904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 31.280001
      vertex -30.500000 -5.000000 29.000000
      vertex -30.536324 -5.000000 29.299145
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 31.280001
      vertex -25.000000 -5.000000 26.030001
      vertex -30.500000 -5.000000 29.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -25.000000 -5.000000 31.280001
      vertex -31.599329 -5.000000 30.240887
      vertex -34.250000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -34.250000 -5.000000 31.280001
      vertex -34.250000 -8.000000 31.280001
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -34.250000 -5.000000 31.280001
      vertex -25.000000 -8.000000 31.280001
      vertex -25.000000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 1.000000 0.000000 -0.000000
    outer loop
      vertex -25.000000 -7.000000 26.030001
      vertex -25.000000 -5.000000 31.280001
      vertex -25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 26.030001
      vertex -25.000000 -8.000000 31.280001
      vertex -25.000000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 1.000000 0.000000 -0.000000
    outer loop
      vertex -25.000000 -5.000000 26.030001
      vertex -25.000000 -5.000000 31.280001
      vertex -25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 3.000000
      vertex -25.000000 -8.000000 26.030001
      vertex -25.000000 -9.000000 26.030001
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -25.000000 -8.000000 26.030001
      vertex -25.000000 -9.000000 3.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 -0.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -25.000000 -7.000000 26.030001
      vertex -25.000000 -8.000000 26.030001
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120539
    outer loop
      vertex -30.536324 -5.000000 29.299145
      vertex -30.500000 -5.000000 29.000000
      vertex -30.500000 -8.000000 29.000000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 -0.120539
    outer loop
      vertex -30.536324 -5.000000 29.299145
      vertex -30.500000 -8.000000 29.000000
      vertex -30.536324 -8.000000 29.299145
    endloop
  endfacet
  facet normal -0.935016 -0.000000 -0.354605
    outer loop
      vertex -30.643181 -5.000000 29.580904
      vertex -30.536324 -8.000000 29.299145
      vertex -30.643181 -8.000000 29.580904
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex -30.643181 -5.000000 29.580904
      vertex -30.536324 -5.000000 29.299145
      vertex -30.536324 -8.000000 29.299145
    endloop
  endfacet
  facet normal -0.822985 -0.000000 -0.568063
    outer loop
      vertex -30.814362 -5.000000 29.828903
      vertex -30.643181 -8.000000 29.580904
      vertex -30.814362 -8.000000 29.828903
    endloop
  endfacet
  facet normal -0.822985 0.000000 -0.568063
    outer loop
      vertex -30.814362 -5.000000 29.828903
      vertex -30.643181 -5.000000 29.580904
      vertex -30.643181 -8.000000 29.580904
    endloop
  endfacet
  facet normal -0.663124 -0.000000 -0.748509
    outer loop
      vertex -31.039919 -5.000000 30.028730
      vertex -30.814362 -8.000000 29.828903
      vertex -31.039919 -8.000000 30.028730
    endloop
  endfacet
  facet normal -0.663124 0.000000 -0.748509
    outer loop
      vertex -31.039919 -5.000000 30.028730
      vertex -30.814362 -5.000000 29.828903
      vertex -30.814362 -8.000000 29.828903
    endloop
  endfacet
  facet normal -0.239319 -0.000000 -0.970941
    outer loop
      vertex -31.306744 -5.000000 30.168770
      vertex -31.306744 -8.000000 30.168770
      vertex -31.599329 -8.000000 30.240887
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex -31.306744 -5.000000 30.168770
      vertex -31.039919 -8.000000 30.028730
      vertex -31.306744 -8.000000 30.168770
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex -31.306744 -5.000000 30.168770
      vertex -31.039919 -5.000000 30.028730
      vertex -31.039919 -8.000000 30.028730
    endloop
  endfacet
  facet normal -0.239319 -0.000000 -0.970941
    outer loop
      vertex -31.599329 -5.000000 30.240887
      vertex -31.306744 -5.000000 30.168770
      vertex -31.599329 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.900671 -5.000000 30.240887
      vertex -31.599329 -8.000000 30.240887
      vertex -31.900671 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.900671 -5.000000 30.240887
      vertex -31.599329 -5.000000 30.240887
      vertex -31.599329 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.239319 0.000000 -0.970941
    outer loop
      vertex -32.193256 -5.000000 30.168770
      vertex -31.900671 -8.000000 30.240887
      vertex -32.193256 -8.000000 30.168770
    endloop
  endfacet
  facet normal 0.239319 -0.000000 -0.970941
    outer loop
      vertex -32.193256 -5.000000 30.168770
      vertex -31.900671 -5.000000 30.240887
      vertex -31.900671 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.464723 0.000000 -0.885456
    outer loop
      vertex -32.460079 -5.000000 30.028730
      vertex -32.193256 -8.000000 30.168770
      vertex -32.460079 -8.000000 30.028730
    endloop
  endfacet
  facet normal 0.464723 -0.000000 -0.885456
    outer loop
      vertex -32.460079 -5.000000 30.028730
      vertex -32.193256 -5.000000 30.168770
      vertex -32.193256 -8.000000 30.168770
    endloop
  endfacet
  facet normal 0.822985 0.000000 -0.568063
    outer loop
      vertex -32.685638 -5.000000 29.828903
      vertex -32.685638 -8.000000 29.828903
      vertex -32.856819 -8.000000 29.580904
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex -32.685638 -5.000000 29.828903
      vertex -32.460079 -8.000000 30.028730
      vertex -32.685638 -8.000000 29.828903
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex -32.685638 -5.000000 29.828903
      vertex -32.460079 -5.000000 30.028730
      vertex -32.460079 -8.000000 30.028730
    endloop
  endfacet
  facet normal 0.822985 0.000000 -0.568063
    outer loop
      vertex -32.856819 -5.000000 29.580904
      vertex -32.685638 -5.000000 29.828903
      vertex -32.856819 -8.000000 29.580904
    endloop
  endfacet
  facet normal 0.935016 -0.000000 -0.354605
    outer loop
      vertex -32.963676 -5.000000 29.299145
      vertex -32.856819 -5.000000 29.580904
      vertex -32.856819 -8.000000 29.580904
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex -32.963676 -5.000000 29.299145
      vertex -32.856819 -8.000000 29.580904
      vertex -32.963676 -8.000000 29.299145
    endloop
  endfacet
  facet normal 0.992709 -0.000000 -0.120539
    outer loop
      vertex -33.000000 -5.000000 29.000000
      vertex -32.963676 -5.000000 29.299145
      vertex -32.963676 -8.000000 29.299145
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120539
    outer loop
      vertex -33.000000 -5.000000 29.000000
      vertex -32.963676 -8.000000 29.299145
      vertex -33.000000 -8.000000 29.000000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex -32.963676 -5.000000 28.700855
      vertex -33.000000 -5.000000 29.000000
      vertex -33.000000 -8.000000 29.000000
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex -32.963676 -5.000000 28.700855
      vertex -32.963676 -8.000000 28.700855
      vertex -32.856819 -8.000000 28.419096
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex -32.963676 -5.000000 28.700855
      vertex -33.000000 -8.000000 29.000000
      vertex -32.963676 -8.000000 28.700855
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex -32.856819 -5.000000 28.419096
      vertex -32.963676 -5.000000 28.700855
      vertex -32.856819 -8.000000 28.419096
    endloop
  endfacet
  facet normal 0.822985 0.000000 0.568063
    outer loop
      vertex -32.856819 -5.000000 28.419096
      vertex -32.856819 -8.000000 28.419096
      vertex -32.685638 -8.000000 28.171097
    endloop
  endfacet
  facet normal 0.822985 0.000000 0.568063
    outer loop
      vertex -32.685638 -5.000000 28.171097
      vertex -32.856819 -5.000000 28.419096
      vertex -32.685638 -8.000000 28.171097
    endloop
  endfacet
  facet normal 0.663121 0.000000 0.748512
    outer loop
      vertex -32.685638 -5.000000 28.171097
      vertex -32.685638 -8.000000 28.171097
      vertex -32.460079 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.663121 0.000000 0.748512
    outer loop
      vertex -32.460079 -5.000000 27.971270
      vertex -32.685638 -5.000000 28.171097
      vertex -32.460079 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.464723 0.000000 0.885456
    outer loop
      vertex -32.193256 -5.000000 27.831230
      vertex -32.460079 -5.000000 27.971270
      vertex -32.460079 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.464723 0.000000 0.885456
    outer loop
      vertex -32.193256 -5.000000 27.831230
      vertex -32.460079 -8.000000 27.971270
      vertex -32.193256 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex -31.900671 -5.000000 27.759113
      vertex -32.193256 -8.000000 27.831230
      vertex -31.900671 -8.000000 27.759113
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex -31.900671 -5.000000 27.759113
      vertex -32.193256 -5.000000 27.831230
      vertex -32.193256 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -31.599329 -5.000000 27.759113
      vertex -31.900671 -5.000000 27.759113
      vertex -31.900671 -8.000000 27.759113
    endloop
  endfacet
  facet normal -0.239319 0.000000 0.970941
    outer loop
      vertex -31.599329 -5.000000 27.759113
      vertex -31.599329 -8.000000 27.759113
      vertex -31.306744 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -31.599329 -5.000000 27.759113
      vertex -31.900671 -8.000000 27.759113
      vertex -31.599329 -8.000000 27.759113
    endloop
  endfacet
  facet normal -0.239319 0.000000 0.970941
    outer loop
      vertex -31.306744 -5.000000 27.831230
      vertex -31.599329 -5.000000 27.759113
      vertex -31.306744 -8.000000 27.831230
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex -31.039919 -5.000000 27.971270
      vertex -31.306744 -8.000000 27.831230
      vertex -31.039919 -8.000000 27.971270
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex -31.039919 -5.000000 27.971270
      vertex -31.306744 -5.000000 27.831230
      vertex -31.306744 -8.000000 27.831230
    endloop
  endfacet
  facet normal -0.663124 0.000000 0.748509
    outer loop
      vertex -30.814362 -5.000000 28.171097
      vertex -31.039919 -8.000000 27.971270
      vertex -30.814362 -8.000000 28.171097
    endloop
  endfacet
  facet normal -0.663124 -0.000000 0.748509
    outer loop
      vertex -30.814362 -5.000000 28.171097
      vertex -31.039919 -5.000000 27.971270
      vertex -31.039919 -8.000000 27.971270
    endloop
  endfacet
  facet normal -0.822985 0.000000 0.568063
    outer loop
      vertex -30.643181 -5.000000 28.419096
      vertex -30.814362 -8.000000 28.171097
      vertex -30.643181 -8.000000 28.419096
    endloop
  endfacet
  facet normal -0.822985 -0.000000 0.568063
    outer loop
      vertex -30.643181 -5.000000 28.419096
      vertex -30.814362 -5.000000 28.171097
      vertex -30.814362 -8.000000 28.171097
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex -30.536324 -5.000000 28.700855
      vertex -30.643181 -8.000000 28.419096
      vertex -30.536324 -8.000000 28.700855
    endloop
  endfacet
  facet normal -0.935016 -0.000000 0.354605
    outer loop
      vertex -30.536324 -5.000000 28.700855
      vertex -30.643181 -5.000000 28.419096
      vertex -30.643181 -8.000000 28.419096
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120539
    outer loop
      vertex -30.500000 -5.000000 29.000000
      vertex -30.536324 -8.000000 28.700855
      vertex -30.500000 -8.000000 29.000000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 0.120539
    outer loop
      vertex -30.500000 -5.000000 29.000000
      vertex -30.536324 -5.000000 28.700855
      vertex -30.536324 -8.000000 28.700855
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex 25.000000 -5.000000 31.280001
      vertex 25.000000 -7.000000 26.030001
      vertex 25.000000 -8.000000 31.280001
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 31.280001
      vertex 25.000000 -7.000000 26.030001
      vertex 25.000000 -8.000000 26.030001
    endloop
  endfacet
  facet normal -1.000000 0.000000 -0.000000
    outer loop
      vertex 25.000000 -5.000000 31.280001
      vertex 25.000000 -5.000000 26.030001
      vertex 25.000000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 26.030001
      vertex 25.000000 -9.000000 3.000000
      vertex 25.000000 -9.000000 26.030001
    endloop
  endfacet
  facet normal -1.000000 0.000000 -0.000000
    outer loop
      vertex 25.000000 -8.000000 26.030001
      vertex 25.000000 -7.000000 3.000000
      vertex 25.000000 -9.000000 3.000000
    endloop
  endfacet
  facet normal -1.000000 -0.000000 -0.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 25.000000 -7.000000 3.000000
      vertex 25.000000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.000000 -9.000000 26.030001
      vertex 34.250000 -9.000000 26.030001
      vertex 34.250000 -8.000000 26.030001
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 25.000000 -8.000000 26.030001
      vertex 25.000000 -9.000000 26.030001
      vertex 34.250000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 1.000000 -0.000000 0.000000
    outer loop
      vertex 34.250000 -8.000000 31.280001
      vertex 34.250000 -7.000000 26.030001
      vertex 34.250000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 34.250000 -7.000000 26.030001
      vertex 34.250000 -5.000000 26.030001
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 34.250000 -8.000000 31.280001
      vertex 34.250000 -8.000000 26.030001
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 1.000000 -0.000000 0.000000
    outer loop
      vertex 34.250000 -8.000000 26.030001
      vertex 34.250000 -7.000000 -36.849998
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 1.000000 -0.000000 0.000000
    outer loop
      vertex 34.250000 -9.000000 26.030001
      vertex 34.250000 -9.000000 -36.849998
      vertex 34.250000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 34.250000 -8.000000 26.030001
      vertex 34.250000 -9.000000 -36.849998
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000001 0.000000 -1.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 0.000000 -7.000000 -36.849972
      vertex 34.250000 -7.000000 -36.849998
    endloop
  endfacet
  facet normal -0.000001 -0.000011 -1.000000
    outer loop
      vertex 34.250000 -9.000000 -36.849998
      vertex 0.000000 -9.000000 -36.849949
      vertex 0.000000 -7.000000 -36.849972
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120539
    outer loop
      vertex -29.786324 -7.000000 -34.700855
      vertex -29.750000 -7.000000 -35.000000
      vertex -29.750000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 -0.120539
    outer loop
      vertex -29.786324 -7.000000 -34.700855
      vertex -29.750000 -9.000000 -35.000000
      vertex -29.786324 -9.000000 -34.700855
    endloop
  endfacet
  facet normal -0.935015 -0.000000 -0.354607
    outer loop
      vertex -29.893181 -7.000000 -34.419098
      vertex -29.786324 -9.000000 -34.700855
      vertex -29.893181 -9.000000 -34.419098
    endloop
  endfacet
  facet normal -0.935015 -0.000000 -0.354607
    outer loop
      vertex -29.893181 -7.000000 -34.419098
      vertex -29.786324 -7.000000 -34.700855
      vertex -29.786324 -9.000000 -34.700855
    endloop
  endfacet
  facet normal -0.822987 -0.000000 -0.568060
    outer loop
      vertex -30.064362 -7.000000 -34.171097
      vertex -29.893181 -9.000000 -34.419098
      vertex -30.064362 -9.000000 -34.171097
    endloop
  endfacet
  facet normal -0.822987 0.000000 -0.568060
    outer loop
      vertex -30.064362 -7.000000 -34.171097
      vertex -29.893181 -7.000000 -34.419098
      vertex -29.893181 -9.000000 -34.419098
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748513
    outer loop
      vertex -30.289919 -7.000000 -33.971272
      vertex -30.064362 -9.000000 -34.171097
      vertex -30.289919 -9.000000 -33.971272
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748513
    outer loop
      vertex -30.289919 -7.000000 -33.971272
      vertex -30.064362 -7.000000 -34.171097
      vertex -30.064362 -9.000000 -34.171097
    endloop
  endfacet
  facet normal -0.464726 -0.000000 -0.885455
    outer loop
      vertex -30.556744 -7.000000 -33.831230
      vertex -30.289919 -9.000000 -33.971272
      vertex -30.556744 -9.000000 -33.831230
    endloop
  endfacet
  facet normal -0.464726 -0.000000 -0.885455
    outer loop
      vertex -30.556744 -7.000000 -33.831230
      vertex -30.289919 -7.000000 -33.971272
      vertex -30.289919 -9.000000 -33.971272
    endloop
  endfacet
  facet normal -0.239319 -0.000000 -0.970941
    outer loop
      vertex -30.849329 -7.000000 -33.759113
      vertex -30.556744 -9.000000 -33.831230
      vertex -30.849329 -9.000000 -33.759113
    endloop
  endfacet
  facet normal -0.239319 0.000000 -0.970941
    outer loop
      vertex -30.849329 -7.000000 -33.759113
      vertex -30.556744 -7.000000 -33.831230
      vertex -30.556744 -9.000000 -33.831230
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.150671 -7.000000 -33.759113
      vertex -30.849329 -9.000000 -33.759113
      vertex -31.150671 -9.000000 -33.759113
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.150671 -7.000000 -33.759113
      vertex -30.849329 -7.000000 -33.759113
      vertex -30.849329 -9.000000 -33.759113
    endloop
  endfacet
  facet normal 0.239319 0.000000 -0.970941
    outer loop
      vertex -31.443256 -7.000000 -33.831230
      vertex -31.150671 -9.000000 -33.759113
      vertex -31.443256 -9.000000 -33.831230
    endloop
  endfacet
  facet normal 0.239319 -0.000000 -0.970941
    outer loop
      vertex -31.443256 -7.000000 -33.831230
      vertex -31.150671 -7.000000 -33.759113
      vertex -31.150671 -9.000000 -33.759113
    endloop
  endfacet
  facet normal 0.464726 0.000000 -0.885455
    outer loop
      vertex -31.710081 -7.000000 -33.971272
      vertex -31.443256 -9.000000 -33.831230
      vertex -31.710081 -9.000000 -33.971272
    endloop
  endfacet
  facet normal 0.464726 0.000000 -0.885455
    outer loop
      vertex -31.710081 -7.000000 -33.971272
      vertex -31.443256 -7.000000 -33.831230
      vertex -31.443256 -9.000000 -33.831230
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748513
    outer loop
      vertex -31.935638 -7.000000 -34.171097
      vertex -31.710081 -9.000000 -33.971272
      vertex -31.935638 -9.000000 -34.171097
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748513
    outer loop
      vertex -31.935638 -7.000000 -34.171097
      vertex -31.710081 -7.000000 -33.971272
      vertex -31.710081 -9.000000 -33.971272
    endloop
  endfacet
  facet normal 0.822987 -0.000000 -0.568060
    outer loop
      vertex -32.106819 -7.000000 -34.419098
      vertex -31.935638 -7.000000 -34.171097
      vertex -31.935638 -9.000000 -34.171097
    endloop
  endfacet
  facet normal 0.822987 0.000000 -0.568060
    outer loop
      vertex -32.106819 -7.000000 -34.419098
      vertex -31.935638 -9.000000 -34.171097
      vertex -32.106819 -9.000000 -34.419098
    endloop
  endfacet
  facet normal 0.935015 0.000000 -0.354607
    outer loop
      vertex -32.213676 -7.000000 -34.700855
      vertex -32.106819 -7.000000 -34.419098
      vertex -32.106819 -9.000000 -34.419098
    endloop
  endfacet
  facet normal 0.935015 0.000000 -0.354607
    outer loop
      vertex -32.213676 -7.000000 -34.700855
      vertex -32.106819 -9.000000 -34.419098
      vertex -32.213676 -9.000000 -34.700855
    endloop
  endfacet
  facet normal 0.992709 -0.000000 -0.120539
    outer loop
      vertex -32.250000 -7.000000 -35.000000
      vertex -32.213676 -7.000000 -34.700855
      vertex -32.213676 -9.000000 -34.700855
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120539
    outer loop
      vertex -32.250000 -7.000000 -35.000000
      vertex -32.213676 -9.000000 -34.700855
      vertex -32.250000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex -32.213676 -7.000000 -35.299145
      vertex -32.250000 -7.000000 -35.000000
      vertex -32.250000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex -32.213676 -7.000000 -35.299145
      vertex -32.250000 -9.000000 -35.000000
      vertex -32.213676 -9.000000 -35.299145
    endloop
  endfacet
  facet normal 0.935015 -0.000000 0.354607
    outer loop
      vertex -32.106819 -7.000000 -35.580902
      vertex -32.213676 -7.000000 -35.299145
      vertex -32.213676 -9.000000 -35.299145
    endloop
  endfacet
  facet normal 0.935015 0.000000 0.354607
    outer loop
      vertex -32.106819 -7.000000 -35.580902
      vertex -32.213676 -9.000000 -35.299145
      vertex -32.106819 -9.000000 -35.580902
    endloop
  endfacet
  facet normal 0.822987 0.000000 0.568060
    outer loop
      vertex -31.935638 -7.000000 -35.828903
      vertex -32.106819 -7.000000 -35.580902
      vertex -32.106819 -9.000000 -35.580902
    endloop
  endfacet
  facet normal 0.663121 0.000000 0.748513
    outer loop
      vertex -31.935638 -7.000000 -35.828903
      vertex -31.935638 -9.000000 -35.828903
      vertex -31.710081 -9.000000 -36.028728
    endloop
  endfacet
  facet normal 0.822987 0.000000 0.568060
    outer loop
      vertex -31.935638 -7.000000 -35.828903
      vertex -32.106819 -9.000000 -35.580902
      vertex -31.935638 -9.000000 -35.828903
    endloop
  endfacet
  facet normal 0.663121 0.000000 0.748513
    outer loop
      vertex -31.710081 -7.000000 -36.028728
      vertex -31.935638 -7.000000 -35.828903
      vertex -31.710081 -9.000000 -36.028728
    endloop
  endfacet
  facet normal 0.464726 -0.000000 0.885455
    outer loop
      vertex -31.443256 -7.000000 -36.168770
      vertex -31.710081 -7.000000 -36.028728
      vertex -31.710081 -9.000000 -36.028728
    endloop
  endfacet
  facet normal 0.464726 0.000000 0.885455
    outer loop
      vertex -31.443256 -7.000000 -36.168770
      vertex -31.710081 -9.000000 -36.028728
      vertex -31.443256 -9.000000 -36.168770
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex -31.150671 -7.000000 -36.240887
      vertex -31.443256 -9.000000 -36.168770
      vertex -31.150671 -9.000000 -36.240887
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex -31.150671 -7.000000 -36.240887
      vertex -31.443256 -7.000000 -36.168770
      vertex -31.443256 -9.000000 -36.168770
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -30.849329 -7.000000 -36.240887
      vertex -31.150671 -7.000000 -36.240887
      vertex -31.150671 -9.000000 -36.240887
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -30.849329 -7.000000 -36.240887
      vertex -31.150671 -9.000000 -36.240887
      vertex -30.849329 -9.000000 -36.240887
    endloop
  endfacet
  facet normal -0.464726 0.000000 0.885455
    outer loop
      vertex -30.556744 -7.000000 -36.168770
      vertex -30.556744 -9.000000 -36.168770
      vertex -30.289919 -9.000000 -36.028728
    endloop
  endfacet
  facet normal -0.239319 0.000000 0.970941
    outer loop
      vertex -30.556744 -7.000000 -36.168770
      vertex -30.849329 -9.000000 -36.240887
      vertex -30.556744 -9.000000 -36.168770
    endloop
  endfacet
  facet normal -0.239319 -0.000000 0.970941
    outer loop
      vertex -30.556744 -7.000000 -36.168770
      vertex -30.849329 -7.000000 -36.240887
      vertex -30.849329 -9.000000 -36.240887
    endloop
  endfacet
  facet normal -0.464726 0.000000 0.885455
    outer loop
      vertex -30.289919 -7.000000 -36.028728
      vertex -30.556744 -7.000000 -36.168770
      vertex -30.289919 -9.000000 -36.028728
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748513
    outer loop
      vertex -30.064362 -7.000000 -35.828903
      vertex -30.289919 -9.000000 -36.028728
      vertex -30.064362 -9.000000 -35.828903
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748513
    outer loop
      vertex -30.064362 -7.000000 -35.828903
      vertex -30.289919 -7.000000 -36.028728
      vertex -30.289919 -9.000000 -36.028728
    endloop
  endfacet
  facet normal -0.935015 0.000000 0.354607
    outer loop
      vertex -29.893181 -7.000000 -35.580902
      vertex -29.893181 -9.000000 -35.580902
      vertex -29.786324 -9.000000 -35.299145
    endloop
  endfacet
  facet normal -0.822987 0.000000 0.568060
    outer loop
      vertex -29.893181 -7.000000 -35.580902
      vertex -30.064362 -9.000000 -35.828903
      vertex -29.893181 -9.000000 -35.580902
    endloop
  endfacet
  facet normal -0.822987 -0.000000 0.568060
    outer loop
      vertex -29.893181 -7.000000 -35.580902
      vertex -30.064362 -7.000000 -35.828903
      vertex -30.064362 -9.000000 -35.828903
    endloop
  endfacet
  facet normal -0.935015 0.000000 0.354607
    outer loop
      vertex -29.786324 -7.000000 -35.299145
      vertex -29.893181 -7.000000 -35.580902
      vertex -29.786324 -9.000000 -35.299145
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120539
    outer loop
      vertex -29.750000 -7.000000 -35.000000
      vertex -29.786324 -9.000000 -35.299145
      vertex -29.750000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 0.120539
    outer loop
      vertex -29.750000 -7.000000 -35.000000
      vertex -29.786324 -7.000000 -35.299145
      vertex -29.786324 -9.000000 -35.299145
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex -25.000000 -9.000000 -33.000000
      vertex -25.000000 -7.000000 -11.000000
      vertex -25.000000 -9.000000 -11.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 -0.000000
    outer loop
      vertex -25.000000 -7.000000 -33.000000
      vertex -25.000000 -7.000000 -11.000000
      vertex -25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex 25.000000 -7.000000 -11.000000
      vertex 25.000000 -9.000000 -33.000000
      vertex 25.000000 -9.000000 -11.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 -0.000000
    outer loop
      vertex 25.000000 -7.000000 -11.000000
      vertex 25.000000 -7.000000 -33.000000
      vertex 25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120539
    outer loop
      vertex 31.213676 -7.000000 -34.700855
      vertex 31.250000 -7.000000 -35.000000
      vertex 31.250000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 -0.120539
    outer loop
      vertex 31.213676 -7.000000 -34.700855
      vertex 31.250000 -9.000000 -35.000000
      vertex 31.213676 -9.000000 -34.700855
    endloop
  endfacet
  facet normal -0.935015 -0.000000 -0.354607
    outer loop
      vertex 31.106819 -7.000000 -34.419098
      vertex 31.213676 -9.000000 -34.700855
      vertex 31.106819 -9.000000 -34.419098
    endloop
  endfacet
  facet normal -0.935015 -0.000000 -0.354607
    outer loop
      vertex 31.106819 -7.000000 -34.419098
      vertex 31.213676 -7.000000 -34.700855
      vertex 31.213676 -9.000000 -34.700855
    endloop
  endfacet
  facet normal -0.822987 -0.000000 -0.568060
    outer loop
      vertex 30.935638 -7.000000 -34.171097
      vertex 31.106819 -9.000000 -34.419098
      vertex 30.935638 -9.000000 -34.171097
    endloop
  endfacet
  facet normal -0.822987 0.000000 -0.568060
    outer loop
      vertex 30.935638 -7.000000 -34.171097
      vertex 31.106819 -7.000000 -34.419098
      vertex 31.106819 -9.000000 -34.419098
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748513
    outer loop
      vertex 30.710081 -7.000000 -33.971272
      vertex 30.935638 -9.000000 -34.171097
      vertex 30.710081 -9.000000 -33.971272
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748513
    outer loop
      vertex 30.710081 -7.000000 -33.971272
      vertex 30.935638 -7.000000 -34.171097
      vertex 30.935638 -9.000000 -34.171097
    endloop
  endfacet
  facet normal -0.464726 -0.000000 -0.885455
    outer loop
      vertex 30.443256 -7.000000 -33.831230
      vertex 30.710081 -9.000000 -33.971272
      vertex 30.443256 -9.000000 -33.831230
    endloop
  endfacet
  facet normal -0.464726 -0.000000 -0.885455
    outer loop
      vertex 30.443256 -7.000000 -33.831230
      vertex 30.710081 -7.000000 -33.971272
      vertex 30.710081 -9.000000 -33.971272
    endloop
  endfacet
  facet normal -0.239319 -0.000000 -0.970941
    outer loop
      vertex 30.150671 -7.000000 -33.759113
      vertex 30.443256 -9.000000 -33.831230
      vertex 30.150671 -9.000000 -33.759113
    endloop
  endfacet
  facet normal -0.239319 0.000000 -0.970941
    outer loop
      vertex 30.150671 -7.000000 -33.759113
      vertex 30.443256 -7.000000 -33.831230
      vertex 30.443256 -9.000000 -33.831230
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.849329 -7.000000 -33.759113
      vertex 30.150671 -9.000000 -33.759113
      vertex 29.849329 -9.000000 -33.759113
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.849329 -7.000000 -33.759113
      vertex 30.150671 -7.000000 -33.759113
      vertex 30.150671 -9.000000 -33.759113
    endloop
  endfacet
  facet normal 0.239319 0.000000 -0.970941
    outer loop
      vertex 29.556744 -7.000000 -33.831230
      vertex 29.849329 -9.000000 -33.759113
      vertex 29.556744 -9.000000 -33.831230
    endloop
  endfacet
  facet normal 0.239319 -0.000000 -0.970941
    outer loop
      vertex 29.556744 -7.000000 -33.831230
      vertex 29.849329 -7.000000 -33.759113
      vertex 29.849329 -9.000000 -33.759113
    endloop
  endfacet
  facet normal 0.464726 0.000000 -0.885455
    outer loop
      vertex 29.289919 -7.000000 -33.971272
      vertex 29.556744 -9.000000 -33.831230
      vertex 29.289919 -9.000000 -33.971272
    endloop
  endfacet
  facet normal 0.464726 0.000000 -0.885455
    outer loop
      vertex 29.289919 -7.000000 -33.971272
      vertex 29.556744 -7.000000 -33.831230
      vertex 29.556744 -9.000000 -33.831230
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748513
    outer loop
      vertex 29.064362 -7.000000 -34.171097
      vertex 29.289919 -9.000000 -33.971272
      vertex 29.064362 -9.000000 -34.171097
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748513
    outer loop
      vertex 29.064362 -7.000000 -34.171097
      vertex 29.289919 -7.000000 -33.971272
      vertex 29.289919 -9.000000 -33.971272
    endloop
  endfacet
  facet normal 0.822987 -0.000000 -0.568060
    outer loop
      vertex 28.893181 -7.000000 -34.419098
      vertex 29.064362 -7.000000 -34.171097
      vertex 29.064362 -9.000000 -34.171097
    endloop
  endfacet
  facet normal 0.822987 0.000000 -0.568060
    outer loop
      vertex 28.893181 -7.000000 -34.419098
      vertex 29.064362 -9.000000 -34.171097
      vertex 28.893181 -9.000000 -34.419098
    endloop
  endfacet
  facet normal 0.935015 0.000000 -0.354607
    outer loop
      vertex 28.786324 -7.000000 -34.700855
      vertex 28.893181 -7.000000 -34.419098
      vertex 28.893181 -9.000000 -34.419098
    endloop
  endfacet
  facet normal 0.935015 0.000000 -0.354607
    outer loop
      vertex 28.786324 -7.000000 -34.700855
      vertex 28.893181 -9.000000 -34.419098
      vertex 28.786324 -9.000000 -34.700855
    endloop
  endfacet
  facet normal 0.992709 -0.000000 -0.120539
    outer loop
      vertex 28.750000 -7.000000 -35.000000
      vertex 28.786324 -7.000000 -34.700855
      vertex 28.786324 -9.000000 -34.700855
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120539
    outer loop
      vertex 28.750000 -7.000000 -35.000000
      vertex 28.786324 -9.000000 -34.700855
      vertex 28.750000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex 28.786324 -7.000000 -35.299145
      vertex 28.750000 -7.000000 -35.000000
      vertex 28.750000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex 28.786324 -7.000000 -35.299145
      vertex 28.750000 -9.000000 -35.000000
      vertex 28.786324 -9.000000 -35.299145
    endloop
  endfacet
  facet normal 0.935015 -0.000000 0.354607
    outer loop
      vertex 28.893181 -7.000000 -35.580902
      vertex 28.786324 -7.000000 -35.299145
      vertex 28.786324 -9.000000 -35.299145
    endloop
  endfacet
  facet normal 0.935015 0.000000 0.354607
    outer loop
      vertex 28.893181 -7.000000 -35.580902
      vertex 28.786324 -9.000000 -35.299145
      vertex 28.893181 -9.000000 -35.580902
    endloop
  endfacet
  facet normal 0.822987 0.000000 0.568060
    outer loop
      vertex 29.064362 -7.000000 -35.828903
      vertex 28.893181 -7.000000 -35.580902
      vertex 28.893181 -9.000000 -35.580902
    endloop
  endfacet
  facet normal 0.663121 0.000000 0.748513
    outer loop
      vertex 29.064362 -7.000000 -35.828903
      vertex 29.064362 -9.000000 -35.828903
      vertex 29.289919 -9.000000 -36.028728
    endloop
  endfacet
  facet normal 0.822987 0.000000 0.568060
    outer loop
      vertex 29.064362 -7.000000 -35.828903
      vertex 28.893181 -9.000000 -35.580902
      vertex 29.064362 -9.000000 -35.828903
    endloop
  endfacet
  facet normal 0.663121 0.000000 0.748513
    outer loop
      vertex 29.289919 -7.000000 -36.028728
      vertex 29.064362 -7.000000 -35.828903
      vertex 29.289919 -9.000000 -36.028728
    endloop
  endfacet
  facet normal 0.464726 -0.000000 0.885455
    outer loop
      vertex 29.556744 -7.000000 -36.168770
      vertex 29.289919 -7.000000 -36.028728
      vertex 29.289919 -9.000000 -36.028728
    endloop
  endfacet
  facet normal 0.464726 0.000000 0.885455
    outer loop
      vertex 29.556744 -7.000000 -36.168770
      vertex 29.289919 -9.000000 -36.028728
      vertex 29.556744 -9.000000 -36.168770
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex 29.849329 -7.000000 -36.240887
      vertex 29.556744 -9.000000 -36.168770
      vertex 29.849329 -9.000000 -36.240887
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex 29.849329 -7.000000 -36.240887
      vertex 29.556744 -7.000000 -36.168770
      vertex 29.556744 -9.000000 -36.168770
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 30.150671 -7.000000 -36.240887
      vertex 29.849329 -7.000000 -36.240887
      vertex 29.849329 -9.000000 -36.240887
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 30.150671 -7.000000 -36.240887
      vertex 29.849329 -9.000000 -36.240887
      vertex 30.150671 -9.000000 -36.240887
    endloop
  endfacet
  facet normal -0.464726 0.000000 0.885455
    outer loop
      vertex 30.443256 -7.000000 -36.168770
      vertex 30.443256 -9.000000 -36.168770
      vertex 30.710081 -9.000000 -36.028728
    endloop
  endfacet
  facet normal -0.239319 0.000000 0.970941
    outer loop
      vertex 30.443256 -7.000000 -36.168770
      vertex 30.150671 -9.000000 -36.240887
      vertex 30.443256 -9.000000 -36.168770
    endloop
  endfacet
  facet normal -0.239319 -0.000000 0.970941
    outer loop
      vertex 30.443256 -7.000000 -36.168770
      vertex 30.150671 -7.000000 -36.240887
      vertex 30.150671 -9.000000 -36.240887
    endloop
  endfacet
  facet normal -0.464726 0.000000 0.885455
    outer loop
      vertex 30.710081 -7.000000 -36.028728
      vertex 30.443256 -7.000000 -36.168770
      vertex 30.710081 -9.000000 -36.028728
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748513
    outer loop
      vertex 30.935638 -7.000000 -35.828903
      vertex 30.710081 -9.000000 -36.028728
      vertex 30.935638 -9.000000 -35.828903
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748513
    outer loop
      vertex 30.935638 -7.000000 -35.828903
      vertex 30.710081 -7.000000 -36.028728
      vertex 30.710081 -9.000000 -36.028728
    endloop
  endfacet
  facet normal -0.935015 0.000000 0.354607
    outer loop
      vertex 31.106819 -7.000000 -35.580902
      vertex 31.106819 -9.000000 -35.580902
      vertex 31.213676 -9.000000 -35.299145
    endloop
  endfacet
  facet normal -0.822987 0.000000 0.568060
    outer loop
      vertex 31.106819 -7.000000 -35.580902
      vertex 30.935638 -9.000000 -35.828903
      vertex 31.106819 -9.000000 -35.580902
    endloop
  endfacet
  facet normal -0.822987 -0.000000 0.568060
    outer loop
      vertex 31.106819 -7.000000 -35.580902
      vertex 30.935638 -7.000000 -35.828903
      vertex 30.935638 -9.000000 -35.828903
    endloop
  endfacet
  facet normal -0.935015 0.000000 0.354607
    outer loop
      vertex 31.213676 -7.000000 -35.299145
      vertex 31.106819 -7.000000 -35.580902
      vertex 31.213676 -9.000000 -35.299145
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120539
    outer loop
      vertex 31.250000 -7.000000 -35.000000
      vertex 31.213676 -9.000000 -35.299145
      vertex 31.250000 -9.000000 -35.000000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 0.120539
    outer loop
      vertex 31.250000 -7.000000 -35.000000
      vertex 31.213676 -7.000000 -35.299145
      vertex 31.213676 -9.000000 -35.299145
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.000000 -5.000000 26.030001
      vertex 34.250000 -5.000000 26.030001
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.000000 -7.000000 26.030001
      vertex 25.000000 -5.000000 26.030001
      vertex 34.250000 -7.000000 26.030001
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120534
    outer loop
      vertex 28.110001 -3.500000 23.400000
      vertex 28.110001 -7.000000 23.400000
      vertex 28.141964 -3.500000 23.663248
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex 28.141964 -3.500000 23.663248
      vertex 28.141964 -7.000000 23.663248
      vertex 28.235998 -3.500000 23.911196
    endloop
  endfacet
  facet normal -0.992709 -0.000000 0.120534
    outer loop
      vertex 28.110001 -7.000000 23.400000
      vertex 28.141964 -7.000000 23.663248
      vertex 28.141964 -3.500000 23.663248
    endloop
  endfacet
  facet normal -0.822982 0.000000 0.568068
    outer loop
      vertex 28.235998 -3.500000 23.911196
      vertex 28.235998 -7.000000 23.911196
      vertex 28.386639 -3.500000 24.129435
    endloop
  endfacet
  facet normal -0.935016 -0.000000 0.354605
    outer loop
      vertex 28.141964 -7.000000 23.663248
      vertex 28.235998 -7.000000 23.911196
      vertex 28.235998 -3.500000 23.911196
    endloop
  endfacet
  facet normal -0.663125 0.000000 0.748509
    outer loop
      vertex 28.386639 -3.500000 24.129435
      vertex 28.386639 -7.000000 24.129435
      vertex 28.585129 -3.500000 24.305283
    endloop
  endfacet
  facet normal -0.822982 -0.000000 0.568068
    outer loop
      vertex 28.235998 -7.000000 23.911196
      vertex 28.386639 -7.000000 24.129435
      vertex 28.386639 -3.500000 24.129435
    endloop
  endfacet
  facet normal -0.464723 0.000000 0.885456
    outer loop
      vertex 28.585129 -3.500000 24.305283
      vertex 28.585129 -7.000000 24.305283
      vertex 28.819935 -3.500000 24.428518
    endloop
  endfacet
  facet normal -0.663125 -0.000000 0.748509
    outer loop
      vertex 28.386639 -7.000000 24.129435
      vertex 28.585129 -7.000000 24.305283
      vertex 28.585129 -3.500000 24.305283
    endloop
  endfacet
  facet normal -0.239314 0.000000 0.970942
    outer loop
      vertex 28.819935 -3.500000 24.428518
      vertex 28.819935 -7.000000 24.428518
      vertex 29.077410 -3.500000 24.491980
    endloop
  endfacet
  facet normal -0.464723 -0.000000 0.885456
    outer loop
      vertex 28.585129 -7.000000 24.305283
      vertex 28.819935 -7.000000 24.428518
      vertex 28.819935 -3.500000 24.428518
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 29.077410 -3.500000 24.491980
      vertex 29.077410 -7.000000 24.491980
      vertex 29.342590 -3.500000 24.491980
    endloop
  endfacet
  facet normal -0.239314 -0.000000 0.970942
    outer loop
      vertex 28.819935 -7.000000 24.428518
      vertex 29.077410 -7.000000 24.491980
      vertex 29.077410 -3.500000 24.491980
    endloop
  endfacet
  facet normal 0.239314 0.000000 0.970942
    outer loop
      vertex 29.342590 -3.500000 24.491980
      vertex 29.342590 -7.000000 24.491980
      vertex 29.600065 -3.500000 24.428518
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.077410 -7.000000 24.491980
      vertex 29.342590 -7.000000 24.491980
      vertex 29.342590 -3.500000 24.491980
    endloop
  endfacet
  facet normal 0.464723 0.000000 0.885456
    outer loop
      vertex 29.600065 -3.500000 24.428518
      vertex 29.600065 -7.000000 24.428518
      vertex 29.834871 -3.500000 24.305283
    endloop
  endfacet
  facet normal 0.239314 0.000000 0.970942
    outer loop
      vertex 29.342590 -7.000000 24.491980
      vertex 29.600065 -7.000000 24.428518
      vertex 29.600065 -3.500000 24.428518
    endloop
  endfacet
  facet normal 0.663125 0.000000 0.748509
    outer loop
      vertex 29.834871 -3.500000 24.305283
      vertex 29.834871 -7.000000 24.305283
      vertex 30.033361 -3.500000 24.129435
    endloop
  endfacet
  facet normal 0.464723 0.000000 0.885456
    outer loop
      vertex 29.600065 -7.000000 24.428518
      vertex 29.834871 -7.000000 24.305283
      vertex 29.834871 -3.500000 24.305283
    endloop
  endfacet
  facet normal 0.822982 0.000000 0.568068
    outer loop
      vertex 30.033361 -3.500000 24.129435
      vertex 30.033361 -7.000000 24.129435
      vertex 30.184002 -3.500000 23.911196
    endloop
  endfacet
  facet normal 0.663125 0.000000 0.748509
    outer loop
      vertex 29.834871 -7.000000 24.305283
      vertex 30.033361 -7.000000 24.129435
      vertex 30.033361 -3.500000 24.129435
    endloop
  endfacet
  facet normal 0.822982 0.000000 0.568068
    outer loop
      vertex 30.033361 -7.000000 24.129435
      vertex 30.184002 -7.000000 23.911196
      vertex 30.184002 -3.500000 23.911196
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 30.184002 -3.500000 23.911196
      vertex 30.184002 -7.000000 23.911196
      vertex 30.278036 -3.500000 23.663248
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 30.184002 -7.000000 23.911196
      vertex 30.278036 -7.000000 23.663248
      vertex 30.278036 -3.500000 23.663248
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120534
    outer loop
      vertex 30.278036 -3.500000 23.663248
      vertex 30.278036 -7.000000 23.663248
      vertex 30.309999 -3.500000 23.400000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120534
    outer loop
      vertex 30.278036 -7.000000 23.663248
      vertex 30.309999 -7.000000 23.400000
      vertex 30.309999 -3.500000 23.400000
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120535
    outer loop
      vertex 30.309999 -3.500000 23.400000
      vertex 30.309999 -7.000000 23.400000
      vertex 30.278036 -3.500000 23.136753
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120535
    outer loop
      vertex 30.309999 -7.000000 23.400000
      vertex 30.278036 -7.000000 23.136753
      vertex 30.278036 -3.500000 23.136753
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex 30.278036 -7.000000 23.136753
      vertex 30.184002 -7.000000 22.888805
      vertex 30.278036 -3.500000 23.136753
    endloop
  endfacet
  facet normal 0.935016 -0.000000 -0.354605
    outer loop
      vertex 30.278036 -3.500000 23.136753
      vertex 30.184002 -7.000000 22.888805
      vertex 30.184002 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.822984 0.000000 -0.568064
    outer loop
      vertex 30.184002 -7.000000 22.888805
      vertex 30.033361 -7.000000 22.670565
      vertex 30.184002 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.822984 -0.000000 -0.568064
    outer loop
      vertex 30.184002 -3.500000 22.888805
      vertex 30.033361 -7.000000 22.670565
      vertex 30.033361 -3.500000 22.670565
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex 30.033361 -7.000000 22.670565
      vertex 29.834871 -7.000000 22.494719
      vertex 30.033361 -3.500000 22.670565
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex 30.033361 -3.500000 22.670565
      vertex 29.834871 -7.000000 22.494719
      vertex 29.834871 -3.500000 22.494719
    endloop
  endfacet
  facet normal 0.464723 0.000000 -0.885456
    outer loop
      vertex 29.834871 -7.000000 22.494719
      vertex 29.600065 -7.000000 22.371483
      vertex 29.834871 -3.500000 22.494719
    endloop
  endfacet
  facet normal 0.464723 -0.000000 -0.885456
    outer loop
      vertex 29.834871 -3.500000 22.494719
      vertex 29.600065 -7.000000 22.371483
      vertex 29.600065 -3.500000 22.371483
    endloop
  endfacet
  facet normal 0.239320 0.000000 -0.970941
    outer loop
      vertex 29.600065 -3.500000 22.371483
      vertex 29.600065 -7.000000 22.371483
      vertex 29.342590 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.239320 0.000000 -0.970941
    outer loop
      vertex 29.600065 -7.000000 22.371483
      vertex 29.342590 -7.000000 22.308020
      vertex 29.342590 -3.500000 22.308020
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 29.342590 -3.500000 22.308020
      vertex 29.342590 -7.000000 22.308020
      vertex 29.077410 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.342590 -7.000000 22.308020
      vertex 29.077410 -7.000000 22.308020
      vertex 29.077410 -3.500000 22.308020
    endloop
  endfacet
  facet normal -0.239320 -0.000000 -0.970941
    outer loop
      vertex 29.077410 -3.500000 22.308020
      vertex 29.077410 -7.000000 22.308020
      vertex 28.819935 -3.500000 22.371483
    endloop
  endfacet
  facet normal -0.239320 -0.000000 -0.970941
    outer loop
      vertex 29.077410 -7.000000 22.308020
      vertex 28.819935 -7.000000 22.371483
      vertex 28.819935 -3.500000 22.371483
    endloop
  endfacet
  facet normal -0.464723 0.000000 -0.885456
    outer loop
      vertex 28.819935 -7.000000 22.371483
      vertex 28.585129 -7.000000 22.494719
      vertex 28.819935 -3.500000 22.371483
    endloop
  endfacet
  facet normal -0.464723 0.000000 -0.885456
    outer loop
      vertex 28.819935 -3.500000 22.371483
      vertex 28.585129 -7.000000 22.494719
      vertex 28.585129 -3.500000 22.494719
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748512
    outer loop
      vertex 28.585129 -3.500000 22.494719
      vertex 28.585129 -7.000000 22.494719
      vertex 28.386639 -3.500000 22.670565
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748512
    outer loop
      vertex 28.585129 -7.000000 22.494719
      vertex 28.386639 -7.000000 22.670565
      vertex 28.386639 -3.500000 22.670565
    endloop
  endfacet
  facet normal -0.822984 -0.000000 -0.568064
    outer loop
      vertex 28.386639 -3.500000 22.670565
      vertex 28.386639 -7.000000 22.670565
      vertex 28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal -0.822984 0.000000 -0.568064
    outer loop
      vertex 28.386639 -7.000000 22.670565
      vertex 28.235998 -7.000000 22.888805
      vertex 28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex 28.235998 -3.500000 22.888805
      vertex 28.141964 -7.000000 23.136753
      vertex 28.141964 -3.500000 23.136753
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex 28.235998 -7.000000 22.888805
      vertex 28.141964 -7.000000 23.136753
      vertex 28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal -0.992709 -0.000000 -0.120535
    outer loop
      vertex 28.141964 -3.500000 23.136753
      vertex 28.110001 -7.000000 23.400000
      vertex 28.110001 -3.500000 23.400000
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120535
    outer loop
      vertex 28.141964 -7.000000 23.136753
      vertex 28.110001 -7.000000 23.400000
      vertex 28.141964 -3.500000 23.136753
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120535
    outer loop
      vertex 28.110001 -3.500000 -27.400000
      vertex 28.110001 -7.000000 -27.400000
      vertex 28.141964 -3.500000 -27.136753
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex 28.141964 -3.500000 -27.136753
      vertex 28.141964 -7.000000 -27.136753
      vertex 28.235998 -3.500000 -26.888805
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120535
    outer loop
      vertex 28.110001 -7.000000 -27.400000
      vertex 28.141964 -7.000000 -27.136753
      vertex 28.141964 -3.500000 -27.136753
    endloop
  endfacet
  facet normal -0.822984 0.000000 0.568064
    outer loop
      vertex 28.235998 -3.500000 -26.888805
      vertex 28.235998 -7.000000 -26.888805
      vertex 28.386639 -3.500000 -26.670565
    endloop
  endfacet
  facet normal -0.935016 -0.000000 0.354605
    outer loop
      vertex 28.141964 -7.000000 -27.136753
      vertex 28.235998 -7.000000 -26.888805
      vertex 28.235998 -3.500000 -26.888805
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex 28.386639 -3.500000 -26.670565
      vertex 28.386639 -7.000000 -26.670565
      vertex 28.585129 -3.500000 -26.494719
    endloop
  endfacet
  facet normal -0.822984 -0.000000 0.568064
    outer loop
      vertex 28.235998 -7.000000 -26.888805
      vertex 28.386639 -7.000000 -26.670565
      vertex 28.386639 -3.500000 -26.670565
    endloop
  endfacet
  facet normal -0.464723 0.000000 0.885456
    outer loop
      vertex 28.585129 -3.500000 -26.494719
      vertex 28.585129 -7.000000 -26.494719
      vertex 28.819935 -3.500000 -26.371483
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex 28.386639 -7.000000 -26.670565
      vertex 28.585129 -7.000000 -26.494719
      vertex 28.585129 -3.500000 -26.494719
    endloop
  endfacet
  facet normal -0.239320 0.000000 0.970941
    outer loop
      vertex 28.819935 -3.500000 -26.371483
      vertex 28.819935 -7.000000 -26.371483
      vertex 29.077410 -3.500000 -26.308020
    endloop
  endfacet
  facet normal -0.464723 -0.000000 0.885456
    outer loop
      vertex 28.585129 -7.000000 -26.494719
      vertex 28.819935 -7.000000 -26.371483
      vertex 28.819935 -3.500000 -26.371483
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 29.077410 -3.500000 -26.308020
      vertex 29.077410 -7.000000 -26.308020
      vertex 29.342590 -3.500000 -26.308020
    endloop
  endfacet
  facet normal -0.239320 0.000000 0.970941
    outer loop
      vertex 28.819935 -7.000000 -26.371483
      vertex 29.077410 -7.000000 -26.308020
      vertex 29.077410 -3.500000 -26.308020
    endloop
  endfacet
  facet normal 0.239320 0.000000 0.970941
    outer loop
      vertex 29.342590 -3.500000 -26.308020
      vertex 29.342590 -7.000000 -26.308020
      vertex 29.600065 -3.500000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.077410 -7.000000 -26.308020
      vertex 29.342590 -7.000000 -26.308020
      vertex 29.342590 -3.500000 -26.308020
    endloop
  endfacet
  facet normal 0.464723 0.000000 0.885456
    outer loop
      vertex 29.600065 -3.500000 -26.371483
      vertex 29.600065 -7.000000 -26.371483
      vertex 29.834871 -3.500000 -26.494719
    endloop
  endfacet
  facet normal 0.239320 -0.000000 0.970941
    outer loop
      vertex 29.342590 -7.000000 -26.308020
      vertex 29.600065 -7.000000 -26.371483
      vertex 29.600065 -3.500000 -26.371483
    endloop
  endfacet
  facet normal 0.663121 0.000000 0.748512
    outer loop
      vertex 29.834871 -3.500000 -26.494719
      vertex 29.834871 -7.000000 -26.494719
      vertex 30.033361 -3.500000 -26.670565
    endloop
  endfacet
  facet normal 0.464723 0.000000 0.885456
    outer loop
      vertex 29.600065 -7.000000 -26.371483
      vertex 29.834871 -7.000000 -26.494719
      vertex 29.834871 -3.500000 -26.494719
    endloop
  endfacet
  facet normal 0.822984 0.000000 0.568064
    outer loop
      vertex 30.033361 -3.500000 -26.670565
      vertex 30.033361 -7.000000 -26.670565
      vertex 30.184002 -3.500000 -26.888805
    endloop
  endfacet
  facet normal 0.663121 -0.000000 0.748512
    outer loop
      vertex 29.834871 -7.000000 -26.494719
      vertex 30.033361 -7.000000 -26.670565
      vertex 30.033361 -3.500000 -26.670565
    endloop
  endfacet
  facet normal 0.822984 0.000000 0.568064
    outer loop
      vertex 30.033361 -7.000000 -26.670565
      vertex 30.184002 -7.000000 -26.888805
      vertex 30.184002 -3.500000 -26.888805
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 30.184002 -3.500000 -26.888805
      vertex 30.184002 -7.000000 -26.888805
      vertex 30.278036 -3.500000 -27.136753
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 30.184002 -7.000000 -26.888805
      vertex 30.278036 -7.000000 -27.136753
      vertex 30.278036 -3.500000 -27.136753
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120535
    outer loop
      vertex 30.278036 -3.500000 -27.136753
      vertex 30.278036 -7.000000 -27.136753
      vertex 30.309999 -3.500000 -27.400000
    endloop
  endfacet
  facet normal 0.992709 -0.000000 0.120535
    outer loop
      vertex 30.278036 -7.000000 -27.136753
      vertex 30.309999 -7.000000 -27.400000
      vertex 30.309999 -3.500000 -27.400000
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120534
    outer loop
      vertex 30.309999 -3.500000 -27.400000
      vertex 30.309999 -7.000000 -27.400000
      vertex 30.278036 -3.500000 -27.663248
    endloop
  endfacet
  facet normal 0.992709 -0.000000 -0.120534
    outer loop
      vertex 30.309999 -7.000000 -27.400000
      vertex 30.278036 -7.000000 -27.663248
      vertex 30.278036 -3.500000 -27.663248
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex 30.278036 -7.000000 -27.663248
      vertex 30.184002 -7.000000 -27.911196
      vertex 30.278036 -3.500000 -27.663248
    endloop
  endfacet
  facet normal 0.935016 -0.000000 -0.354605
    outer loop
      vertex 30.278036 -3.500000 -27.663248
      vertex 30.184002 -7.000000 -27.911196
      vertex 30.184002 -3.500000 -27.911196
    endloop
  endfacet
  facet normal 0.822982 0.000000 -0.568068
    outer loop
      vertex 30.184002 -7.000000 -27.911196
      vertex 30.033361 -7.000000 -28.129435
      vertex 30.184002 -3.500000 -27.911196
    endloop
  endfacet
  facet normal 0.822982 -0.000000 -0.568068
    outer loop
      vertex 30.184002 -3.500000 -27.911196
      vertex 30.033361 -7.000000 -28.129435
      vertex 30.033361 -3.500000 -28.129435
    endloop
  endfacet
  facet normal 0.663125 0.000000 -0.748509
    outer loop
      vertex 30.033361 -7.000000 -28.129435
      vertex 29.834871 -7.000000 -28.305283
      vertex 30.033361 -3.500000 -28.129435
    endloop
  endfacet
  facet normal 0.663125 -0.000000 -0.748509
    outer loop
      vertex 30.033361 -3.500000 -28.129435
      vertex 29.834871 -7.000000 -28.305283
      vertex 29.834871 -3.500000 -28.305283
    endloop
  endfacet
  facet normal 0.464723 0.000000 -0.885456
    outer loop
      vertex 29.834871 -7.000000 -28.305283
      vertex 29.600065 -7.000000 -28.428518
      vertex 29.834871 -3.500000 -28.305283
    endloop
  endfacet
  facet normal 0.464723 -0.000000 -0.885456
    outer loop
      vertex 29.834871 -3.500000 -28.305283
      vertex 29.600065 -7.000000 -28.428518
      vertex 29.600065 -3.500000 -28.428518
    endloop
  endfacet
  facet normal 0.239314 0.000000 -0.970942
    outer loop
      vertex 29.600065 -3.500000 -28.428518
      vertex 29.600065 -7.000000 -28.428518
      vertex 29.342590 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.239314 -0.000000 -0.970942
    outer loop
      vertex 29.600065 -7.000000 -28.428518
      vertex 29.342590 -7.000000 -28.491980
      vertex 29.342590 -3.500000 -28.491980
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 29.342590 -3.500000 -28.491980
      vertex 29.342590 -7.000000 -28.491980
      vertex 29.077410 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.342590 -7.000000 -28.491980
      vertex 29.077410 -7.000000 -28.491980
      vertex 29.077410 -3.500000 -28.491980
    endloop
  endfacet
  facet normal -0.239314 0.000000 -0.970942
    outer loop
      vertex 29.077410 -7.000000 -28.491980
      vertex 28.819935 -7.000000 -28.428518
      vertex 29.077410 -3.500000 -28.491980
    endloop
  endfacet
  facet normal -0.239314 0.000000 -0.970942
    outer loop
      vertex 29.077410 -3.500000 -28.491980
      vertex 28.819935 -7.000000 -28.428518
      vertex 28.819935 -3.500000 -28.428518
    endloop
  endfacet
  facet normal -0.464723 0.000000 -0.885456
    outer loop
      vertex 28.819935 -7.000000 -28.428518
      vertex 28.585129 -7.000000 -28.305283
      vertex 28.819935 -3.500000 -28.428518
    endloop
  endfacet
  facet normal -0.464723 0.000000 -0.885456
    outer loop
      vertex 28.819935 -3.500000 -28.428518
      vertex 28.585129 -7.000000 -28.305283
      vertex 28.585129 -3.500000 -28.305283
    endloop
  endfacet
  facet normal -0.663125 0.000000 -0.748509
    outer loop
      vertex 28.585129 -7.000000 -28.305283
      vertex 28.386639 -7.000000 -28.129435
      vertex 28.585129 -3.500000 -28.305283
    endloop
  endfacet
  facet normal -0.663125 0.000000 -0.748509
    outer loop
      vertex 28.585129 -3.500000 -28.305283
      vertex 28.386639 -7.000000 -28.129435
      vertex 28.386639 -3.500000 -28.129435
    endloop
  endfacet
  facet normal -0.822982 0.000000 -0.568068
    outer loop
      vertex 28.386639 -3.500000 -28.129435
      vertex 28.235998 -7.000000 -27.911196
      vertex 28.235998 -3.500000 -27.911196
    endloop
  endfacet
  facet normal -0.822982 0.000000 -0.568068
    outer loop
      vertex 28.386639 -7.000000 -28.129435
      vertex 28.235998 -7.000000 -27.911196
      vertex 28.386639 -3.500000 -28.129435
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex 28.235998 -3.500000 -27.911196
      vertex 28.141964 -7.000000 -27.663248
      vertex 28.141964 -3.500000 -27.663248
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex 28.235998 -7.000000 -27.911196
      vertex 28.141964 -7.000000 -27.663248
      vertex 28.235998 -3.500000 -27.911196
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120534
    outer loop
      vertex 28.141964 -3.500000 -27.663248
      vertex 28.110001 -7.000000 -27.400000
      vertex 28.110001 -3.500000 -27.400000
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120534
    outer loop
      vertex 28.141964 -7.000000 -27.663248
      vertex 28.110001 -7.000000 -27.400000
      vertex 28.141964 -3.500000 -27.663248
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120534
    outer loop
      vertex -28.141964 -7.000000 23.663248
      vertex -28.110001 -7.000000 23.400000
      vertex -28.110001 -3.500000 23.400000
    endloop
  endfacet
  facet normal 0.992709 -0.000000 0.120534
    outer loop
      vertex -28.141964 -7.000000 23.663248
      vertex -28.110001 -3.500000 23.400000
      vertex -28.141964 -3.500000 23.663248
    endloop
  endfacet
  facet normal 0.935016 -0.000000 0.354605
    outer loop
      vertex -28.235998 -7.000000 23.911196
      vertex -28.141964 -3.500000 23.663248
      vertex -28.235998 -3.500000 23.911196
    endloop
  endfacet
  facet normal 0.822982 -0.000000 0.568068
    outer loop
      vertex -28.235998 -7.000000 23.911196
      vertex -28.235998 -3.500000 23.911196
      vertex -28.386639 -3.500000 24.129435
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex -28.235998 -7.000000 23.911196
      vertex -28.141964 -7.000000 23.663248
      vertex -28.141964 -3.500000 23.663248
    endloop
  endfacet
  facet normal 0.822982 -0.000000 0.568068
    outer loop
      vertex -28.386639 -7.000000 24.129435
      vertex -28.235998 -7.000000 23.911196
      vertex -28.386639 -3.500000 24.129435
    endloop
  endfacet
  facet normal 0.663125 -0.000000 0.748509
    outer loop
      vertex -28.585129 -7.000000 24.305283
      vertex -28.386639 -3.500000 24.129435
      vertex -28.585129 -3.500000 24.305283
    endloop
  endfacet
  facet normal 0.663125 0.000000 0.748509
    outer loop
      vertex -28.585129 -7.000000 24.305283
      vertex -28.386639 -7.000000 24.129435
      vertex -28.386639 -3.500000 24.129435
    endloop
  endfacet
  facet normal 0.464723 -0.000000 0.885456
    outer loop
      vertex -28.819935 -7.000000 24.428518
      vertex -28.585129 -3.500000 24.305283
      vertex -28.819935 -3.500000 24.428518
    endloop
  endfacet
  facet normal 0.464723 0.000000 0.885456
    outer loop
      vertex -28.819935 -7.000000 24.428518
      vertex -28.585129 -7.000000 24.305283
      vertex -28.585129 -3.500000 24.305283
    endloop
  endfacet
  facet normal 0.239314 -0.000000 0.970942
    outer loop
      vertex -29.077410 -7.000000 24.491980
      vertex -28.819935 -3.500000 24.428518
      vertex -29.077410 -3.500000 24.491980
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -29.077410 -7.000000 24.491980
      vertex -29.077410 -3.500000 24.491980
      vertex -29.342590 -3.500000 24.491980
    endloop
  endfacet
  facet normal 0.239314 0.000000 0.970942
    outer loop
      vertex -29.077410 -7.000000 24.491980
      vertex -28.819935 -7.000000 24.428518
      vertex -28.819935 -3.500000 24.428518
    endloop
  endfacet
  facet normal -0.239314 0.000000 0.970942
    outer loop
      vertex -29.342590 -7.000000 24.491980
      vertex -29.342590 -3.500000 24.491980
      vertex -29.600065 -3.500000 24.428518
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -29.342590 -7.000000 24.491980
      vertex -29.077410 -7.000000 24.491980
      vertex -29.342590 -3.500000 24.491980
    endloop
  endfacet
  facet normal -0.239314 0.000000 0.970942
    outer loop
      vertex -29.600065 -7.000000 24.428518
      vertex -29.342590 -7.000000 24.491980
      vertex -29.600065 -3.500000 24.428518
    endloop
  endfacet
  facet normal -0.464723 0.000000 0.885456
    outer loop
      vertex -29.834871 -7.000000 24.305283
      vertex -29.600065 -3.500000 24.428518
      vertex -29.834871 -3.500000 24.305283
    endloop
  endfacet
  facet normal -0.464723 -0.000000 0.885456
    outer loop
      vertex -29.834871 -7.000000 24.305283
      vertex -29.600065 -7.000000 24.428518
      vertex -29.600065 -3.500000 24.428518
    endloop
  endfacet
  facet normal -0.663125 0.000000 0.748509
    outer loop
      vertex -30.033361 -7.000000 24.129435
      vertex -29.834871 -3.500000 24.305283
      vertex -30.033361 -3.500000 24.129435
    endloop
  endfacet
  facet normal -0.663125 -0.000000 0.748509
    outer loop
      vertex -30.033361 -7.000000 24.129435
      vertex -29.834871 -7.000000 24.305283
      vertex -29.834871 -3.500000 24.305283
    endloop
  endfacet
  facet normal -0.822982 0.000000 0.568068
    outer loop
      vertex -30.184002 -7.000000 23.911196
      vertex -30.033361 -3.500000 24.129435
      vertex -30.184002 -3.500000 23.911196
    endloop
  endfacet
  facet normal -0.822982 -0.000000 0.568068
    outer loop
      vertex -30.184002 -7.000000 23.911196
      vertex -30.033361 -7.000000 24.129435
      vertex -30.033361 -3.500000 24.129435
    endloop
  endfacet
  facet normal -0.935016 -0.000000 0.354605
    outer loop
      vertex -30.278036 -7.000000 23.663248
      vertex -30.184002 -7.000000 23.911196
      vertex -30.184002 -3.500000 23.911196
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex -30.278036 -7.000000 23.663248
      vertex -30.184002 -3.500000 23.911196
      vertex -30.278036 -3.500000 23.663248
    endloop
  endfacet
  facet normal -0.992709 -0.000000 0.120534
    outer loop
      vertex -30.309999 -7.000000 23.400000
      vertex -30.278036 -7.000000 23.663248
      vertex -30.278036 -3.500000 23.663248
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120534
    outer loop
      vertex -30.309999 -7.000000 23.400000
      vertex -30.278036 -3.500000 23.663248
      vertex -30.309999 -3.500000 23.400000
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120535
    outer loop
      vertex -30.309999 -7.000000 23.400000
      vertex -30.309999 -3.500000 23.400000
      vertex -30.278036 -3.500000 23.136753
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120535
    outer loop
      vertex -30.278036 -7.000000 23.136753
      vertex -30.309999 -7.000000 23.400000
      vertex -30.278036 -3.500000 23.136753
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex -30.184002 -7.000000 22.888805
      vertex -30.278036 -7.000000 23.136753
      vertex -30.278036 -3.500000 23.136753
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex -30.184002 -7.000000 22.888805
      vertex -30.278036 -3.500000 23.136753
      vertex -30.184002 -3.500000 22.888805
    endloop
  endfacet
  facet normal -0.822984 0.000000 -0.568064
    outer loop
      vertex -30.033361 -7.000000 22.670565
      vertex -30.184002 -7.000000 22.888805
      vertex -30.184002 -3.500000 22.888805
    endloop
  endfacet
  facet normal -0.822984 0.000000 -0.568064
    outer loop
      vertex -30.033361 -7.000000 22.670565
      vertex -30.184002 -3.500000 22.888805
      vertex -30.033361 -3.500000 22.670565
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748512
    outer loop
      vertex -29.834871 -7.000000 22.494719
      vertex -30.033361 -7.000000 22.670565
      vertex -30.033361 -3.500000 22.670565
    endloop
  endfacet
  facet normal -0.663121 0.000000 -0.748512
    outer loop
      vertex -29.834871 -7.000000 22.494719
      vertex -30.033361 -3.500000 22.670565
      vertex -29.834871 -3.500000 22.494719
    endloop
  endfacet
  facet normal -0.464723 0.000000 -0.885456
    outer loop
      vertex -29.600065 -7.000000 22.371483
      vertex -29.834871 -7.000000 22.494719
      vertex -29.834871 -3.500000 22.494719
    endloop
  endfacet
  facet normal -0.464723 0.000000 -0.885456
    outer loop
      vertex -29.600065 -7.000000 22.371483
      vertex -29.834871 -3.500000 22.494719
      vertex -29.600065 -3.500000 22.371483
    endloop
  endfacet
  facet normal -0.239320 0.000000 -0.970941
    outer loop
      vertex -29.600065 -7.000000 22.371483
      vertex -29.600065 -3.500000 22.371483
      vertex -29.342590 -3.500000 22.308020
    endloop
  endfacet
  facet normal -0.239320 0.000000 -0.970941
    outer loop
      vertex -29.342590 -7.000000 22.308020
      vertex -29.600065 -7.000000 22.371483
      vertex -29.342590 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -29.077410 -7.000000 22.308020
      vertex -29.342590 -7.000000 22.308020
      vertex -29.342590 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -29.077410 -7.000000 22.308020
      vertex -29.342590 -3.500000 22.308020
      vertex -29.077410 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.239320 0.000000 -0.970941
    outer loop
      vertex -28.819935 -7.000000 22.371483
      vertex -29.077410 -7.000000 22.308020
      vertex -29.077410 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.239320 0.000000 -0.970941
    outer loop
      vertex -28.819935 -7.000000 22.371483
      vertex -29.077410 -3.500000 22.308020
      vertex -28.819935 -3.500000 22.371483
    endloop
  endfacet
  facet normal 0.464723 -0.000000 -0.885456
    outer loop
      vertex -28.585129 -7.000000 22.494719
      vertex -28.819935 -7.000000 22.371483
      vertex -28.819935 -3.500000 22.371483
    endloop
  endfacet
  facet normal 0.464723 0.000000 -0.885456
    outer loop
      vertex -28.585129 -7.000000 22.494719
      vertex -28.819935 -3.500000 22.371483
      vertex -28.585129 -3.500000 22.494719
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex -28.585129 -7.000000 22.494719
      vertex -28.585129 -3.500000 22.494719
      vertex -28.386639 -3.500000 22.670565
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex -28.386639 -7.000000 22.670565
      vertex -28.585129 -7.000000 22.494719
      vertex -28.386639 -3.500000 22.670565
    endloop
  endfacet
  facet normal 0.822984 0.000000 -0.568064
    outer loop
      vertex -28.386639 -7.000000 22.670565
      vertex -28.386639 -3.500000 22.670565
      vertex -28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.822984 0.000000 -0.568064
    outer loop
      vertex -28.235998 -7.000000 22.888805
      vertex -28.386639 -7.000000 22.670565
      vertex -28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex -28.141964 -7.000000 23.136753
      vertex -28.235998 -3.500000 22.888805
      vertex -28.141964 -3.500000 23.136753
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120535
    outer loop
      vertex -28.141964 -7.000000 23.136753
      vertex -28.141964 -3.500000 23.136753
      vertex -28.110001 -3.500000 23.400000
    endloop
  endfacet
  facet normal 0.935016 -0.000000 -0.354605
    outer loop
      vertex -28.141964 -7.000000 23.136753
      vertex -28.235998 -7.000000 22.888805
      vertex -28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120535
    outer loop
      vertex -28.110001 -7.000000 23.400000
      vertex -28.141964 -7.000000 23.136753
      vertex -28.110001 -3.500000 23.400000
    endloop
  endfacet
  facet normal 0.992709 -0.000000 0.120535
    outer loop
      vertex -28.141964 -7.000000 -27.136753
      vertex -28.110001 -7.000000 -27.400000
      vertex -28.110001 -3.500000 -27.400000
    endloop
  endfacet
  facet normal 0.992709 -0.000000 0.120535
    outer loop
      vertex -28.141964 -7.000000 -27.136753
      vertex -28.110001 -3.500000 -27.400000
      vertex -28.141964 -3.500000 -27.136753
    endloop
  endfacet
  facet normal 0.935016 -0.000000 0.354605
    outer loop
      vertex -28.235998 -7.000000 -26.888805
      vertex -28.141964 -3.500000 -27.136753
      vertex -28.235998 -3.500000 -26.888805
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex -28.235998 -7.000000 -26.888805
      vertex -28.141964 -7.000000 -27.136753
      vertex -28.141964 -3.500000 -27.136753
    endloop
  endfacet
  facet normal 0.822984 -0.000000 0.568064
    outer loop
      vertex -28.386639 -7.000000 -26.670565
      vertex -28.235998 -3.500000 -26.888805
      vertex -28.386639 -3.500000 -26.670565
    endloop
  endfacet
  facet normal 0.822984 0.000000 0.568064
    outer loop
      vertex -28.386639 -7.000000 -26.670565
      vertex -28.235998 -7.000000 -26.888805
      vertex -28.235998 -3.500000 -26.888805
    endloop
  endfacet
  facet normal 0.663121 -0.000000 0.748512
    outer loop
      vertex -28.585129 -7.000000 -26.494719
      vertex -28.386639 -3.500000 -26.670565
      vertex -28.585129 -3.500000 -26.494719
    endloop
  endfacet
  facet normal 0.663121 -0.000000 0.748512
    outer loop
      vertex -28.585129 -7.000000 -26.494719
      vertex -28.386639 -7.000000 -26.670565
      vertex -28.386639 -3.500000 -26.670565
    endloop
  endfacet
  facet normal 0.464723 -0.000000 0.885456
    outer loop
      vertex -28.819935 -7.000000 -26.371483
      vertex -28.585129 -3.500000 -26.494719
      vertex -28.819935 -3.500000 -26.371483
    endloop
  endfacet
  facet normal 0.464723 0.000000 0.885456
    outer loop
      vertex -28.819935 -7.000000 -26.371483
      vertex -28.585129 -7.000000 -26.494719
      vertex -28.585129 -3.500000 -26.494719
    endloop
  endfacet
  facet normal 0.239320 -0.000000 0.970941
    outer loop
      vertex -29.077410 -7.000000 -26.308020
      vertex -28.819935 -3.500000 -26.371483
      vertex -29.077410 -3.500000 -26.308020
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -29.077410 -7.000000 -26.308020
      vertex -29.077410 -3.500000 -26.308020
      vertex -29.342590 -3.500000 -26.308020
    endloop
  endfacet
  facet normal 0.239320 -0.000000 0.970941
    outer loop
      vertex -29.077410 -7.000000 -26.308020
      vertex -28.819935 -7.000000 -26.371483
      vertex -28.819935 -3.500000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -29.342590 -7.000000 -26.308020
      vertex -29.077410 -7.000000 -26.308020
      vertex -29.342590 -3.500000 -26.308020
    endloop
  endfacet
  facet normal -0.239320 0.000000 0.970941
    outer loop
      vertex -29.600065 -7.000000 -26.371483
      vertex -29.342590 -3.500000 -26.308020
      vertex -29.600065 -3.500000 -26.371483
    endloop
  endfacet
  facet normal -0.239320 0.000000 0.970941
    outer loop
      vertex -29.600065 -7.000000 -26.371483
      vertex -29.342590 -7.000000 -26.308020
      vertex -29.342590 -3.500000 -26.308020
    endloop
  endfacet
  facet normal -0.464723 0.000000 0.885456
    outer loop
      vertex -29.834871 -7.000000 -26.494719
      vertex -29.600065 -3.500000 -26.371483
      vertex -29.834871 -3.500000 -26.494719
    endloop
  endfacet
  facet normal -0.464723 -0.000000 0.885456
    outer loop
      vertex -29.834871 -7.000000 -26.494719
      vertex -29.600065 -7.000000 -26.371483
      vertex -29.600065 -3.500000 -26.371483
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex -30.033361 -7.000000 -26.670565
      vertex -29.834871 -3.500000 -26.494719
      vertex -30.033361 -3.500000 -26.670565
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex -30.033361 -7.000000 -26.670565
      vertex -29.834871 -7.000000 -26.494719
      vertex -29.834871 -3.500000 -26.494719
    endloop
  endfacet
  facet normal -0.822984 0.000000 0.568064
    outer loop
      vertex -30.184002 -7.000000 -26.888805
      vertex -30.033361 -3.500000 -26.670565
      vertex -30.184002 -3.500000 -26.888805
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex -30.184002 -7.000000 -26.888805
      vertex -30.184002 -3.500000 -26.888805
      vertex -30.278036 -3.500000 -27.136753
    endloop
  endfacet
  facet normal -0.822984 -0.000000 0.568064
    outer loop
      vertex -30.184002 -7.000000 -26.888805
      vertex -30.033361 -7.000000 -26.670565
      vertex -30.033361 -3.500000 -26.670565
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex -30.278036 -7.000000 -27.136753
      vertex -30.184002 -7.000000 -26.888805
      vertex -30.278036 -3.500000 -27.136753
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120535
    outer loop
      vertex -30.278036 -7.000000 -27.136753
      vertex -30.278036 -3.500000 -27.136753
      vertex -30.309999 -3.500000 -27.400000
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120535
    outer loop
      vertex -30.309999 -7.000000 -27.400000
      vertex -30.278036 -7.000000 -27.136753
      vertex -30.309999 -3.500000 -27.400000
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120534
    outer loop
      vertex -30.309999 -7.000000 -27.400000
      vertex -30.309999 -3.500000 -27.400000
      vertex -30.278036 -3.500000 -27.663248
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120534
    outer loop
      vertex -30.278036 -7.000000 -27.663248
      vertex -30.309999 -7.000000 -27.400000
      vertex -30.278036 -3.500000 -27.663248
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex -30.184002 -7.000000 -27.911196
      vertex -30.278036 -7.000000 -27.663248
      vertex -30.278036 -3.500000 -27.663248
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex -30.184002 -7.000000 -27.911196
      vertex -30.278036 -3.500000 -27.663248
      vertex -30.184002 -3.500000 -27.911196
    endloop
  endfacet
  facet normal -0.822982 0.000000 -0.568068
    outer loop
      vertex -30.033361 -7.000000 -28.129435
      vertex -30.184002 -7.000000 -27.911196
      vertex -30.184002 -3.500000 -27.911196
    endloop
  endfacet
  facet normal -0.822982 0.000000 -0.568068
    outer loop
      vertex -30.033361 -7.000000 -28.129435
      vertex -30.184002 -3.500000 -27.911196
      vertex -30.033361 -3.500000 -28.129435
    endloop
  endfacet
  facet normal -0.663125 0.000000 -0.748509
    outer loop
      vertex -29.834871 -7.000000 -28.305283
      vertex -30.033361 -7.000000 -28.129435
      vertex -30.033361 -3.500000 -28.129435
    endloop
  endfacet
  facet normal -0.663125 0.000000 -0.748509
    outer loop
      vertex -29.834871 -7.000000 -28.305283
      vertex -30.033361 -3.500000 -28.129435
      vertex -29.834871 -3.500000 -28.305283
    endloop
  endfacet
  facet normal -0.464723 0.000000 -0.885456
    outer loop
      vertex -29.600065 -7.000000 -28.428518
      vertex -29.834871 -7.000000 -28.305283
      vertex -29.834871 -3.500000 -28.305283
    endloop
  endfacet
  facet normal -0.464723 0.000000 -0.885456
    outer loop
      vertex -29.600065 -7.000000 -28.428518
      vertex -29.834871 -3.500000 -28.305283
      vertex -29.600065 -3.500000 -28.428518
    endloop
  endfacet
  facet normal -0.239314 0.000000 -0.970942
    outer loop
      vertex -29.342590 -7.000000 -28.491980
      vertex -29.600065 -7.000000 -28.428518
      vertex -29.600065 -3.500000 -28.428518
    endloop
  endfacet
  facet normal -0.239314 0.000000 -0.970942
    outer loop
      vertex -29.342590 -7.000000 -28.491980
      vertex -29.600065 -3.500000 -28.428518
      vertex -29.342590 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -29.077410 -7.000000 -28.491980
      vertex -29.342590 -7.000000 -28.491980
      vertex -29.342590 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -29.077410 -7.000000 -28.491980
      vertex -29.342590 -3.500000 -28.491980
      vertex -29.077410 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.239314 -0.000000 -0.970942
    outer loop
      vertex -28.819935 -7.000000 -28.428518
      vertex -29.077410 -7.000000 -28.491980
      vertex -29.077410 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.239314 0.000000 -0.970942
    outer loop
      vertex -28.819935 -7.000000 -28.428518
      vertex -29.077410 -3.500000 -28.491980
      vertex -28.819935 -3.500000 -28.428518
    endloop
  endfacet
  facet normal 0.464723 -0.000000 -0.885456
    outer loop
      vertex -28.585129 -7.000000 -28.305283
      vertex -28.819935 -7.000000 -28.428518
      vertex -28.819935 -3.500000 -28.428518
    endloop
  endfacet
  facet normal 0.464723 0.000000 -0.885456
    outer loop
      vertex -28.585129 -7.000000 -28.305283
      vertex -28.819935 -3.500000 -28.428518
      vertex -28.585129 -3.500000 -28.305283
    endloop
  endfacet
  facet normal 0.663125 0.000000 -0.748509
    outer loop
      vertex -28.585129 -7.000000 -28.305283
      vertex -28.585129 -3.500000 -28.305283
      vertex -28.386639 -3.500000 -28.129435
    endloop
  endfacet
  facet normal 0.663125 0.000000 -0.748509
    outer loop
      vertex -28.386639 -7.000000 -28.129435
      vertex -28.585129 -7.000000 -28.305283
      vertex -28.386639 -3.500000 -28.129435
    endloop
  endfacet
  facet normal 0.822982 0.000000 -0.568068
    outer loop
      vertex -28.235998 -7.000000 -27.911196
      vertex -28.386639 -3.500000 -28.129435
      vertex -28.235998 -3.500000 -27.911196
    endloop
  endfacet
  facet normal 0.822982 -0.000000 -0.568068
    outer loop
      vertex -28.235998 -7.000000 -27.911196
      vertex -28.386639 -7.000000 -28.129435
      vertex -28.386639 -3.500000 -28.129435
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex -28.141964 -7.000000 -27.663248
      vertex -28.235998 -3.500000 -27.911196
      vertex -28.141964 -3.500000 -27.663248
    endloop
  endfacet
  facet normal 0.935016 -0.000000 -0.354605
    outer loop
      vertex -28.141964 -7.000000 -27.663248
      vertex -28.235998 -7.000000 -27.911196
      vertex -28.235998 -3.500000 -27.911196
    endloop
  endfacet
  facet normal 0.992709 -0.000000 -0.120534
    outer loop
      vertex -28.110001 -7.000000 -27.400000
      vertex -28.141964 -7.000000 -27.663248
      vertex -28.141964 -3.500000 -27.663248
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120534
    outer loop
      vertex -28.110001 -7.000000 -27.400000
      vertex -28.141964 -3.500000 -27.663248
      vertex -28.110001 -3.500000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 32.460079 -8.000000 27.971270
      vertex 34.250000 -8.000000 26.030001
      vertex 32.685638 -8.000000 28.171097
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex 32.856819 -8.000000 28.419096
      vertex 32.685638 -8.000000 28.171097
      vertex 34.250000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 32.193256 -8.000000 27.831230
      vertex 34.250000 -8.000000 26.030001
      vertex 32.460079 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex 32.963676 -8.000000 28.700855
      vertex 32.856819 -8.000000 28.419096
      vertex 34.250000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 31.900671 -8.000000 27.759113
      vertex 34.250000 -8.000000 26.030001
      vertex 32.193256 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex 33.000000 -8.000000 29.000000
      vertex 32.963676 -8.000000 28.700855
      vertex 34.250000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 31.599329 -8.000000 27.759113
      vertex 34.250000 -8.000000 26.030001
      vertex 31.900671 -8.000000 27.759113
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 31.306744 -8.000000 27.831230
      vertex 34.250000 -8.000000 26.030001
      vertex 31.599329 -8.000000 27.759113
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -8.000000 31.280001
      vertex 32.856819 -8.000000 29.580904
      vertex 32.963676 -8.000000 29.299145
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 34.250000 -8.000000 31.280001
      vertex 32.963676 -8.000000 29.299145
      vertex 33.000000 -8.000000 29.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex 34.250000 -8.000000 31.280001
      vertex 33.000000 -8.000000 29.000000
      vertex 34.250000 -8.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 32.685638 -8.000000 29.828903
      vertex 32.856819 -8.000000 29.580904
      vertex 34.250000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 32.460079 -8.000000 30.028730
      vertex 32.685638 -8.000000 29.828903
      vertex 34.250000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 32.193256 -8.000000 30.168770
      vertex 32.460079 -8.000000 30.028730
      vertex 34.250000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 31.900671 -8.000000 30.240887
      vertex 32.193256 -8.000000 30.168770
      vertex 34.250000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 31.599329 -8.000000 30.240887
      vertex 31.900671 -8.000000 30.240887
      vertex 34.250000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 26.030001
      vertex 31.306744 -8.000000 27.831230
      vertex 31.039919 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 26.030001
      vertex 31.039919 -8.000000 27.971270
      vertex 30.814362 -8.000000 28.171097
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 26.030001
      vertex 30.814362 -8.000000 28.171097
      vertex 30.643181 -8.000000 28.419096
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 26.030001
      vertex 30.643181 -8.000000 28.419096
      vertex 30.536324 -8.000000 28.700855
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 26.030001
      vertex 30.536324 -8.000000 28.700855
      vertex 30.500000 -8.000000 29.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 26.030001
      vertex 34.250000 -8.000000 26.030001
      vertex 31.306744 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 31.280001
      vertex 30.500000 -8.000000 29.000000
      vertex 30.536324 -8.000000 29.299145
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 31.280001
      vertex 30.536324 -8.000000 29.299145
      vertex 30.643181 -8.000000 29.580904
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 31.280001
      vertex 30.643181 -8.000000 29.580904
      vertex 30.814362 -8.000000 29.828903
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 31.280001
      vertex 30.814362 -8.000000 29.828903
      vertex 31.039919 -8.000000 30.028730
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 31.280001
      vertex 31.039919 -8.000000 30.028730
      vertex 31.306744 -8.000000 30.168770
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 31.280001
      vertex 31.306744 -8.000000 30.168770
      vertex 31.599329 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 31.280001
      vertex 31.599329 -8.000000 30.240887
      vertex 34.250000 -8.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 25.000000 -8.000000 31.280001
      vertex 25.000000 -8.000000 26.030001
      vertex 30.500000 -8.000000 29.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.000000 -5.000000 31.280001
      vertex 25.000000 -8.000000 31.280001
      vertex 34.250000 -8.000000 31.280001
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 25.000000 -5.000000 31.280001
      vertex 34.250000 -8.000000 31.280001
      vertex 34.250000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 31.039919 -5.000000 27.971270
      vertex 25.000000 -5.000000 26.030001
      vertex 30.814362 -5.000000 28.171097
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.643181 -5.000000 28.419096
      vertex 30.814362 -5.000000 28.171097
      vertex 25.000000 -5.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 31.306744 -5.000000 27.831230
      vertex 25.000000 -5.000000 26.030001
      vertex 31.039919 -5.000000 27.971270
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.536324 -5.000000 28.700855
      vertex 30.643181 -5.000000 28.419096
      vertex 25.000000 -5.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.500000 -5.000000 29.000000
      vertex 25.000000 -5.000000 26.030001
      vertex 25.000000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.500000 -5.000000 29.000000
      vertex 30.536324 -5.000000 28.700855
      vertex 25.000000 -5.000000 26.030001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.536324 -5.000000 29.299145
      vertex 30.500000 -5.000000 29.000000
      vertex 25.000000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.643181 -5.000000 29.580904
      vertex 30.536324 -5.000000 29.299145
      vertex 25.000000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 26.030001
      vertex 31.900671 -5.000000 27.759113
      vertex 32.193256 -5.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 26.030001
      vertex 31.599329 -5.000000 27.759113
      vertex 31.900671 -5.000000 27.759113
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 26.030001
      vertex 31.306744 -5.000000 27.831230
      vertex 31.599329 -5.000000 27.759113
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 26.030001
      vertex 25.000000 -5.000000 26.030001
      vertex 31.306744 -5.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 32.460079 -5.000000 27.971270
      vertex 34.250000 -5.000000 26.030001
      vertex 32.193256 -5.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.814362 -5.000000 29.828903
      vertex 30.643181 -5.000000 29.580904
      vertex 25.000000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 32.685638 -5.000000 28.171097
      vertex 34.250000 -5.000000 26.030001
      vertex 32.460079 -5.000000 27.971270
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 31.039919 -5.000000 30.028730
      vertex 30.814362 -5.000000 29.828903
      vertex 25.000000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 32.856819 -5.000000 28.419096
      vertex 34.250000 -5.000000 26.030001
      vertex 32.685638 -5.000000 28.171097
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 31.306744 -5.000000 30.168770
      vertex 31.039919 -5.000000 30.028730
      vertex 25.000000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 32.963676 -5.000000 28.700855
      vertex 34.250000 -5.000000 26.030001
      vertex 32.856819 -5.000000 28.419096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 31.599329 -5.000000 30.240887
      vertex 31.306744 -5.000000 30.168770
      vertex 25.000000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 33.000000 -5.000000 29.000000
      vertex 34.250000 -5.000000 26.030001
      vertex 32.963676 -5.000000 28.700855
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 31.900671 -5.000000 30.240887
      vertex 31.599329 -5.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 32.193256 -5.000000 30.168770
      vertex 31.900671 -5.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 32.460079 -5.000000 30.028730
      vertex 32.193256 -5.000000 30.168770
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 32.685638 -5.000000 29.828903
      vertex 32.460079 -5.000000 30.028730
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 32.856819 -5.000000 29.580904
      vertex 32.685638 -5.000000 29.828903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 32.963676 -5.000000 29.299145
      vertex 32.856819 -5.000000 29.580904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 33.000000 -5.000000 29.000000
      vertex 32.963676 -5.000000 29.299145
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 31.599329 -5.000000 30.240887
      vertex 25.000000 -5.000000 31.280001
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 34.250000 -5.000000 31.280001
      vertex 34.250000 -5.000000 26.030001
      vertex 33.000000 -5.000000 29.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.834871 -3.500000 22.494719
      vertex 30.184002 -3.500000 22.888805
      vertex 30.033361 -3.500000 22.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.600065 -3.500000 22.371483
      vertex 29.342590 -3.500000 22.308020
      vertex 29.834871 -3.500000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.309999 -3.500000 23.400000
      vertex 30.184002 -3.500000 23.911196
      vertex 30.278036 -3.500000 23.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.278036 -3.500000 23.136753
      vertex 30.184002 -3.500000 23.911196
      vertex 30.309999 -3.500000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.184002 -3.500000 22.888805
      vertex 30.184002 -3.500000 23.911196
      vertex 30.278036 -3.500000 23.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.834871 -3.500000 22.494719
      vertex 30.184002 -3.500000 23.911196
      vertex 30.184002 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.184002 -3.500000 23.911196
      vertex 29.834871 -3.500000 24.305283
      vertex 30.033361 -3.500000 24.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.834871 -3.500000 22.494719
      vertex 29.834871 -3.500000 24.305283
      vertex 30.184002 -3.500000 23.911196
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.585129 -3.500000 22.494719
      vertex 28.235998 -3.500000 22.888805
      vertex 28.819935 -3.500000 22.371483
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.386639 -3.500000 22.670565
      vertex 28.235998 -3.500000 22.888805
      vertex 28.585129 -3.500000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.342590 -3.500000 22.308020
      vertex 29.600065 -3.500000 24.428518
      vertex 29.834871 -3.500000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.834871 -3.500000 22.494719
      vertex 29.600065 -3.500000 24.428518
      vertex 29.834871 -3.500000 24.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.342590 -3.500000 22.308020
      vertex 29.342590 -3.500000 24.491980
      vertex 29.600065 -3.500000 24.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.077410 -3.500000 22.308020
      vertex 29.077410 -3.500000 24.491980
      vertex 29.342590 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.342590 -3.500000 22.308020
      vertex 29.077410 -3.500000 24.491980
      vertex 29.342590 -3.500000 24.491980
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.819935 -3.500000 22.371483
      vertex 28.819935 -3.500000 24.428518
      vertex 29.077410 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.077410 -3.500000 22.308020
      vertex 28.819935 -3.500000 24.428518
      vertex 29.077410 -3.500000 24.491980
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.141964 -3.500000 23.663248
      vertex 28.235998 -3.500000 23.911196
      vertex 28.110001 -3.500000 23.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.141964 -3.500000 23.136753
      vertex 28.235998 -3.500000 23.911196
      vertex 28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.110001 -3.500000 23.400000
      vertex 28.235998 -3.500000 23.911196
      vertex 28.141964 -3.500000 23.136753
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.235998 -3.500000 22.888805
      vertex 28.585129 -3.500000 24.305283
      vertex 28.819935 -3.500000 22.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.819935 -3.500000 22.371483
      vertex 28.585129 -3.500000 24.305283
      vertex 28.819935 -3.500000 24.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 28.235998 -3.500000 22.888805
      vertex 28.386639 -3.500000 24.129435
      vertex 28.585129 -3.500000 24.305283
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.235998 -3.500000 23.911196
      vertex 28.386639 -3.500000 24.129435
      vertex 28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.834871 -3.500000 -28.305283
      vertex 30.184002 -3.500000 -27.911196
      vertex 30.033361 -3.500000 -28.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.600065 -3.500000 -28.428518
      vertex 29.342590 -3.500000 -28.491980
      vertex 29.834871 -3.500000 -28.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.309999 -3.500000 -27.400000
      vertex 30.184002 -3.500000 -26.888805
      vertex 30.278036 -3.500000 -27.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.278036 -3.500000 -27.663248
      vertex 30.184002 -3.500000 -26.888805
      vertex 30.309999 -3.500000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.184002 -3.500000 -27.911196
      vertex 30.184002 -3.500000 -26.888805
      vertex 30.278036 -3.500000 -27.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.834871 -3.500000 -28.305283
      vertex 30.184002 -3.500000 -26.888805
      vertex 30.184002 -3.500000 -27.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.184002 -3.500000 -26.888805
      vertex 29.834871 -3.500000 -26.494719
      vertex 30.033361 -3.500000 -26.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.834871 -3.500000 -28.305283
      vertex 29.834871 -3.500000 -26.494719
      vertex 30.184002 -3.500000 -26.888805
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.585129 -3.500000 -28.305283
      vertex 28.235998 -3.500000 -27.911196
      vertex 28.819935 -3.500000 -28.428518
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.386639 -3.500000 -28.129435
      vertex 28.235998 -3.500000 -27.911196
      vertex 28.585129 -3.500000 -28.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.342590 -3.500000 -28.491980
      vertex 29.600065 -3.500000 -26.371483
      vertex 29.834871 -3.500000 -28.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.834871 -3.500000 -28.305283
      vertex 29.600065 -3.500000 -26.371483
      vertex 29.834871 -3.500000 -26.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.342590 -3.500000 -28.491980
      vertex 29.342590 -3.500000 -26.308020
      vertex 29.600065 -3.500000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.077410 -3.500000 -28.491980
      vertex 29.077410 -3.500000 -26.308020
      vertex 29.342590 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.342590 -3.500000 -28.491980
      vertex 29.077410 -3.500000 -26.308020
      vertex 29.342590 -3.500000 -26.308020
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.819935 -3.500000 -28.428518
      vertex 28.819935 -3.500000 -26.371483
      vertex 29.077410 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.077410 -3.500000 -28.491980
      vertex 28.819935 -3.500000 -26.371483
      vertex 29.077410 -3.500000 -26.308020
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.141964 -3.500000 -27.136753
      vertex 28.235998 -3.500000 -26.888805
      vertex 28.110001 -3.500000 -27.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.141964 -3.500000 -27.663248
      vertex 28.235998 -3.500000 -26.888805
      vertex 28.235998 -3.500000 -27.911196
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.110001 -3.500000 -27.400000
      vertex 28.235998 -3.500000 -26.888805
      vertex 28.141964 -3.500000 -27.663248
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.235998 -3.500000 -27.911196
      vertex 28.585129 -3.500000 -26.494719
      vertex 28.819935 -3.500000 -28.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.819935 -3.500000 -28.428518
      vertex 28.585129 -3.500000 -26.494719
      vertex 28.819935 -3.500000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 28.235998 -3.500000 -27.911196
      vertex 28.386639 -3.500000 -26.670565
      vertex 28.585129 -3.500000 -26.494719
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.235998 -3.500000 -26.888805
      vertex 28.386639 -3.500000 -26.670565
      vertex 28.235998 -3.500000 -27.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 22.888805
      vertex -29.834871 -3.500000 22.494719
      vertex -30.033361 -3.500000 22.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.342590 -3.500000 22.308020
      vertex -29.600065 -3.500000 22.371483
      vertex -29.834871 -3.500000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 23.911196
      vertex -30.309999 -3.500000 23.400000
      vertex -30.278036 -3.500000 23.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 23.911196
      vertex -30.278036 -3.500000 23.136753
      vertex -30.309999 -3.500000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 23.911196
      vertex -30.184002 -3.500000 22.888805
      vertex -30.278036 -3.500000 23.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 23.911196
      vertex -29.834871 -3.500000 22.494719
      vertex -30.184002 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.834871 -3.500000 24.305283
      vertex -30.184002 -3.500000 23.911196
      vertex -30.033361 -3.500000 24.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.834871 -3.500000 24.305283
      vertex -29.834871 -3.500000 22.494719
      vertex -30.184002 -3.500000 23.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 22.888805
      vertex -28.585129 -3.500000 22.494719
      vertex -28.819935 -3.500000 22.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 22.888805
      vertex -28.386639 -3.500000 22.670565
      vertex -28.585129 -3.500000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.600065 -3.500000 24.428518
      vertex -29.342590 -3.500000 22.308020
      vertex -29.834871 -3.500000 22.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.600065 -3.500000 24.428518
      vertex -29.834871 -3.500000 22.494719
      vertex -29.834871 -3.500000 24.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.342590 -3.500000 24.491980
      vertex -29.342590 -3.500000 22.308020
      vertex -29.600065 -3.500000 24.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.077410 -3.500000 24.491980
      vertex -29.077410 -3.500000 22.308020
      vertex -29.342590 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.077410 -3.500000 24.491980
      vertex -29.342590 -3.500000 22.308020
      vertex -29.342590 -3.500000 24.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.819935 -3.500000 24.428518
      vertex -28.819935 -3.500000 22.371483
      vertex -29.077410 -3.500000 22.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.819935 -3.500000 24.428518
      vertex -29.077410 -3.500000 22.308020
      vertex -29.077410 -3.500000 24.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 23.911196
      vertex -28.141964 -3.500000 23.663248
      vertex -28.110001 -3.500000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 23.911196
      vertex -28.141964 -3.500000 23.136753
      vertex -28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 23.911196
      vertex -28.110001 -3.500000 23.400000
      vertex -28.141964 -3.500000 23.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.585129 -3.500000 24.305283
      vertex -28.235998 -3.500000 22.888805
      vertex -28.819935 -3.500000 22.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.585129 -3.500000 24.305283
      vertex -28.819935 -3.500000 22.371483
      vertex -28.819935 -3.500000 24.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.386639 -3.500000 24.129435
      vertex -28.235998 -3.500000 22.888805
      vertex -28.585129 -3.500000 24.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.386639 -3.500000 24.129435
      vertex -28.235998 -3.500000 23.911196
      vertex -28.235998 -3.500000 22.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 -27.911196
      vertex -29.834871 -3.500000 -28.305283
      vertex -30.033361 -3.500000 -28.129435
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.342590 -3.500000 -28.491980
      vertex -29.600065 -3.500000 -28.428518
      vertex -29.834871 -3.500000 -28.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 -26.888805
      vertex -30.309999 -3.500000 -27.400000
      vertex -30.278036 -3.500000 -27.136753
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 -26.888805
      vertex -30.278036 -3.500000 -27.663248
      vertex -30.309999 -3.500000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 -26.888805
      vertex -30.184002 -3.500000 -27.911196
      vertex -30.278036 -3.500000 -27.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.184002 -3.500000 -26.888805
      vertex -29.834871 -3.500000 -28.305283
      vertex -30.184002 -3.500000 -27.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.834871 -3.500000 -26.494719
      vertex -30.184002 -3.500000 -26.888805
      vertex -30.033361 -3.500000 -26.670565
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.834871 -3.500000 -26.494719
      vertex -29.834871 -3.500000 -28.305283
      vertex -30.184002 -3.500000 -26.888805
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 -27.911196
      vertex -28.585129 -3.500000 -28.305283
      vertex -28.819935 -3.500000 -28.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 -27.911196
      vertex -28.386639 -3.500000 -28.129435
      vertex -28.585129 -3.500000 -28.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.600065 -3.500000 -26.371483
      vertex -29.342590 -3.500000 -28.491980
      vertex -29.834871 -3.500000 -28.305283
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.600065 -3.500000 -26.371483
      vertex -29.834871 -3.500000 -28.305283
      vertex -29.834871 -3.500000 -26.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.342590 -3.500000 -26.308020
      vertex -29.342590 -3.500000 -28.491980
      vertex -29.600065 -3.500000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.077410 -3.500000 -26.308020
      vertex -29.077410 -3.500000 -28.491980
      vertex -29.342590 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.077410 -3.500000 -26.308020
      vertex -29.342590 -3.500000 -28.491980
      vertex -29.342590 -3.500000 -26.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.819935 -3.500000 -26.371483
      vertex -28.819935 -3.500000 -28.428518
      vertex -29.077410 -3.500000 -28.491980
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.819935 -3.500000 -26.371483
      vertex -29.077410 -3.500000 -28.491980
      vertex -29.077410 -3.500000 -26.308020
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 -26.888805
      vertex -28.141964 -3.500000 -27.136753
      vertex -28.110001 -3.500000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 -26.888805
      vertex -28.141964 -3.500000 -27.663248
      vertex -28.235998 -3.500000 -27.911196
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.235998 -3.500000 -26.888805
      vertex -28.110001 -3.500000 -27.400000
      vertex -28.141964 -3.500000 -27.663248
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.585129 -3.500000 -26.494719
      vertex -28.235998 -3.500000 -27.911196
      vertex -28.819935 -3.500000 -28.428518
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.585129 -3.500000 -26.494719
      vertex -28.819935 -3.500000 -28.428518
      vertex -28.819935 -3.500000 -26.371483
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.386639 -3.500000 -26.670565
      vertex -28.235998 -3.500000 -27.911196
      vertex -28.585129 -3.500000 -26.494719
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.386639 -3.500000 -26.670565
      vertex -28.235998 -3.500000 -26.888805
      vertex -28.235998 -3.500000 -27.911196
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120539
    outer loop
      vertex 32.963676 -5.000000 29.299145
      vertex 33.000000 -5.000000 29.000000
      vertex 33.000000 -8.000000 29.000000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 -0.120539
    outer loop
      vertex 32.963676 -5.000000 29.299145
      vertex 33.000000 -8.000000 29.000000
      vertex 32.963676 -8.000000 29.299145
    endloop
  endfacet
  facet normal -0.935016 -0.000000 -0.354605
    outer loop
      vertex 32.856819 -5.000000 29.580904
      vertex 32.963676 -8.000000 29.299145
      vertex 32.856819 -8.000000 29.580904
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex 32.856819 -5.000000 29.580904
      vertex 32.963676 -5.000000 29.299145
      vertex 32.963676 -8.000000 29.299145
    endloop
  endfacet
  facet normal -0.822985 -0.000000 -0.568063
    outer loop
      vertex 32.685638 -5.000000 29.828903
      vertex 32.856819 -8.000000 29.580904
      vertex 32.685638 -8.000000 29.828903
    endloop
  endfacet
  facet normal -0.822985 0.000000 -0.568063
    outer loop
      vertex 32.685638 -5.000000 29.828903
      vertex 32.856819 -5.000000 29.580904
      vertex 32.856819 -8.000000 29.580904
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748512
    outer loop
      vertex 32.460079 -5.000000 30.028730
      vertex 32.685638 -8.000000 29.828903
      vertex 32.460079 -8.000000 30.028730
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748512
    outer loop
      vertex 32.460079 -5.000000 30.028730
      vertex 32.685638 -5.000000 29.828903
      vertex 32.685638 -8.000000 29.828903
    endloop
  endfacet
  facet normal -0.239319 -0.000000 -0.970941
    outer loop
      vertex 32.193256 -5.000000 30.168770
      vertex 32.193256 -8.000000 30.168770
      vertex 31.900671 -8.000000 30.240887
    endloop
  endfacet
  facet normal -0.464723 -0.000000 -0.885456
    outer loop
      vertex 32.193256 -5.000000 30.168770
      vertex 32.460079 -8.000000 30.028730
      vertex 32.193256 -8.000000 30.168770
    endloop
  endfacet
  facet normal -0.464723 0.000000 -0.885456
    outer loop
      vertex 32.193256 -5.000000 30.168770
      vertex 32.460079 -5.000000 30.028730
      vertex 32.460079 -8.000000 30.028730
    endloop
  endfacet
  facet normal -0.239319 -0.000000 -0.970941
    outer loop
      vertex 31.900671 -5.000000 30.240887
      vertex 32.193256 -5.000000 30.168770
      vertex 31.900671 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 31.599329 -5.000000 30.240887
      vertex 31.900671 -8.000000 30.240887
      vertex 31.599329 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 31.599329 -5.000000 30.240887
      vertex 31.900671 -5.000000 30.240887
      vertex 31.900671 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.239319 0.000000 -0.970941
    outer loop
      vertex 31.306744 -5.000000 30.168770
      vertex 31.599329 -8.000000 30.240887
      vertex 31.306744 -8.000000 30.168770
    endloop
  endfacet
  facet normal 0.239319 -0.000000 -0.970941
    outer loop
      vertex 31.306744 -5.000000 30.168770
      vertex 31.599329 -5.000000 30.240887
      vertex 31.599329 -8.000000 30.240887
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex 31.039919 -5.000000 30.028730
      vertex 31.306744 -8.000000 30.168770
      vertex 31.039919 -8.000000 30.028730
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex 31.039919 -5.000000 30.028730
      vertex 31.306744 -5.000000 30.168770
      vertex 31.306744 -8.000000 30.168770
    endloop
  endfacet
  facet normal 0.822985 0.000000 -0.568063
    outer loop
      vertex 30.814362 -5.000000 29.828903
      vertex 30.814362 -8.000000 29.828903
      vertex 30.643181 -8.000000 29.580904
    endloop
  endfacet
  facet normal 0.663124 0.000000 -0.748509
    outer loop
      vertex 30.814362 -5.000000 29.828903
      vertex 31.039919 -8.000000 30.028730
      vertex 30.814362 -8.000000 29.828903
    endloop
  endfacet
  facet normal 0.663124 -0.000000 -0.748509
    outer loop
      vertex 30.814362 -5.000000 29.828903
      vertex 31.039919 -5.000000 30.028730
      vertex 31.039919 -8.000000 30.028730
    endloop
  endfacet
  facet normal 0.822985 0.000000 -0.568063
    outer loop
      vertex 30.643181 -5.000000 29.580904
      vertex 30.814362 -5.000000 29.828903
      vertex 30.643181 -8.000000 29.580904
    endloop
  endfacet
  facet normal 0.935016 -0.000000 -0.354605
    outer loop
      vertex 30.536324 -5.000000 29.299145
      vertex 30.643181 -5.000000 29.580904
      vertex 30.643181 -8.000000 29.580904
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex 30.536324 -5.000000 29.299145
      vertex 30.643181 -8.000000 29.580904
      vertex 30.536324 -8.000000 29.299145
    endloop
  endfacet
  facet normal 0.992709 -0.000000 -0.120539
    outer loop
      vertex 30.500000 -5.000000 29.000000
      vertex 30.536324 -5.000000 29.299145
      vertex 30.536324 -8.000000 29.299145
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120539
    outer loop
      vertex 30.500000 -5.000000 29.000000
      vertex 30.536324 -8.000000 29.299145
      vertex 30.500000 -8.000000 29.000000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex 30.536324 -5.000000 28.700855
      vertex 30.500000 -5.000000 29.000000
      vertex 30.500000 -8.000000 29.000000
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 30.536324 -5.000000 28.700855
      vertex 30.536324 -8.000000 28.700855
      vertex 30.643181 -8.000000 28.419096
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex 30.536324 -5.000000 28.700855
      vertex 30.500000 -8.000000 29.000000
      vertex 30.536324 -8.000000 28.700855
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 30.643181 -5.000000 28.419096
      vertex 30.536324 -5.000000 28.700855
      vertex 30.643181 -8.000000 28.419096
    endloop
  endfacet
  facet normal 0.822985 0.000000 0.568063
    outer loop
      vertex 30.643181 -5.000000 28.419096
      vertex 30.643181 -8.000000 28.419096
      vertex 30.814362 -8.000000 28.171097
    endloop
  endfacet
  facet normal 0.822985 0.000000 0.568063
    outer loop
      vertex 30.814362 -5.000000 28.171097
      vertex 30.643181 -5.000000 28.419096
      vertex 30.814362 -8.000000 28.171097
    endloop
  endfacet
  facet normal 0.663124 0.000000 0.748509
    outer loop
      vertex 30.814362 -5.000000 28.171097
      vertex 30.814362 -8.000000 28.171097
      vertex 31.039919 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.663124 0.000000 0.748509
    outer loop
      vertex 31.039919 -5.000000 27.971270
      vertex 30.814362 -5.000000 28.171097
      vertex 31.039919 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.464721 -0.000000 0.885457
    outer loop
      vertex 31.306744 -5.000000 27.831230
      vertex 31.039919 -5.000000 27.971270
      vertex 31.039919 -8.000000 27.971270
    endloop
  endfacet
  facet normal 0.464721 0.000000 0.885457
    outer loop
      vertex 31.306744 -5.000000 27.831230
      vertex 31.039919 -8.000000 27.971270
      vertex 31.306744 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex 31.599329 -5.000000 27.759113
      vertex 31.306744 -8.000000 27.831230
      vertex 31.599329 -8.000000 27.759113
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex 31.599329 -5.000000 27.759113
      vertex 31.306744 -5.000000 27.831230
      vertex 31.306744 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 31.900671 -5.000000 27.759113
      vertex 31.599329 -5.000000 27.759113
      vertex 31.599329 -8.000000 27.759113
    endloop
  endfacet
  facet normal -0.239319 0.000000 0.970941
    outer loop
      vertex 31.900671 -5.000000 27.759113
      vertex 31.900671 -8.000000 27.759113
      vertex 32.193256 -8.000000 27.831230
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 31.900671 -5.000000 27.759113
      vertex 31.599329 -8.000000 27.759113
      vertex 31.900671 -8.000000 27.759113
    endloop
  endfacet
  facet normal -0.239319 0.000000 0.970941
    outer loop
      vertex 32.193256 -5.000000 27.831230
      vertex 31.900671 -5.000000 27.759113
      vertex 32.193256 -8.000000 27.831230
    endloop
  endfacet
  facet normal -0.464723 0.000000 0.885456
    outer loop
      vertex 32.460079 -5.000000 27.971270
      vertex 32.193256 -8.000000 27.831230
      vertex 32.460079 -8.000000 27.971270
    endloop
  endfacet
  facet normal -0.464723 -0.000000 0.885456
    outer loop
      vertex 32.460079 -5.000000 27.971270
      vertex 32.193256 -5.000000 27.831230
      vertex 32.193256 -8.000000 27.831230
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex 32.685638 -5.000000 28.171097
      vertex 32.460079 -8.000000 27.971270
      vertex 32.685638 -8.000000 28.171097
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex 32.685638 -5.000000 28.171097
      vertex 32.460079 -5.000000 27.971270
      vertex 32.460079 -8.000000 27.971270
    endloop
  endfacet
  facet normal -0.822985 0.000000 0.568063
    outer loop
      vertex 32.856819 -5.000000 28.419096
      vertex 32.685638 -8.000000 28.171097
      vertex 32.856819 -8.000000 28.419096
    endloop
  endfacet
  facet normal -0.822985 -0.000000 0.568063
    outer loop
      vertex 32.856819 -5.000000 28.419096
      vertex 32.685638 -5.000000 28.171097
      vertex 32.685638 -8.000000 28.171097
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex 32.963676 -5.000000 28.700855
      vertex 32.856819 -8.000000 28.419096
      vertex 32.963676 -8.000000 28.700855
    endloop
  endfacet
  facet normal -0.935016 -0.000000 0.354605
    outer loop
      vertex 32.963676 -5.000000 28.700855
      vertex 32.856819 -5.000000 28.419096
      vertex 32.856819 -8.000000 28.419096
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120539
    outer loop
      vertex 33.000000 -5.000000 29.000000
      vertex 32.963676 -8.000000 28.700855
      vertex 33.000000 -8.000000 29.000000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 0.120539
    outer loop
      vertex 33.000000 -5.000000 29.000000
      vertex 32.963676 -5.000000 28.700855
      vertex 32.963676 -8.000000 28.700855
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex -25.000000 -9.000000 3.000000
      vertex 25.000000 -9.000000 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -25.000000 -7.000000 3.000000
      vertex 25.000000 -9.000000 3.000000
      vertex 25.000000 -7.000000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex -25.000000 -7.000000 -33.000000
      vertex -25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.000000 -7.000000 -33.000000
      vertex -25.000000 -9.000000 -33.000000
      vertex 25.000000 -9.000000 -33.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -25.000000 -9.000000 -11.000000
      vertex -25.000000 -7.000000 -11.000000
      vertex 25.000000 -7.000000 -11.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -25.000000 -9.000000 -11.000000
      vertex 25.000000 -7.000000 -11.000000
      vertex 25.000000 -9.000000 -11.000000
    endloop
  endfacet
endsolid Mesh

```

### Screen Cover

```stl
solid Mesh
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex -21.000000 -2.500000 -29.400000
      vertex -21.000000 -0.000000 -29.400000
      vertex -21.000000 0.000000 -24.400000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex -21.000000 -2.500000 -29.400000
      vertex -21.000000 0.000000 -24.400000
      vertex -21.000000 -2.500000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -31.209999 -0.000000 -24.400000
      vertex -31.209999 -2.500000 -24.400000
      vertex -21.000000 -2.500000 -24.400000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -31.209999 -0.000000 -24.400000
      vertex -21.000000 -2.500000 -24.400000
      vertex -21.000000 0.000000 -24.400000
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex -31.209999 0.000000 25.400000
      vertex -31.209999 -2.500000 20.400000
      vertex -31.209999 -3.000000 25.400000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -31.209999 0.000000 25.400000
      vertex -31.209999 0.000000 20.400000
      vertex -31.209999 -2.500000 20.400000
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex -31.209999 -2.500000 -24.400000
      vertex -31.209999 -3.000000 -29.400000
      vertex -31.209999 -2.500000 20.400000
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex -31.209999 -2.500000 20.400000
      vertex -31.209999 -3.000000 -29.400000
      vertex -31.209999 -3.000000 25.400000
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex -31.209999 -0.000000 -24.400000
      vertex -31.209999 -0.000000 -29.400000
      vertex -31.209999 -2.500000 -24.400000
    endloop
  endfacet
  facet normal -1.000000 0.000000 -0.000000
    outer loop
      vertex -31.209999 -2.500000 -24.400000
      vertex -31.209999 -0.000000 -29.400000
      vertex -31.209999 -3.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.209999 -2.500000 20.400000
      vertex -31.209999 0.000000 20.400000
      vertex -21.000000 0.000000 20.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.209999 -2.500000 20.400000
      vertex -21.000000 0.000000 20.400000
      vertex -21.000000 -2.500000 20.400000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex -21.000000 -2.500000 20.400000
      vertex -21.000000 0.000000 20.400000
      vertex -21.000000 0.000000 25.400000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex -21.000000 -2.500000 20.400000
      vertex -21.000000 0.000000 25.400000
      vertex -21.000000 -2.500000 25.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -29.920080 -0.000000 -28.428730
      vertex -31.209999 -0.000000 -29.400000
      vertex -30.145638 -0.000000 -28.228903
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -30.316820 -0.000000 -27.980904
      vertex -30.145638 -0.000000 -28.228903
      vertex -31.209999 -0.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.653255 -0.000000 -28.568769
      vertex -31.209999 -0.000000 -29.400000
      vertex -29.920080 -0.000000 -28.428730
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -30.423677 -0.000000 -27.699144
      vertex -30.316820 -0.000000 -27.980904
      vertex -31.209999 -0.000000 -29.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -29.360670 -0.000000 -28.640886
      vertex -31.209999 -0.000000 -29.400000
      vertex -29.653255 -0.000000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -30.459999 -0.000000 -27.400000
      vertex -30.423677 -0.000000 -27.699144
      vertex -31.209999 -0.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.059330 -0.000000 -28.640886
      vertex -31.209999 -0.000000 -29.400000
      vertex -29.360670 -0.000000 -28.640886
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 -0.000000 -24.400000
      vertex -29.653255 -0.000000 -26.231230
      vertex -29.920080 -0.000000 -26.371269
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 -0.000000 -24.400000
      vertex -29.920080 -0.000000 -26.371269
      vertex -30.145638 -0.000000 -26.571096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 -0.000000 -24.400000
      vertex -30.145638 -0.000000 -26.571096
      vertex -30.316820 -0.000000 -26.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 -0.000000 -24.400000
      vertex -30.316820 -0.000000 -26.819096
      vertex -30.423677 -0.000000 -27.100855
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 -0.000000 -24.400000
      vertex -30.423677 -0.000000 -27.100855
      vertex -30.459999 -0.000000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 -0.000000 -24.400000
      vertex -30.459999 -0.000000 -27.400000
      vertex -31.209999 -0.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.360670 -0.000000 -26.159115
      vertex -29.653255 -0.000000 -26.231230
      vertex -31.209999 -0.000000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.059330 -0.000000 -26.159115
      vertex -29.360670 -0.000000 -26.159115
      vertex -31.209999 -0.000000 -24.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -28.766745 -0.000000 -26.231230
      vertex -29.059330 -0.000000 -26.159115
      vertex -31.209999 -0.000000 -24.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 -0.000000 -29.400000
      vertex -28.766745 -0.000000 -28.568769
      vertex -28.499920 -0.000000 -28.428730
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 -0.000000 -29.400000
      vertex -28.499920 -0.000000 -28.428730
      vertex -28.274361 -0.000000 -28.228903
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 -0.000000 -29.400000
      vertex -28.274361 -0.000000 -28.228903
      vertex -28.103180 -0.000000 -27.980904
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 -0.000000 -29.400000
      vertex -28.103180 -0.000000 -27.980904
      vertex -27.996323 -0.000000 -27.699144
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 -0.000000 -29.400000
      vertex -27.996323 -0.000000 -27.699144
      vertex -27.959999 -0.000000 -27.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 -24.400000
      vertex -27.959999 -0.000000 -27.400000
      vertex -27.996323 -0.000000 -27.100855
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 -24.400000
      vertex -27.996323 -0.000000 -27.100855
      vertex -28.103180 -0.000000 -26.819096
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 -24.400000
      vertex -28.103180 -0.000000 -26.819096
      vertex -28.274361 -0.000000 -26.571096
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 -24.400000
      vertex -28.274361 -0.000000 -26.571096
      vertex -28.499920 -0.000000 -26.371269
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 -24.400000
      vertex -28.499920 -0.000000 -26.371269
      vertex -28.766745 -0.000000 -26.231230
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 -24.400000
      vertex -21.000000 -0.000000 -29.400000
      vertex -27.959999 -0.000000 -27.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 -24.400000
      vertex -28.766745 -0.000000 -26.231230
      vertex -31.209999 -0.000000 -24.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 -0.000000 -29.400000
      vertex -31.209999 -0.000000 -29.400000
      vertex -29.059330 -0.000000 -28.640886
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 -0.000000 -29.400000
      vertex -29.059330 -0.000000 -28.640886
      vertex -28.766745 -0.000000 -28.568769
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -29.920080 0.000000 22.371269
      vertex -31.209999 0.000000 20.400000
      vertex -30.145638 0.000000 22.571096
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -30.316820 0.000000 22.819096
      vertex -30.145638 0.000000 22.571096
      vertex -31.209999 0.000000 20.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -29.653255 0.000000 22.231230
      vertex -31.209999 0.000000 20.400000
      vertex -29.920080 0.000000 22.371269
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -30.423677 0.000000 23.100855
      vertex -30.316820 0.000000 22.819096
      vertex -31.209999 0.000000 20.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -29.360670 0.000000 22.159115
      vertex -31.209999 0.000000 20.400000
      vertex -29.653255 0.000000 22.231230
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -30.459999 0.000000 23.400000
      vertex -30.423677 0.000000 23.100855
      vertex -31.209999 0.000000 20.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.059330 0.000000 22.159115
      vertex -31.209999 0.000000 20.400000
      vertex -29.360670 0.000000 22.159115
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -28.766745 0.000000 22.231230
      vertex -31.209999 0.000000 20.400000
      vertex -29.059330 0.000000 22.159115
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 0.000000 25.400000
      vertex -30.145638 0.000000 24.228903
      vertex -30.316820 0.000000 23.980904
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 0.000000 25.400000
      vertex -30.316820 0.000000 23.980904
      vertex -30.423677 0.000000 23.699144
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 0.000000 25.400000
      vertex -30.423677 0.000000 23.699144
      vertex -30.459999 0.000000 23.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -31.209999 0.000000 25.400000
      vertex -30.459999 0.000000 23.400000
      vertex -31.209999 0.000000 20.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -29.920080 0.000000 24.428730
      vertex -30.145638 0.000000 24.228903
      vertex -31.209999 0.000000 25.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.653255 0.000000 24.568769
      vertex -29.920080 0.000000 24.428730
      vertex -31.209999 0.000000 25.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex -29.360670 0.000000 24.640886
      vertex -29.653255 0.000000 24.568769
      vertex -31.209999 0.000000 25.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -29.059330 0.000000 24.640886
      vertex -29.360670 0.000000 24.640886
      vertex -31.209999 0.000000 25.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 20.400000
      vertex -28.766745 0.000000 22.231230
      vertex -28.499920 0.000000 22.371269
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 20.400000
      vertex -28.499920 0.000000 22.371269
      vertex -28.274361 0.000000 22.571096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 20.400000
      vertex -28.274361 0.000000 22.571096
      vertex -28.103180 0.000000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 20.400000
      vertex -28.103180 0.000000 22.819096
      vertex -27.996323 0.000000 23.100855
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 20.400000
      vertex -27.996323 0.000000 23.100855
      vertex -27.959999 0.000000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 20.400000
      vertex -31.209999 0.000000 20.400000
      vertex -28.766745 0.000000 22.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 25.400000
      vertex -27.959999 0.000000 23.400000
      vertex -27.996323 0.000000 23.699144
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 25.400000
      vertex -27.996323 0.000000 23.699144
      vertex -28.103180 0.000000 23.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 0.000000 25.400000
      vertex -28.103180 0.000000 23.980904
      vertex -28.274361 0.000000 24.228903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 0.000000 25.400000
      vertex -28.274361 0.000000 24.228903
      vertex -28.499920 0.000000 24.428730
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 0.000000 25.400000
      vertex -28.499920 0.000000 24.428730
      vertex -28.766745 0.000000 24.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex -21.000000 0.000000 25.400000
      vertex -21.000000 0.000000 20.400000
      vertex -27.959999 0.000000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.209999 0.000000 25.400000
      vertex -21.000000 0.000000 25.400000
      vertex -29.059330 0.000000 24.640886
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.059330 0.000000 24.640886
      vertex -21.000000 0.000000 25.400000
      vertex -28.766745 0.000000 24.568769
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120539
    outer loop
      vertex -27.996323 -0.000000 -27.100855
      vertex -27.959999 -0.000000 -27.400000
      vertex -27.959999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 -0.120539
    outer loop
      vertex -27.996323 -0.000000 -27.100855
      vertex -27.959999 -2.500000 -27.400000
      vertex -27.996323 -2.500000 -27.100855
    endloop
  endfacet
  facet normal -0.935016 -0.000000 -0.354605
    outer loop
      vertex -28.103180 -0.000000 -26.819096
      vertex -27.996323 -2.500000 -27.100855
      vertex -28.103180 -2.500000 -26.819096
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex -28.103180 -0.000000 -26.819096
      vertex -27.996323 -0.000000 -27.100855
      vertex -27.996323 -2.500000 -27.100855
    endloop
  endfacet
  facet normal -0.822985 -0.000000 -0.568063
    outer loop
      vertex -28.274361 -0.000000 -26.571096
      vertex -28.103180 -2.500000 -26.819096
      vertex -28.274361 -2.500000 -26.571096
    endloop
  endfacet
  facet normal -0.822985 0.000000 -0.568063
    outer loop
      vertex -28.274361 -0.000000 -26.571096
      vertex -28.103180 -0.000000 -26.819096
      vertex -28.103180 -2.500000 -26.819096
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748512
    outer loop
      vertex -28.499920 -0.000000 -26.371269
      vertex -28.274361 -2.500000 -26.571096
      vertex -28.499920 -2.500000 -26.371269
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748512
    outer loop
      vertex -28.499920 -0.000000 -26.371269
      vertex -28.274361 -0.000000 -26.571096
      vertex -28.274361 -2.500000 -26.571096
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex -28.766745 -0.000000 -26.231230
      vertex -28.499920 -2.500000 -26.371269
      vertex -28.766745 -2.500000 -26.231230
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex -28.766745 -0.000000 -26.231230
      vertex -28.499920 -0.000000 -26.371269
      vertex -28.499920 -2.500000 -26.371269
    endloop
  endfacet
  facet normal -0.239313 -0.000000 -0.970942
    outer loop
      vertex -29.059330 -0.000000 -26.159115
      vertex -28.766745 -2.500000 -26.231230
      vertex -29.059330 -2.500000 -26.159115
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -29.059330 -0.000000 -26.159115
      vertex -29.059330 -2.500000 -26.159115
      vertex -29.360670 -2.500000 -26.159115
    endloop
  endfacet
  facet normal -0.239313 -0.000000 -0.970942
    outer loop
      vertex -29.059330 -0.000000 -26.159115
      vertex -28.766745 -0.000000 -26.231230
      vertex -28.766745 -2.500000 -26.231230
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -29.360670 -0.000000 -26.159115
      vertex -29.059330 -0.000000 -26.159115
      vertex -29.360670 -2.500000 -26.159115
    endloop
  endfacet
  facet normal 0.239313 0.000000 -0.970942
    outer loop
      vertex -29.653255 -0.000000 -26.231230
      vertex -29.360670 -2.500000 -26.159115
      vertex -29.653255 -2.500000 -26.231230
    endloop
  endfacet
  facet normal 0.239313 0.000000 -0.970942
    outer loop
      vertex -29.653255 -0.000000 -26.231230
      vertex -29.360670 -0.000000 -26.159115
      vertex -29.360670 -2.500000 -26.159115
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex -29.920080 -0.000000 -26.371269
      vertex -29.653255 -2.500000 -26.231230
      vertex -29.920080 -2.500000 -26.371269
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex -29.920080 -0.000000 -26.371269
      vertex -29.653255 -0.000000 -26.231230
      vertex -29.653255 -2.500000 -26.231230
    endloop
  endfacet
  facet normal 0.663124 0.000000 -0.748509
    outer loop
      vertex -30.145638 -0.000000 -26.571096
      vertex -29.920080 -2.500000 -26.371269
      vertex -30.145638 -2.500000 -26.571096
    endloop
  endfacet
  facet normal 0.663124 -0.000000 -0.748509
    outer loop
      vertex -30.145638 -0.000000 -26.571096
      vertex -29.920080 -0.000000 -26.371269
      vertex -29.920080 -2.500000 -26.371269
    endloop
  endfacet
  facet normal 0.822982 0.000000 -0.568067
    outer loop
      vertex -30.316820 -0.000000 -26.819096
      vertex -30.145638 -2.500000 -26.571096
      vertex -30.316820 -2.500000 -26.819096
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex -30.316820 -0.000000 -26.819096
      vertex -30.316820 -2.500000 -26.819096
      vertex -30.423677 -2.500000 -27.100855
    endloop
  endfacet
  facet normal 0.822982 -0.000000 -0.568067
    outer loop
      vertex -30.316820 -0.000000 -26.819096
      vertex -30.145638 -0.000000 -26.571096
      vertex -30.145638 -2.500000 -26.571096
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex -30.423677 -0.000000 -27.100855
      vertex -30.316820 -0.000000 -26.819096
      vertex -30.423677 -2.500000 -27.100855
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120533
    outer loop
      vertex -30.423677 -0.000000 -27.100855
      vertex -30.423677 -2.500000 -27.100855
      vertex -30.459999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120533
    outer loop
      vertex -30.459999 -0.000000 -27.400000
      vertex -30.423677 -0.000000 -27.100855
      vertex -30.459999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120533
    outer loop
      vertex -30.423677 -0.000000 -27.699144
      vertex -30.459999 -2.500000 -27.400000
      vertex -30.423677 -2.500000 -27.699144
    endloop
  endfacet
  facet normal 0.992709 -0.000000 0.120533
    outer loop
      vertex -30.423677 -0.000000 -27.699144
      vertex -30.459999 -0.000000 -27.400000
      vertex -30.459999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex -30.316820 -0.000000 -27.980904
      vertex -30.423677 -2.500000 -27.699144
      vertex -30.316820 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex -30.316820 -0.000000 -27.980904
      vertex -30.423677 -0.000000 -27.699144
      vertex -30.423677 -2.500000 -27.699144
    endloop
  endfacet
  facet normal 0.822982 0.000000 0.568067
    outer loop
      vertex -30.145638 -0.000000 -28.228903
      vertex -30.316820 -2.500000 -27.980904
      vertex -30.145638 -2.500000 -28.228903
    endloop
  endfacet
  facet normal 0.822982 0.000000 0.568067
    outer loop
      vertex -30.145638 -0.000000 -28.228903
      vertex -30.316820 -0.000000 -27.980904
      vertex -30.316820 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.663124 0.000000 0.748509
    outer loop
      vertex -29.920080 -0.000000 -28.428730
      vertex -30.145638 -2.500000 -28.228903
      vertex -29.920080 -2.500000 -28.428730
    endloop
  endfacet
  facet normal 0.663124 0.000000 0.748509
    outer loop
      vertex -29.920080 -0.000000 -28.428730
      vertex -30.145638 -0.000000 -28.228903
      vertex -30.145638 -2.500000 -28.228903
    endloop
  endfacet
  facet normal 0.464721 0.000000 0.885457
    outer loop
      vertex -29.653255 -0.000000 -28.568769
      vertex -29.920080 -2.500000 -28.428730
      vertex -29.653255 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.464721 -0.000000 0.885457
    outer loop
      vertex -29.653255 -0.000000 -28.568769
      vertex -29.920080 -0.000000 -28.428730
      vertex -29.920080 -2.500000 -28.428730
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex -29.360670 -0.000000 -28.640886
      vertex -29.653255 -2.500000 -28.568769
      vertex -29.360670 -2.500000 -28.640886
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex -29.360670 -0.000000 -28.640886
      vertex -29.653255 -0.000000 -28.568769
      vertex -29.653255 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -29.059330 -0.000000 -28.640886
      vertex -29.360670 -2.500000 -28.640886
      vertex -29.059330 -2.500000 -28.640886
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -29.059330 -0.000000 -28.640886
      vertex -29.360670 -0.000000 -28.640886
      vertex -29.360670 -2.500000 -28.640886
    endloop
  endfacet
  facet normal -0.239319 0.000000 0.970941
    outer loop
      vertex -28.766745 -0.000000 -28.568769
      vertex -29.059330 -2.500000 -28.640886
      vertex -28.766745 -2.500000 -28.568769
    endloop
  endfacet
  facet normal -0.239319 -0.000000 0.970941
    outer loop
      vertex -28.766745 -0.000000 -28.568769
      vertex -29.059330 -0.000000 -28.640886
      vertex -29.059330 -2.500000 -28.640886
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex -28.499920 -0.000000 -28.428730
      vertex -28.766745 -2.500000 -28.568769
      vertex -28.499920 -2.500000 -28.428730
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex -28.499920 -0.000000 -28.428730
      vertex -28.499920 -2.500000 -28.428730
      vertex -28.274361 -2.500000 -28.228903
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex -28.499920 -0.000000 -28.428730
      vertex -28.766745 -0.000000 -28.568769
      vertex -28.766745 -2.500000 -28.568769
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex -28.274361 -0.000000 -28.228903
      vertex -28.499920 -0.000000 -28.428730
      vertex -28.274361 -2.500000 -28.228903
    endloop
  endfacet
  facet normal -0.822985 0.000000 0.568063
    outer loop
      vertex -28.103180 -0.000000 -27.980904
      vertex -28.274361 -2.500000 -28.228903
      vertex -28.103180 -2.500000 -27.980904
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex -28.103180 -0.000000 -27.980904
      vertex -28.103180 -2.500000 -27.980904
      vertex -27.996323 -2.500000 -27.699144
    endloop
  endfacet
  facet normal -0.822985 -0.000000 0.568063
    outer loop
      vertex -28.103180 -0.000000 -27.980904
      vertex -28.274361 -0.000000 -28.228903
      vertex -28.274361 -2.500000 -28.228903
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex -27.996323 -0.000000 -27.699144
      vertex -28.103180 -0.000000 -27.980904
      vertex -27.996323 -2.500000 -27.699144
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120539
    outer loop
      vertex -27.959999 -0.000000 -27.400000
      vertex -27.996323 -2.500000 -27.699144
      vertex -27.959999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 0.120539
    outer loop
      vertex -27.959999 -0.000000 -27.400000
      vertex -27.996323 -0.000000 -27.699144
      vertex -27.996323 -2.500000 -27.699144
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120539
    outer loop
      vertex -27.996323 0.000000 23.699144
      vertex -27.959999 0.000000 23.400000
      vertex -27.959999 -2.500000 23.400000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 -0.120539
    outer loop
      vertex -27.996323 0.000000 23.699144
      vertex -27.959999 -2.500000 23.400000
      vertex -27.996323 -2.500000 23.699144
    endloop
  endfacet
  facet normal -0.935016 -0.000000 -0.354605
    outer loop
      vertex -28.103180 0.000000 23.980904
      vertex -27.996323 -2.500000 23.699144
      vertex -28.103180 -2.500000 23.980904
    endloop
  endfacet
  facet normal -0.822985 -0.000000 -0.568063
    outer loop
      vertex -28.103180 0.000000 23.980904
      vertex -28.103180 -2.500000 23.980904
      vertex -28.274361 -2.500000 24.228903
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex -28.103180 0.000000 23.980904
      vertex -27.996323 0.000000 23.699144
      vertex -27.996323 -2.500000 23.699144
    endloop
  endfacet
  facet normal -0.822985 -0.000000 -0.568063
    outer loop
      vertex -28.274361 0.000000 24.228903
      vertex -28.103180 0.000000 23.980904
      vertex -28.274361 -2.500000 24.228903
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748512
    outer loop
      vertex -28.499920 0.000000 24.428730
      vertex -28.274361 -2.500000 24.228903
      vertex -28.499920 -2.500000 24.428730
    endloop
  endfacet
  facet normal -0.663121 -0.000000 -0.748512
    outer loop
      vertex -28.499920 0.000000 24.428730
      vertex -28.274361 0.000000 24.228903
      vertex -28.274361 -2.500000 24.228903
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex -28.766745 0.000000 24.568769
      vertex -28.499920 -2.500000 24.428730
      vertex -28.766745 -2.500000 24.568769
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex -28.766745 0.000000 24.568769
      vertex -28.499920 0.000000 24.428730
      vertex -28.499920 -2.500000 24.428730
    endloop
  endfacet
  facet normal -0.239319 -0.000000 -0.970941
    outer loop
      vertex -29.059330 0.000000 24.640886
      vertex -28.766745 -2.500000 24.568769
      vertex -29.059330 -2.500000 24.640886
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -29.059330 0.000000 24.640886
      vertex -29.059330 -2.500000 24.640886
      vertex -29.360670 -2.500000 24.640886
    endloop
  endfacet
  facet normal -0.239319 0.000000 -0.970941
    outer loop
      vertex -29.059330 0.000000 24.640886
      vertex -28.766745 0.000000 24.568769
      vertex -28.766745 -2.500000 24.568769
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -29.360670 0.000000 24.640886
      vertex -29.059330 0.000000 24.640886
      vertex -29.360670 -2.500000 24.640886
    endloop
  endfacet
  facet normal 0.239319 0.000000 -0.970941
    outer loop
      vertex -29.653255 0.000000 24.568769
      vertex -29.360670 -2.500000 24.640886
      vertex -29.653255 -2.500000 24.568769
    endloop
  endfacet
  facet normal 0.239319 -0.000000 -0.970941
    outer loop
      vertex -29.653255 0.000000 24.568769
      vertex -29.360670 0.000000 24.640886
      vertex -29.360670 -2.500000 24.640886
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex -29.920080 0.000000 24.428730
      vertex -29.653255 -2.500000 24.568769
      vertex -29.920080 -2.500000 24.428730
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex -29.920080 0.000000 24.428730
      vertex -29.653255 0.000000 24.568769
      vertex -29.653255 -2.500000 24.568769
    endloop
  endfacet
  facet normal 0.663124 0.000000 -0.748509
    outer loop
      vertex -30.145638 0.000000 24.228903
      vertex -29.920080 -2.500000 24.428730
      vertex -30.145638 -2.500000 24.228903
    endloop
  endfacet
  facet normal 0.663124 -0.000000 -0.748509
    outer loop
      vertex -30.145638 0.000000 24.228903
      vertex -29.920080 0.000000 24.428730
      vertex -29.920080 -2.500000 24.428730
    endloop
  endfacet
  facet normal 0.822982 0.000000 -0.568067
    outer loop
      vertex -30.316820 0.000000 23.980904
      vertex -30.145638 -2.500000 24.228903
      vertex -30.316820 -2.500000 23.980904
    endloop
  endfacet
  facet normal 0.822982 -0.000000 -0.568067
    outer loop
      vertex -30.316820 0.000000 23.980904
      vertex -30.145638 0.000000 24.228903
      vertex -30.145638 -2.500000 24.228903
    endloop
  endfacet
  facet normal 0.935016 -0.000000 -0.354605
    outer loop
      vertex -30.423677 0.000000 23.699144
      vertex -30.316820 0.000000 23.980904
      vertex -30.316820 -2.500000 23.980904
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex -30.423677 0.000000 23.699144
      vertex -30.316820 -2.500000 23.980904
      vertex -30.423677 -2.500000 23.699144
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120533
    outer loop
      vertex -30.423677 0.000000 23.699144
      vertex -30.423677 -2.500000 23.699144
      vertex -30.459999 -2.500000 23.400000
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120533
    outer loop
      vertex -30.459999 0.000000 23.400000
      vertex -30.423677 0.000000 23.699144
      vertex -30.459999 -2.500000 23.400000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120533
    outer loop
      vertex -30.423677 0.000000 23.100855
      vertex -30.459999 -2.500000 23.400000
      vertex -30.423677 -2.500000 23.100855
    endloop
  endfacet
  facet normal 0.992709 -0.000000 0.120533
    outer loop
      vertex -30.423677 0.000000 23.100855
      vertex -30.459999 0.000000 23.400000
      vertex -30.459999 -2.500000 23.400000
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex -30.316820 0.000000 22.819096
      vertex -30.423677 -2.500000 23.100855
      vertex -30.316820 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex -30.316820 0.000000 22.819096
      vertex -30.423677 0.000000 23.100855
      vertex -30.423677 -2.500000 23.100855
    endloop
  endfacet
  facet normal 0.822982 0.000000 0.568067
    outer loop
      vertex -30.145638 0.000000 22.571096
      vertex -30.316820 -2.500000 22.819096
      vertex -30.145638 -2.500000 22.571096
    endloop
  endfacet
  facet normal 0.822982 0.000000 0.568067
    outer loop
      vertex -30.145638 0.000000 22.571096
      vertex -30.316820 0.000000 22.819096
      vertex -30.316820 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.663124 0.000000 0.748509
    outer loop
      vertex -29.920080 0.000000 22.371269
      vertex -30.145638 -2.500000 22.571096
      vertex -29.920080 -2.500000 22.371269
    endloop
  endfacet
  facet normal 0.663124 0.000000 0.748509
    outer loop
      vertex -29.920080 0.000000 22.371269
      vertex -30.145638 0.000000 22.571096
      vertex -30.145638 -2.500000 22.571096
    endloop
  endfacet
  facet normal 0.464721 0.000000 0.885457
    outer loop
      vertex -29.653255 0.000000 22.231230
      vertex -29.920080 -2.500000 22.371269
      vertex -29.653255 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.464721 -0.000000 0.885457
    outer loop
      vertex -29.653255 0.000000 22.231230
      vertex -29.920080 0.000000 22.371269
      vertex -29.920080 -2.500000 22.371269
    endloop
  endfacet
  facet normal 0.239313 0.000000 0.970942
    outer loop
      vertex -29.360670 0.000000 22.159115
      vertex -29.653255 -2.500000 22.231230
      vertex -29.360670 -2.500000 22.159115
    endloop
  endfacet
  facet normal 0.239313 -0.000000 0.970942
    outer loop
      vertex -29.360670 0.000000 22.159115
      vertex -29.653255 0.000000 22.231230
      vertex -29.653255 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -29.059330 0.000000 22.159115
      vertex -29.360670 -2.500000 22.159115
      vertex -29.059330 -2.500000 22.159115
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -29.059330 0.000000 22.159115
      vertex -29.360670 0.000000 22.159115
      vertex -29.360670 -2.500000 22.159115
    endloop
  endfacet
  facet normal -0.239313 0.000000 0.970942
    outer loop
      vertex -28.766745 0.000000 22.231230
      vertex -29.059330 -2.500000 22.159115
      vertex -28.766745 -2.500000 22.231230
    endloop
  endfacet
  facet normal -0.239313 0.000000 0.970942
    outer loop
      vertex -28.766745 0.000000 22.231230
      vertex -29.059330 0.000000 22.159115
      vertex -29.059330 -2.500000 22.159115
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex -28.499920 0.000000 22.371269
      vertex -28.766745 -2.500000 22.231230
      vertex -28.499920 -2.500000 22.371269
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex -28.499920 0.000000 22.371269
      vertex -28.766745 0.000000 22.231230
      vertex -28.766745 -2.500000 22.231230
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex -28.274361 0.000000 22.571096
      vertex -28.499920 -2.500000 22.371269
      vertex -28.274361 -2.500000 22.571096
    endloop
  endfacet
  facet normal -0.663121 0.000000 0.748512
    outer loop
      vertex -28.274361 0.000000 22.571096
      vertex -28.499920 0.000000 22.371269
      vertex -28.499920 -2.500000 22.371269
    endloop
  endfacet
  facet normal -0.822985 0.000000 0.568063
    outer loop
      vertex -28.103180 0.000000 22.819096
      vertex -28.274361 -2.500000 22.571096
      vertex -28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal -0.822985 -0.000000 0.568063
    outer loop
      vertex -28.103180 0.000000 22.819096
      vertex -28.274361 0.000000 22.571096
      vertex -28.274361 -2.500000 22.571096
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex -27.996323 0.000000 23.100855
      vertex -28.103180 -2.500000 22.819096
      vertex -27.996323 -2.500000 23.100855
    endloop
  endfacet
  facet normal -0.935016 -0.000000 0.354605
    outer loop
      vertex -27.996323 0.000000 23.100855
      vertex -28.103180 0.000000 22.819096
      vertex -28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120539
    outer loop
      vertex -27.959999 0.000000 23.400000
      vertex -27.996323 -2.500000 23.100855
      vertex -27.959999 -2.500000 23.400000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 0.120539
    outer loop
      vertex -27.959999 0.000000 23.400000
      vertex -27.996323 0.000000 23.100855
      vertex -27.996323 -2.500000 23.100855
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.653255 -2.500000 -28.568769
      vertex -30.145638 -2.500000 -28.228903
      vertex -30.316820 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.653255 -2.500000 -28.568769
      vertex -29.920080 -2.500000 -28.428730
      vertex -30.145638 -2.500000 -28.228903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.459999 -2.500000 -27.400000
      vertex -30.316820 -2.500000 -27.980904
      vertex -30.423677 -2.500000 -27.699144
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.059330 -2.500000 -28.640886
      vertex -29.360670 -2.500000 -28.640886
      vertex -29.653255 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.145638 -2.500000 -26.571096
      vertex -30.423677 -2.500000 -27.100855
      vertex -30.316820 -2.500000 -26.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.145638 -2.500000 -26.571096
      vertex -30.459999 -2.500000 -27.400000
      vertex -30.423677 -2.500000 -27.100855
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.145638 -2.500000 -26.571096
      vertex -30.316820 -2.500000 -27.980904
      vertex -30.459999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.920080 -2.500000 -26.371269
      vertex -29.653255 -2.500000 -28.568769
      vertex -30.316820 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.920080 -2.500000 -26.371269
      vertex -30.316820 -2.500000 -27.980904
      vertex -30.145638 -2.500000 -26.571096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.103180 -2.500000 -27.980904
      vertex -28.499920 -2.500000 -28.428730
      vertex -28.766745 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.103180 -2.500000 -27.980904
      vertex -28.274361 -2.500000 -28.228903
      vertex -28.499920 -2.500000 -28.428730
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.360670 -2.500000 -26.159115
      vertex -29.920080 -2.500000 -26.371269
      vertex -29.653255 -2.500000 -26.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.360670 -2.500000 -26.159115
      vertex -29.653255 -2.500000 -28.568769
      vertex -29.920080 -2.500000 -26.371269
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -27.959999 -2.500000 -27.400000
      vertex -27.996323 -2.500000 -27.699144
      vertex -28.103180 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.059330 -2.500000 -26.159115
      vertex -28.766745 -2.500000 -28.568769
      vertex -29.059330 -2.500000 -28.640886
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.059330 -2.500000 -26.159115
      vertex -29.059330 -2.500000 -28.640886
      vertex -29.653255 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.059330 -2.500000 -26.159115
      vertex -29.653255 -2.500000 -28.568769
      vertex -29.360670 -2.500000 -26.159115
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.103180 -2.500000 -26.819096
      vertex -27.996323 -2.500000 -27.100855
      vertex -27.959999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.103180 -2.500000 -26.819096
      vertex -27.959999 -2.500000 -27.400000
      vertex -28.103180 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.499920 -2.500000 -26.371269
      vertex -29.059330 -2.500000 -26.159115
      vertex -28.766745 -2.500000 -26.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.499920 -2.500000 -26.371269
      vertex -28.766745 -2.500000 -28.568769
      vertex -29.059330 -2.500000 -26.159115
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.274361 -2.500000 -26.571096
      vertex -28.103180 -2.500000 -27.980904
      vertex -28.766745 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.274361 -2.500000 -26.571096
      vertex -28.103180 -2.500000 -26.819096
      vertex -28.103180 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.274361 -2.500000 -26.571096
      vertex -28.766745 -2.500000 -28.568769
      vertex -28.499920 -2.500000 -26.371269
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.653255 -2.500000 22.231230
      vertex -30.145638 -2.500000 22.571096
      vertex -30.316820 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.653255 -2.500000 22.231230
      vertex -29.920080 -2.500000 22.371269
      vertex -30.145638 -2.500000 22.571096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.459999 -2.500000 23.400000
      vertex -30.316820 -2.500000 22.819096
      vertex -30.423677 -2.500000 23.100855
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.059330 -2.500000 22.159115
      vertex -29.360670 -2.500000 22.159115
      vertex -29.653255 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.145638 -2.500000 24.228903
      vertex -30.423677 -2.500000 23.699144
      vertex -30.316820 -2.500000 23.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.145638 -2.500000 24.228903
      vertex -30.459999 -2.500000 23.400000
      vertex -30.423677 -2.500000 23.699144
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -30.145638 -2.500000 24.228903
      vertex -30.316820 -2.500000 22.819096
      vertex -30.459999 -2.500000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.920080 -2.500000 24.428730
      vertex -29.653255 -2.500000 22.231230
      vertex -30.316820 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.920080 -2.500000 24.428730
      vertex -30.316820 -2.500000 22.819096
      vertex -30.145638 -2.500000 24.228903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.103180 -2.500000 22.819096
      vertex -28.499920 -2.500000 22.371269
      vertex -28.766745 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.103180 -2.500000 22.819096
      vertex -28.274361 -2.500000 22.571096
      vertex -28.499920 -2.500000 22.371269
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.360670 -2.500000 24.640886
      vertex -29.920080 -2.500000 24.428730
      vertex -29.653255 -2.500000 24.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.360670 -2.500000 24.640886
      vertex -29.653255 -2.500000 22.231230
      vertex -29.920080 -2.500000 24.428730
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -27.959999 -2.500000 23.400000
      vertex -27.996323 -2.500000 23.100855
      vertex -28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.059330 -2.500000 24.640886
      vertex -28.766745 -2.500000 22.231230
      vertex -29.059330 -2.500000 22.159115
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.059330 -2.500000 24.640886
      vertex -29.059330 -2.500000 22.159115
      vertex -29.653255 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.059330 -2.500000 24.640886
      vertex -29.653255 -2.500000 22.231230
      vertex -29.360670 -2.500000 24.640886
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.103180 -2.500000 23.980904
      vertex -27.996323 -2.500000 23.699144
      vertex -27.959999 -2.500000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.103180 -2.500000 23.980904
      vertex -27.959999 -2.500000 23.400000
      vertex -28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.499920 -2.500000 24.428730
      vertex -29.059330 -2.500000 24.640886
      vertex -28.766745 -2.500000 24.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.499920 -2.500000 24.428730
      vertex -28.766745 -2.500000 22.231230
      vertex -29.059330 -2.500000 24.640886
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.274361 -2.500000 24.228903
      vertex -28.103180 -2.500000 22.819096
      vertex -28.766745 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.274361 -2.500000 24.228903
      vertex -28.103180 -2.500000 23.980904
      vertex -28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -28.274361 -2.500000 24.228903
      vertex -28.766745 -2.500000 22.231230
      vertex -28.499920 -2.500000 24.428730
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 -2.500000 -24.400000
      vertex -31.209999 -2.500000 -24.400000
      vertex -29.209999 -2.500000 -18.900000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.209999 -2.500000 20.400000
      vertex -29.209999 -2.500000 17.900000
      vertex -29.209999 -2.500000 -18.900000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -31.209999 -2.500000 20.400000
      vertex -29.209999 -2.500000 -18.900000
      vertex -31.209999 -2.500000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 21.000000 -2.500000 -29.400000
      vertex -21.000000 -2.500000 -29.400000
      vertex -21.000000 -2.500000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 21.000000 -2.500000 -24.400000
      vertex 21.000000 -2.500000 -29.400000
      vertex -21.000000 -2.500000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -21.000000 -2.500000 20.400000
      vertex -29.209999 -2.500000 17.900000
      vertex -31.209999 -2.500000 20.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.209999 -2.500000 -18.900000
      vertex 31.209999 -2.500000 -24.400000
      vertex 21.000000 -2.500000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 21.000000 -2.500000 25.400000
      vertex -21.000000 -2.500000 20.400000
      vertex -21.000000 -2.500000 25.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 21.000000 -2.500000 25.400000
      vertex 21.000000 -2.500000 20.400000
      vertex -21.000000 -2.500000 20.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 31.209999 -2.500000 20.400000
      vertex 29.209999 -2.500000 -18.900000
      vertex 29.209999 -2.500000 17.900000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 31.209999 -2.500000 20.400000
      vertex 29.209999 -2.500000 17.900000
      vertex 21.000000 -2.500000 20.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 31.209999 -2.500000 20.400000
      vertex 31.209999 -2.500000 -24.400000
      vertex 29.209999 -2.500000 -18.900000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -29.209999 -2.500000 -18.900000
      vertex 29.209999 -2.500000 -18.900000
      vertex 21.000000 -2.500000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -29.209999 -2.500000 -18.900000
      vertex 21.000000 -2.500000 -24.400000
      vertex -21.000000 -2.500000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.209999 -2.500000 17.900000
      vertex -29.209999 -2.500000 17.900000
      vertex 21.000000 -2.500000 20.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 21.000000 -2.500000 20.400000
      vertex -29.209999 -2.500000 17.900000
      vertex -21.000000 -2.500000 20.400000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 21.000000 -0.000000 -29.400000
      vertex 21.000000 -2.500000 -29.400000
      vertex 21.000000 -0.000000 -24.400000
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex 21.000000 -0.000000 -24.400000
      vertex 21.000000 -2.500000 -29.400000
      vertex 21.000000 -2.500000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 21.000000 -2.500000 -24.400000
      vertex 31.209999 -2.500000 -24.400000
      vertex 21.000000 -0.000000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 31.209999 -2.500000 -24.400000
      vertex 31.209999 -0.000000 -24.400000
      vertex 21.000000 -0.000000 -24.400000
    endloop
  endfacet
  facet normal 1.000000 0.000000 -0.000000
    outer loop
      vertex 31.209999 -2.500000 20.400000
      vertex 31.209999 -0.000000 25.400000
      vertex 31.209999 -3.000000 25.400000
    endloop
  endfacet
  facet normal 1.000000 0.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 20.400000
      vertex 31.209999 -0.000000 25.400000
      vertex 31.209999 -2.500000 20.400000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 31.209999 -3.000000 -29.400000
      vertex 31.209999 -2.500000 -24.400000
      vertex 31.209999 -2.500000 20.400000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 31.209999 -3.000000 -29.400000
      vertex 31.209999 -2.500000 20.400000
      vertex 31.209999 -3.000000 25.400000
    endloop
  endfacet
  facet normal 1.000000 0.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 -29.400000
      vertex 31.209999 -0.000000 -24.400000
      vertex 31.209999 -2.500000 -24.400000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 31.209999 -0.000000 -29.400000
      vertex 31.209999 -2.500000 -24.400000
      vertex 31.209999 -3.000000 -29.400000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 31.209999 -0.000000 20.400000
      vertex 31.209999 -2.500000 20.400000
      vertex 21.000000 -0.000000 20.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 21.000000 -0.000000 20.400000
      vertex 31.209999 -2.500000 20.400000
      vertex 21.000000 -2.500000 20.400000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 21.000000 -0.000000 20.400000
      vertex 21.000000 -2.500000 20.400000
      vertex 21.000000 -0.000000 25.400000
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex 21.000000 -0.000000 25.400000
      vertex 21.000000 -2.500000 20.400000
      vertex 21.000000 -2.500000 25.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 20.400000
      vertex 29.920080 -0.000000 22.371269
      vertex 30.145638 -0.000000 22.571096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.145638 -0.000000 22.571096
      vertex 30.316820 -0.000000 22.819096
      vertex 31.209999 -0.000000 20.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 20.400000
      vertex 29.653255 -0.000000 22.231230
      vertex 29.920080 -0.000000 22.371269
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.316820 -0.000000 22.819096
      vertex 30.423677 -0.000000 23.100855
      vertex 31.209999 -0.000000 20.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 20.400000
      vertex 29.360670 -0.000000 22.159115
      vertex 29.653255 -0.000000 22.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.423677 -0.000000 23.100855
      vertex 30.459999 -0.000000 23.400000
      vertex 31.209999 -0.000000 20.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 20.400000
      vertex 29.059330 -0.000000 22.159115
      vertex 29.360670 -0.000000 22.159115
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 20.400000
      vertex 28.766745 -0.000000 22.231230
      vertex 29.059330 -0.000000 22.159115
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.145638 -0.000000 24.228903
      vertex 31.209999 -0.000000 25.400000
      vertex 30.316820 -0.000000 23.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.316820 -0.000000 23.980904
      vertex 31.209999 -0.000000 25.400000
      vertex 30.423677 -0.000000 23.699144
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.423677 -0.000000 23.699144
      vertex 31.209999 -0.000000 25.400000
      vertex 30.459999 -0.000000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.459999 -0.000000 23.400000
      vertex 31.209999 -0.000000 25.400000
      vertex 31.209999 -0.000000 20.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.145638 -0.000000 24.228903
      vertex 29.920080 -0.000000 24.428730
      vertex 31.209999 -0.000000 25.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.920080 -0.000000 24.428730
      vertex 29.653255 -0.000000 24.568769
      vertex 31.209999 -0.000000 25.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.653255 -0.000000 24.568769
      vertex 29.360670 -0.000000 24.640886
      vertex 31.209999 -0.000000 25.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.360670 -0.000000 24.640886
      vertex 29.059330 -0.000000 24.640886
      vertex 31.209999 -0.000000 25.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.766745 -0.000000 22.231230
      vertex 21.000000 -0.000000 20.400000
      vertex 28.499920 -0.000000 22.371269
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.499920 -0.000000 22.371269
      vertex 21.000000 -0.000000 20.400000
      vertex 28.274361 -0.000000 22.571096
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.274361 -0.000000 22.571096
      vertex 21.000000 -0.000000 20.400000
      vertex 28.103180 -0.000000 22.819096
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.103180 -0.000000 22.819096
      vertex 21.000000 -0.000000 20.400000
      vertex 27.996323 -0.000000 23.100855
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 27.996323 -0.000000 23.100855
      vertex 21.000000 -0.000000 20.400000
      vertex 27.959999 -0.000000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 20.400000
      vertex 21.000000 -0.000000 20.400000
      vertex 28.766745 -0.000000 22.231230
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 27.959999 -0.000000 23.400000
      vertex 21.000000 -0.000000 25.400000
      vertex 27.996323 -0.000000 23.699144
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 27.996323 -0.000000 23.699144
      vertex 21.000000 -0.000000 25.400000
      vertex 28.103180 -0.000000 23.980904
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.103180 -0.000000 23.980904
      vertex 21.000000 -0.000000 25.400000
      vertex 28.274361 -0.000000 24.228903
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.274361 -0.000000 24.228903
      vertex 21.000000 -0.000000 25.400000
      vertex 28.499920 -0.000000 24.428730
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.499920 -0.000000 24.428730
      vertex 21.000000 -0.000000 25.400000
      vertex 28.766745 -0.000000 24.568769
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 21.000000 -0.000000 20.400000
      vertex 21.000000 -0.000000 25.400000
      vertex 27.959999 -0.000000 23.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 21.000000 -0.000000 25.400000
      vertex 31.209999 -0.000000 25.400000
      vertex 29.059330 -0.000000 24.640886
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 21.000000 -0.000000 25.400000
      vertex 29.059330 -0.000000 24.640886
      vertex 28.766745 -0.000000 24.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 -29.400000
      vertex 29.920080 -0.000000 -28.428730
      vertex 30.145638 -0.000000 -28.228903
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.145638 -0.000000 -28.228903
      vertex 30.316820 -0.000000 -27.980904
      vertex 31.209999 -0.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 -29.400000
      vertex 29.653255 -0.000000 -28.568769
      vertex 29.920080 -0.000000 -28.428730
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.316820 -0.000000 -27.980904
      vertex 30.423677 -0.000000 -27.699144
      vertex 31.209999 -0.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 -29.400000
      vertex 29.360670 -0.000000 -28.640886
      vertex 29.653255 -0.000000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.423677 -0.000000 -27.699144
      vertex 30.459999 -0.000000 -27.400000
      vertex 31.209999 -0.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 31.209999 -0.000000 -29.400000
      vertex 29.059330 -0.000000 -28.640886
      vertex 29.360670 -0.000000 -28.640886
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 29.653255 -0.000000 -26.231230
      vertex 31.209999 -0.000000 -24.400000
      vertex 29.920080 -0.000000 -26.371269
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 29.920080 -0.000000 -26.371269
      vertex 31.209999 -0.000000 -24.400000
      vertex 30.145638 -0.000000 -26.571096
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 30.145638 -0.000000 -26.571096
      vertex 31.209999 -0.000000 -24.400000
      vertex 30.316820 -0.000000 -26.819096
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 30.316820 -0.000000 -26.819096
      vertex 31.209999 -0.000000 -24.400000
      vertex 30.423677 -0.000000 -27.100855
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 30.423677 -0.000000 -27.100855
      vertex 31.209999 -0.000000 -24.400000
      vertex 30.459999 -0.000000 -27.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 30.459999 -0.000000 -27.400000
      vertex 31.209999 -0.000000 -24.400000
      vertex 31.209999 -0.000000 -29.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 29.653255 -0.000000 -26.231230
      vertex 29.360670 -0.000000 -26.159115
      vertex 31.209999 -0.000000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.360670 -0.000000 -26.159115
      vertex 29.059330 -0.000000 -26.159115
      vertex 31.209999 -0.000000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.059330 -0.000000 -26.159115
      vertex 28.766745 -0.000000 -26.231230
      vertex 31.209999 -0.000000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 28.766745 -0.000000 -28.568769
      vertex 21.000000 -0.000000 -29.400000
      vertex 28.499920 -0.000000 -28.428730
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 28.499920 -0.000000 -28.428730
      vertex 21.000000 -0.000000 -29.400000
      vertex 28.274361 -0.000000 -28.228903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 28.274361 -0.000000 -28.228903
      vertex 21.000000 -0.000000 -29.400000
      vertex 28.103180 -0.000000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.103180 -0.000000 -27.980904
      vertex 21.000000 -0.000000 -29.400000
      vertex 27.996323 -0.000000 -27.699144
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 27.996323 -0.000000 -27.699144
      vertex 21.000000 -0.000000 -29.400000
      vertex 27.959999 -0.000000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 27.959999 -0.000000 -27.400000
      vertex 21.000000 -0.000000 -24.400000
      vertex 27.996323 -0.000000 -27.100855
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 27.996323 -0.000000 -27.100855
      vertex 21.000000 -0.000000 -24.400000
      vertex 28.103180 -0.000000 -26.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.103180 -0.000000 -26.819096
      vertex 21.000000 -0.000000 -24.400000
      vertex 28.274361 -0.000000 -26.571096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.274361 -0.000000 -26.571096
      vertex 21.000000 -0.000000 -24.400000
      vertex 28.499920 -0.000000 -26.371269
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.499920 -0.000000 -26.371269
      vertex 21.000000 -0.000000 -24.400000
      vertex 28.766745 -0.000000 -26.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 21.000000 -0.000000 -29.400000
      vertex 21.000000 -0.000000 -24.400000
      vertex 27.959999 -0.000000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.766745 -0.000000 -26.231230
      vertex 21.000000 -0.000000 -24.400000
      vertex 31.209999 -0.000000 -24.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 31.209999 -0.000000 -29.400000
      vertex 21.000000 -0.000000 -29.400000
      vertex 29.059330 -0.000000 -28.640886
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.059330 -0.000000 -28.640886
      vertex 21.000000 -0.000000 -29.400000
      vertex 28.766745 -0.000000 -28.568769
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120539
    outer loop
      vertex 27.959999 -0.000000 23.400000
      vertex 27.996323 -0.000000 23.699144
      vertex 27.959999 -2.500000 23.400000
    endloop
  endfacet
  facet normal 0.992709 -0.000000 -0.120539
    outer loop
      vertex 27.959999 -2.500000 23.400000
      vertex 27.996323 -0.000000 23.699144
      vertex 27.996323 -2.500000 23.699144
    endloop
  endfacet
  facet normal 0.935016 -0.000000 -0.354605
    outer loop
      vertex 27.996323 -2.500000 23.699144
      vertex 28.103180 -0.000000 23.980904
      vertex 28.103180 -2.500000 23.980904
    endloop
  endfacet
  facet normal 0.822985 0.000000 -0.568063
    outer loop
      vertex 28.103180 -2.500000 23.980904
      vertex 28.103180 -0.000000 23.980904
      vertex 28.274361 -2.500000 24.228903
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex 27.996323 -0.000000 23.699144
      vertex 28.103180 -0.000000 23.980904
      vertex 27.996323 -2.500000 23.699144
    endloop
  endfacet
  facet normal 0.822985 -0.000000 -0.568063
    outer loop
      vertex 28.103180 -0.000000 23.980904
      vertex 28.274361 -0.000000 24.228903
      vertex 28.274361 -2.500000 24.228903
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex 28.274361 -2.500000 24.228903
      vertex 28.499920 -0.000000 24.428730
      vertex 28.499920 -2.500000 24.428730
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex 28.274361 -0.000000 24.228903
      vertex 28.499920 -0.000000 24.428730
      vertex 28.274361 -2.500000 24.228903
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex 28.499920 -2.500000 24.428730
      vertex 28.766745 -0.000000 24.568769
      vertex 28.766745 -2.500000 24.568769
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex 28.499920 -0.000000 24.428730
      vertex 28.766745 -0.000000 24.568769
      vertex 28.499920 -2.500000 24.428730
    endloop
  endfacet
  facet normal 0.239319 -0.000000 -0.970941
    outer loop
      vertex 28.766745 -2.500000 24.568769
      vertex 29.059330 -0.000000 24.640886
      vertex 29.059330 -2.500000 24.640886
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.059330 -2.500000 24.640886
      vertex 29.059330 -0.000000 24.640886
      vertex 29.360670 -2.500000 24.640886
    endloop
  endfacet
  facet normal 0.239319 0.000000 -0.970941
    outer loop
      vertex 28.766745 -0.000000 24.568769
      vertex 29.059330 -0.000000 24.640886
      vertex 28.766745 -2.500000 24.568769
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.059330 -0.000000 24.640886
      vertex 29.360670 -0.000000 24.640886
      vertex 29.360670 -2.500000 24.640886
    endloop
  endfacet
  facet normal -0.239319 0.000000 -0.970941
    outer loop
      vertex 29.360670 -2.500000 24.640886
      vertex 29.653255 -0.000000 24.568769
      vertex 29.653255 -2.500000 24.568769
    endloop
  endfacet
  facet normal -0.239319 -0.000000 -0.970941
    outer loop
      vertex 29.360670 -0.000000 24.640886
      vertex 29.653255 -0.000000 24.568769
      vertex 29.360670 -2.500000 24.640886
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex 29.653255 -2.500000 24.568769
      vertex 29.920080 -0.000000 24.428730
      vertex 29.920080 -2.500000 24.428730
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex 29.653255 -0.000000 24.568769
      vertex 29.920080 -0.000000 24.428730
      vertex 29.653255 -2.500000 24.568769
    endloop
  endfacet
  facet normal -0.663124 0.000000 -0.748509
    outer loop
      vertex 29.920080 -2.500000 24.428730
      vertex 30.145638 -0.000000 24.228903
      vertex 30.145638 -2.500000 24.228903
    endloop
  endfacet
  facet normal -0.663124 -0.000000 -0.748509
    outer loop
      vertex 29.920080 -0.000000 24.428730
      vertex 30.145638 -0.000000 24.228903
      vertex 29.920080 -2.500000 24.428730
    endloop
  endfacet
  facet normal -0.822982 0.000000 -0.568067
    outer loop
      vertex 30.145638 -2.500000 24.228903
      vertex 30.316820 -0.000000 23.980904
      vertex 30.316820 -2.500000 23.980904
    endloop
  endfacet
  facet normal -0.822982 -0.000000 -0.568067
    outer loop
      vertex 30.145638 -0.000000 24.228903
      vertex 30.316820 -0.000000 23.980904
      vertex 30.145638 -2.500000 24.228903
    endloop
  endfacet
  facet normal -0.935016 -0.000000 -0.354605
    outer loop
      vertex 30.316820 -0.000000 23.980904
      vertex 30.423677 -0.000000 23.699144
      vertex 30.316820 -2.500000 23.980904
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex 30.316820 -2.500000 23.980904
      vertex 30.423677 -0.000000 23.699144
      vertex 30.423677 -2.500000 23.699144
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120533
    outer loop
      vertex 30.423677 -2.500000 23.699144
      vertex 30.423677 -0.000000 23.699144
      vertex 30.459999 -2.500000 23.400000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 -0.120533
    outer loop
      vertex 30.423677 -0.000000 23.699144
      vertex 30.459999 -0.000000 23.400000
      vertex 30.459999 -2.500000 23.400000
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120533
    outer loop
      vertex 30.459999 -2.500000 23.400000
      vertex 30.423677 -0.000000 23.100855
      vertex 30.423677 -2.500000 23.100855
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120533
    outer loop
      vertex 30.459999 -0.000000 23.400000
      vertex 30.423677 -0.000000 23.100855
      vertex 30.459999 -2.500000 23.400000
    endloop
  endfacet
  facet normal -0.935016 -0.000000 0.354605
    outer loop
      vertex 30.423677 -2.500000 23.100855
      vertex 30.316820 -0.000000 22.819096
      vertex 30.316820 -2.500000 22.819096
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex 30.423677 -0.000000 23.100855
      vertex 30.316820 -0.000000 22.819096
      vertex 30.423677 -2.500000 23.100855
    endloop
  endfacet
  facet normal -0.822982 -0.000000 0.568067
    outer loop
      vertex 30.316820 -2.500000 22.819096
      vertex 30.145638 -0.000000 22.571096
      vertex 30.145638 -2.500000 22.571096
    endloop
  endfacet
  facet normal -0.822982 0.000000 0.568067
    outer loop
      vertex 30.316820 -0.000000 22.819096
      vertex 30.145638 -0.000000 22.571096
      vertex 30.316820 -2.500000 22.819096
    endloop
  endfacet
  facet normal -0.663124 -0.000000 0.748509
    outer loop
      vertex 30.145638 -2.500000 22.571096
      vertex 29.920080 -0.000000 22.371269
      vertex 29.920080 -2.500000 22.371269
    endloop
  endfacet
  facet normal -0.663124 0.000000 0.748509
    outer loop
      vertex 30.145638 -0.000000 22.571096
      vertex 29.920080 -0.000000 22.371269
      vertex 30.145638 -2.500000 22.571096
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex 29.920080 -2.500000 22.371269
      vertex 29.653255 -0.000000 22.231230
      vertex 29.653255 -2.500000 22.231230
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex 29.920080 -0.000000 22.371269
      vertex 29.653255 -0.000000 22.231230
      vertex 29.920080 -2.500000 22.371269
    endloop
  endfacet
  facet normal -0.239313 0.000000 0.970942
    outer loop
      vertex 29.653255 -2.500000 22.231230
      vertex 29.360670 -0.000000 22.159115
      vertex 29.360670 -2.500000 22.159115
    endloop
  endfacet
  facet normal -0.239313 0.000000 0.970942
    outer loop
      vertex 29.653255 -0.000000 22.231230
      vertex 29.360670 -0.000000 22.159115
      vertex 29.653255 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.360670 -2.500000 22.159115
      vertex 29.059330 -0.000000 22.159115
      vertex 29.059330 -2.500000 22.159115
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.360670 -0.000000 22.159115
      vertex 29.059330 -0.000000 22.159115
      vertex 29.360670 -2.500000 22.159115
    endloop
  endfacet
  facet normal 0.239313 -0.000000 0.970942
    outer loop
      vertex 29.059330 -2.500000 22.159115
      vertex 28.766745 -0.000000 22.231230
      vertex 28.766745 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.239313 0.000000 0.970942
    outer loop
      vertex 29.059330 -0.000000 22.159115
      vertex 28.766745 -0.000000 22.231230
      vertex 29.059330 -2.500000 22.159115
    endloop
  endfacet
  facet normal 0.464721 -0.000000 0.885457
    outer loop
      vertex 28.766745 -2.500000 22.231230
      vertex 28.499920 -0.000000 22.371269
      vertex 28.499920 -2.500000 22.371269
    endloop
  endfacet
  facet normal 0.464721 0.000000 0.885457
    outer loop
      vertex 28.766745 -0.000000 22.231230
      vertex 28.499920 -0.000000 22.371269
      vertex 28.766745 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.663121 -0.000000 0.748512
    outer loop
      vertex 28.499920 -2.500000 22.371269
      vertex 28.274361 -0.000000 22.571096
      vertex 28.274361 -2.500000 22.571096
    endloop
  endfacet
  facet normal 0.663121 0.000000 0.748512
    outer loop
      vertex 28.499920 -0.000000 22.371269
      vertex 28.274361 -0.000000 22.571096
      vertex 28.499920 -2.500000 22.371269
    endloop
  endfacet
  facet normal 0.822985 0.000000 0.568063
    outer loop
      vertex 28.274361 -2.500000 22.571096
      vertex 28.103180 -0.000000 22.819096
      vertex 28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.822985 0.000000 0.568063
    outer loop
      vertex 28.274361 -0.000000 22.571096
      vertex 28.103180 -0.000000 22.819096
      vertex 28.274361 -2.500000 22.571096
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 28.103180 -2.500000 22.819096
      vertex 27.996323 -0.000000 23.100855
      vertex 27.996323 -2.500000 23.100855
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 28.103180 -0.000000 22.819096
      vertex 27.996323 -0.000000 23.100855
      vertex 28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex 27.996323 -2.500000 23.100855
      vertex 27.959999 -0.000000 23.400000
      vertex 27.959999 -2.500000 23.400000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex 27.996323 -0.000000 23.100855
      vertex 27.959999 -0.000000 23.400000
      vertex 27.996323 -2.500000 23.100855
    endloop
  endfacet
  facet normal 0.992709 0.000000 -0.120539
    outer loop
      vertex 27.959999 -0.000000 -27.400000
      vertex 27.996323 -0.000000 -27.100855
      vertex 27.959999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal 0.992709 -0.000000 -0.120539
    outer loop
      vertex 27.959999 -2.500000 -27.400000
      vertex 27.996323 -0.000000 -27.100855
      vertex 27.996323 -2.500000 -27.100855
    endloop
  endfacet
  facet normal 0.935016 -0.000000 -0.354605
    outer loop
      vertex 27.996323 -2.500000 -27.100855
      vertex 28.103180 -0.000000 -26.819096
      vertex 28.103180 -2.500000 -26.819096
    endloop
  endfacet
  facet normal 0.822985 0.000000 -0.568063
    outer loop
      vertex 28.103180 -2.500000 -26.819096
      vertex 28.103180 -0.000000 -26.819096
      vertex 28.274361 -2.500000 -26.571096
    endloop
  endfacet
  facet normal 0.935016 0.000000 -0.354605
    outer loop
      vertex 27.996323 -0.000000 -27.100855
      vertex 28.103180 -0.000000 -26.819096
      vertex 27.996323 -2.500000 -27.100855
    endloop
  endfacet
  facet normal 0.822985 -0.000000 -0.568063
    outer loop
      vertex 28.103180 -0.000000 -26.819096
      vertex 28.274361 -0.000000 -26.571096
      vertex 28.274361 -2.500000 -26.571096
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex 28.274361 -2.500000 -26.571096
      vertex 28.499920 -0.000000 -26.371269
      vertex 28.499920 -2.500000 -26.371269
    endloop
  endfacet
  facet normal 0.663121 0.000000 -0.748512
    outer loop
      vertex 28.274361 -0.000000 -26.571096
      vertex 28.499920 -0.000000 -26.371269
      vertex 28.274361 -2.500000 -26.571096
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex 28.499920 -2.500000 -26.371269
      vertex 28.766745 -0.000000 -26.231230
      vertex 28.766745 -2.500000 -26.231230
    endloop
  endfacet
  facet normal 0.464721 0.000000 -0.885457
    outer loop
      vertex 28.499920 -0.000000 -26.371269
      vertex 28.766745 -0.000000 -26.231230
      vertex 28.499920 -2.500000 -26.371269
    endloop
  endfacet
  facet normal 0.239313 0.000000 -0.970942
    outer loop
      vertex 28.766745 -2.500000 -26.231230
      vertex 29.059330 -0.000000 -26.159115
      vertex 29.059330 -2.500000 -26.159115
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.059330 -2.500000 -26.159115
      vertex 29.059330 -0.000000 -26.159115
      vertex 29.360670 -2.500000 -26.159115
    endloop
  endfacet
  facet normal 0.239313 0.000000 -0.970942
    outer loop
      vertex 28.766745 -0.000000 -26.231230
      vertex 29.059330 -0.000000 -26.159115
      vertex 28.766745 -2.500000 -26.231230
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.059330 -0.000000 -26.159115
      vertex 29.360670 -0.000000 -26.159115
      vertex 29.360670 -2.500000 -26.159115
    endloop
  endfacet
  facet normal -0.239313 -0.000000 -0.970942
    outer loop
      vertex 29.360670 -2.500000 -26.159115
      vertex 29.653255 -0.000000 -26.231230
      vertex 29.653255 -2.500000 -26.231230
    endloop
  endfacet
  facet normal -0.239313 -0.000000 -0.970942
    outer loop
      vertex 29.360670 -0.000000 -26.159115
      vertex 29.653255 -0.000000 -26.231230
      vertex 29.360670 -2.500000 -26.159115
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex 29.653255 -2.500000 -26.231230
      vertex 29.920080 -0.000000 -26.371269
      vertex 29.920080 -2.500000 -26.371269
    endloop
  endfacet
  facet normal -0.464721 -0.000000 -0.885457
    outer loop
      vertex 29.653255 -0.000000 -26.231230
      vertex 29.920080 -0.000000 -26.371269
      vertex 29.653255 -2.500000 -26.231230
    endloop
  endfacet
  facet normal -0.663124 0.000000 -0.748509
    outer loop
      vertex 29.920080 -2.500000 -26.371269
      vertex 30.145638 -0.000000 -26.571096
      vertex 30.145638 -2.500000 -26.571096
    endloop
  endfacet
  facet normal -0.663124 -0.000000 -0.748509
    outer loop
      vertex 29.920080 -0.000000 -26.371269
      vertex 30.145638 -0.000000 -26.571096
      vertex 29.920080 -2.500000 -26.371269
    endloop
  endfacet
  facet normal -0.822982 0.000000 -0.568067
    outer loop
      vertex 30.145638 -2.500000 -26.571096
      vertex 30.316820 -0.000000 -26.819096
      vertex 30.316820 -2.500000 -26.819096
    endloop
  endfacet
  facet normal -0.822982 -0.000000 -0.568067
    outer loop
      vertex 30.145638 -0.000000 -26.571096
      vertex 30.316820 -0.000000 -26.819096
      vertex 30.145638 -2.500000 -26.571096
    endloop
  endfacet
  facet normal -0.935016 -0.000000 -0.354605
    outer loop
      vertex 30.316820 -0.000000 -26.819096
      vertex 30.423677 -0.000000 -27.100855
      vertex 30.316820 -2.500000 -26.819096
    endloop
  endfacet
  facet normal -0.935016 0.000000 -0.354605
    outer loop
      vertex 30.316820 -2.500000 -26.819096
      vertex 30.423677 -0.000000 -27.100855
      vertex 30.423677 -2.500000 -27.100855
    endloop
  endfacet
  facet normal -0.992709 0.000000 -0.120533
    outer loop
      vertex 30.423677 -2.500000 -27.100855
      vertex 30.423677 -0.000000 -27.100855
      vertex 30.459999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal -0.992709 -0.000000 -0.120533
    outer loop
      vertex 30.423677 -0.000000 -27.100855
      vertex 30.459999 -0.000000 -27.400000
      vertex 30.459999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120533
    outer loop
      vertex 30.459999 -2.500000 -27.400000
      vertex 30.423677 -0.000000 -27.699144
      vertex 30.423677 -2.500000 -27.699144
    endloop
  endfacet
  facet normal -0.992709 0.000000 0.120533
    outer loop
      vertex 30.459999 -0.000000 -27.400000
      vertex 30.423677 -0.000000 -27.699144
      vertex 30.459999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal -0.935016 -0.000000 0.354605
    outer loop
      vertex 30.423677 -2.500000 -27.699144
      vertex 30.316820 -0.000000 -27.980904
      vertex 30.316820 -2.500000 -27.980904
    endloop
  endfacet
  facet normal -0.935016 0.000000 0.354605
    outer loop
      vertex 30.423677 -0.000000 -27.699144
      vertex 30.316820 -0.000000 -27.980904
      vertex 30.423677 -2.500000 -27.699144
    endloop
  endfacet
  facet normal -0.822982 -0.000000 0.568067
    outer loop
      vertex 30.316820 -2.500000 -27.980904
      vertex 30.145638 -0.000000 -28.228903
      vertex 30.145638 -2.500000 -28.228903
    endloop
  endfacet
  facet normal -0.822982 0.000000 0.568067
    outer loop
      vertex 30.316820 -0.000000 -27.980904
      vertex 30.145638 -0.000000 -28.228903
      vertex 30.316820 -2.500000 -27.980904
    endloop
  endfacet
  facet normal -0.663124 -0.000000 0.748509
    outer loop
      vertex 30.145638 -2.500000 -28.228903
      vertex 29.920080 -0.000000 -28.428730
      vertex 29.920080 -2.500000 -28.428730
    endloop
  endfacet
  facet normal -0.663124 0.000000 0.748509
    outer loop
      vertex 30.145638 -0.000000 -28.228903
      vertex 29.920080 -0.000000 -28.428730
      vertex 30.145638 -2.500000 -28.228903
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex 29.920080 -2.500000 -28.428730
      vertex 29.653255 -0.000000 -28.568769
      vertex 29.653255 -2.500000 -28.568769
    endloop
  endfacet
  facet normal -0.464721 0.000000 0.885457
    outer loop
      vertex 29.920080 -0.000000 -28.428730
      vertex 29.653255 -0.000000 -28.568769
      vertex 29.920080 -2.500000 -28.428730
    endloop
  endfacet
  facet normal -0.239319 -0.000000 0.970941
    outer loop
      vertex 29.653255 -2.500000 -28.568769
      vertex 29.360670 -0.000000 -28.640886
      vertex 29.360670 -2.500000 -28.640886
    endloop
  endfacet
  facet normal -0.239319 0.000000 0.970941
    outer loop
      vertex 29.653255 -0.000000 -28.568769
      vertex 29.360670 -0.000000 -28.640886
      vertex 29.653255 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.360670 -2.500000 -28.640886
      vertex 29.059330 -0.000000 -28.640886
      vertex 29.059330 -2.500000 -28.640886
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.360670 -0.000000 -28.640886
      vertex 29.059330 -0.000000 -28.640886
      vertex 29.360670 -2.500000 -28.640886
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex 29.059330 -2.500000 -28.640886
      vertex 28.766745 -0.000000 -28.568769
      vertex 28.766745 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.239319 0.000000 0.970941
    outer loop
      vertex 29.059330 -0.000000 -28.640886
      vertex 28.766745 -0.000000 -28.568769
      vertex 29.059330 -2.500000 -28.640886
    endloop
  endfacet
  facet normal 0.464721 -0.000000 0.885457
    outer loop
      vertex 28.766745 -2.500000 -28.568769
      vertex 28.499920 -0.000000 -28.428730
      vertex 28.499920 -2.500000 -28.428730
    endloop
  endfacet
  facet normal 0.464721 0.000000 0.885457
    outer loop
      vertex 28.766745 -0.000000 -28.568769
      vertex 28.499920 -0.000000 -28.428730
      vertex 28.766745 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.663121 -0.000000 0.748512
    outer loop
      vertex 28.499920 -2.500000 -28.428730
      vertex 28.274361 -0.000000 -28.228903
      vertex 28.274361 -2.500000 -28.228903
    endloop
  endfacet
  facet normal 0.663121 0.000000 0.748512
    outer loop
      vertex 28.499920 -0.000000 -28.428730
      vertex 28.274361 -0.000000 -28.228903
      vertex 28.499920 -2.500000 -28.428730
    endloop
  endfacet
  facet normal 0.822985 0.000000 0.568063
    outer loop
      vertex 28.274361 -2.500000 -28.228903
      vertex 28.103180 -0.000000 -27.980904
      vertex 28.103180 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.822985 0.000000 0.568063
    outer loop
      vertex 28.274361 -0.000000 -28.228903
      vertex 28.103180 -0.000000 -27.980904
      vertex 28.274361 -2.500000 -28.228903
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 28.103180 -2.500000 -27.980904
      vertex 27.996323 -0.000000 -27.699144
      vertex 27.996323 -2.500000 -27.699144
    endloop
  endfacet
  facet normal 0.935016 0.000000 0.354605
    outer loop
      vertex 28.103180 -0.000000 -27.980904
      vertex 27.996323 -0.000000 -27.699144
      vertex 28.103180 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex 27.996323 -2.500000 -27.699144
      vertex 27.959999 -0.000000 -27.400000
      vertex 27.959999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal 0.992709 0.000000 0.120539
    outer loop
      vertex 27.996323 -0.000000 -27.699144
      vertex 27.959999 -0.000000 -27.400000
      vertex 27.996323 -2.500000 -27.699144
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.145638 -2.500000 22.571096
      vertex 29.653255 -2.500000 22.231230
      vertex 30.316820 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.920080 -2.500000 22.371269
      vertex 29.653255 -2.500000 22.231230
      vertex 30.145638 -2.500000 22.571096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.316820 -2.500000 22.819096
      vertex 30.459999 -2.500000 23.400000
      vertex 30.423677 -2.500000 23.100855
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.360670 -2.500000 22.159115
      vertex 29.059330 -2.500000 22.159115
      vertex 29.653255 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.423677 -2.500000 23.699144
      vertex 30.145638 -2.500000 24.228903
      vertex 30.316820 -2.500000 23.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.459999 -2.500000 23.400000
      vertex 30.145638 -2.500000 24.228903
      vertex 30.423677 -2.500000 23.699144
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.653255 -2.500000 22.231230
      vertex 30.145638 -2.500000 24.228903
      vertex 30.316820 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.316820 -2.500000 22.819096
      vertex 30.145638 -2.500000 24.228903
      vertex 30.459999 -2.500000 23.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.653255 -2.500000 22.231230
      vertex 29.920080 -2.500000 24.428730
      vertex 30.145638 -2.500000 24.228903
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.499920 -2.500000 22.371269
      vertex 28.103180 -2.500000 22.819096
      vertex 28.766745 -2.500000 22.231230
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.274361 -2.500000 22.571096
      vertex 28.103180 -2.500000 22.819096
      vertex 28.499920 -2.500000 22.371269
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.920080 -2.500000 24.428730
      vertex 29.360670 -2.500000 24.640886
      vertex 29.653255 -2.500000 24.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.653255 -2.500000 22.231230
      vertex 29.360670 -2.500000 24.640886
      vertex 29.920080 -2.500000 24.428730
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 27.996323 -2.500000 23.100855
      vertex 27.959999 -2.500000 23.400000
      vertex 28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.059330 -2.500000 22.159115
      vertex 29.059330 -2.500000 24.640886
      vertex 29.653255 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.653255 -2.500000 22.231230
      vertex 29.059330 -2.500000 24.640886
      vertex 29.360670 -2.500000 24.640886
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 27.996323 -2.500000 23.699144
      vertex 28.103180 -2.500000 23.980904
      vertex 27.959999 -2.500000 23.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 27.959999 -2.500000 23.400000
      vertex 28.103180 -2.500000 23.980904
      vertex 28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.059330 -2.500000 24.640886
      vertex 28.499920 -2.500000 24.428730
      vertex 28.766745 -2.500000 24.568769
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.766745 -2.500000 22.231230
      vertex 28.499920 -2.500000 24.428730
      vertex 29.059330 -2.500000 22.159115
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.059330 -2.500000 22.159115
      vertex 28.499920 -2.500000 24.428730
      vertex 29.059330 -2.500000 24.640886
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.103180 -2.500000 22.819096
      vertex 28.274361 -2.500000 24.228903
      vertex 28.766745 -2.500000 22.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 28.766745 -2.500000 22.231230
      vertex 28.274361 -2.500000 24.228903
      vertex 28.499920 -2.500000 24.428730
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.103180 -2.500000 23.980904
      vertex 28.274361 -2.500000 24.228903
      vertex 28.103180 -2.500000 22.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.145638 -2.500000 -28.228903
      vertex 29.653255 -2.500000 -28.568769
      vertex 30.316820 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.920080 -2.500000 -28.428730
      vertex 29.653255 -2.500000 -28.568769
      vertex 30.145638 -2.500000 -28.228903
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.316820 -2.500000 -27.980904
      vertex 30.459999 -2.500000 -27.400000
      vertex 30.423677 -2.500000 -27.699144
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.360670 -2.500000 -28.640886
      vertex 29.059330 -2.500000 -28.640886
      vertex 29.653255 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.423677 -2.500000 -27.100855
      vertex 30.145638 -2.500000 -26.571096
      vertex 30.316820 -2.500000 -26.819096
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 30.459999 -2.500000 -27.400000
      vertex 30.145638 -2.500000 -26.571096
      vertex 30.423677 -2.500000 -27.100855
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.653255 -2.500000 -28.568769
      vertex 30.145638 -2.500000 -26.571096
      vertex 30.316820 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 30.316820 -2.500000 -27.980904
      vertex 30.145638 -2.500000 -26.571096
      vertex 30.459999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.653255 -2.500000 -28.568769
      vertex 29.920080 -2.500000 -26.371269
      vertex 30.145638 -2.500000 -26.571096
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.499920 -2.500000 -28.428730
      vertex 28.103180 -2.500000 -27.980904
      vertex 28.766745 -2.500000 -28.568769
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 28.274361 -2.500000 -28.228903
      vertex 28.103180 -2.500000 -27.980904
      vertex 28.499920 -2.500000 -28.428730
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.920080 -2.500000 -26.371269
      vertex 29.360670 -2.500000 -26.159115
      vertex 29.653255 -2.500000 -26.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 29.653255 -2.500000 -28.568769
      vertex 29.360670 -2.500000 -26.159115
      vertex 29.920080 -2.500000 -26.371269
    endloop
  endfacet
  facet normal -0.000000 1.000000 -0.000000
    outer loop
      vertex 27.996323 -2.500000 -27.699144
      vertex 27.959999 -2.500000 -27.400000
      vertex 28.103180 -2.500000 -27.980904
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.766745 -2.500000 -28.568769
      vertex 29.059330 -2.500000 -26.159115
      vertex 29.059330 -2.500000 -28.640886
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.059330 -2.500000 -28.640886
      vertex 29.059330 -2.500000 -26.159115
      vertex 29.653255 -2.500000 -28.568769
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.653255 -2.500000 -28.568769
      vertex 29.059330 -2.500000 -26.159115
      vertex 29.360670 -2.500000 -26.159115
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 27.996323 -2.500000 -27.100855
      vertex 28.103180 -2.500000 -26.819096
      vertex 27.959999 -2.500000 -27.400000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 27.959999 -2.500000 -27.400000
      vertex 28.103180 -2.500000 -26.819096
      vertex 28.103180 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 29.059330 -2.500000 -26.159115
      vertex 28.499920 -2.500000 -26.371269
      vertex 28.766745 -2.500000 -26.231230
    endloop
  endfacet
  facet normal 0.000000 1.000000 -0.000000
    outer loop
      vertex 28.766745 -2.500000 -28.568769
      vertex 28.499920 -2.500000 -26.371269
      vertex 29.059330 -2.500000 -26.159115
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.103180 -2.500000 -27.980904
      vertex 28.274361 -2.500000 -26.571096
      vertex 28.766745 -2.500000 -28.568769
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 28.103180 -2.500000 -26.819096
      vertex 28.274361 -2.500000 -26.571096
      vertex 28.103180 -2.500000 -27.980904
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 28.766745 -2.500000 -28.568769
      vertex 28.274361 -2.500000 -26.571096
      vertex 28.499920 -2.500000 -26.371269
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex -29.209999 -3.000000 -18.900000
      vertex -29.209999 -2.500000 17.900000
      vertex -29.209999 -3.000000 17.900000
    endloop
  endfacet
  facet normal 1.000000 0.000000 -0.000000
    outer loop
      vertex -29.209999 -2.500000 -18.900000
      vertex -29.209999 -2.500000 17.900000
      vertex -29.209999 -3.000000 -18.900000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -29.209999 -2.500000 -18.900000
      vertex -29.209999 -3.000000 -18.900000
      vertex 29.209999 -3.000000 -18.900000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -29.209999 -2.500000 -18.900000
      vertex 29.209999 -3.000000 -18.900000
      vertex 29.209999 -2.500000 -18.900000
    endloop
  endfacet
  facet normal -1.000000 -0.000000 0.000000
    outer loop
      vertex 29.209999 -2.500000 17.900000
      vertex 29.209999 -3.000000 -18.900000
      vertex 29.209999 -3.000000 17.900000
    endloop
  endfacet
  facet normal -1.000000 0.000000 -0.000000
    outer loop
      vertex 29.209999 -2.500000 17.900000
      vertex 29.209999 -2.500000 -18.900000
      vertex 29.209999 -3.000000 -18.900000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -29.209999 -3.000000 -18.900000
      vertex -29.209999 -3.000000 17.900000
      vertex -31.209999 -3.000000 25.400000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex -31.209999 -3.000000 -29.400000
      vertex -29.209999 -3.000000 -18.900000
      vertex -31.209999 -3.000000 25.400000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 31.209999 -3.000000 25.400000
      vertex -31.209999 -3.000000 25.400000
      vertex -29.209999 -3.000000 17.900000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 29.209999 -3.000000 17.900000
      vertex 31.209999 -3.000000 25.400000
      vertex -29.209999 -3.000000 17.900000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 31.209999 -3.000000 -29.400000
      vertex 29.209999 -3.000000 -18.900000
      vertex -29.209999 -3.000000 -18.900000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 31.209999 -3.000000 -29.400000
      vertex -29.209999 -3.000000 -18.900000
      vertex -31.209999 -3.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 31.209999 -3.000000 -29.400000
      vertex 31.209999 -3.000000 25.400000
      vertex 29.209999 -3.000000 -18.900000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 29.209999 -3.000000 -18.900000
      vertex 31.209999 -3.000000 25.400000
      vertex 29.209999 -3.000000 17.900000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 21.000000 -2.500000 25.400000
      vertex 31.209999 -3.000000 25.400000
      vertex 31.209999 -0.000000 25.400000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 21.000000 -0.000000 25.400000
      vertex 21.000000 -2.500000 25.400000
      vertex 31.209999 -0.000000 25.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -31.209999 0.000000 25.400000
      vertex -21.000000 -2.500000 25.400000
      vertex -21.000000 0.000000 25.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -31.209999 0.000000 25.400000
      vertex -31.209999 -3.000000 25.400000
      vertex -21.000000 -2.500000 25.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -31.209999 -3.000000 25.400000
      vertex 31.209999 -3.000000 25.400000
      vertex -21.000000 -2.500000 25.400000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -21.000000 -2.500000 25.400000
      vertex 31.209999 -3.000000 25.400000
      vertex 21.000000 -2.500000 25.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -29.209999 -2.500000 17.900000
      vertex 29.209999 -2.500000 17.900000
      vertex 29.209999 -3.000000 17.900000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -29.209999 -3.000000 17.900000
      vertex -29.209999 -2.500000 17.900000
      vertex 29.209999 -3.000000 17.900000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 21.000000 -2.500000 -29.400000
      vertex 31.209999 -0.000000 -29.400000
      vertex 31.209999 -3.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 21.000000 -0.000000 -29.400000
      vertex 31.209999 -0.000000 -29.400000
      vertex 21.000000 -2.500000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.209999 -3.000000 -29.400000
      vertex -21.000000 -2.500000 -29.400000
      vertex 21.000000 -2.500000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.209999 -3.000000 -29.400000
      vertex 21.000000 -2.500000 -29.400000
      vertex 31.209999 -3.000000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.209999 -0.000000 -29.400000
      vertex -21.000000 -0.000000 -29.400000
      vertex -21.000000 -2.500000 -29.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.209999 -0.000000 -29.400000
      vertex -21.000000 -2.500000 -29.400000
      vertex -31.209999 -3.000000 -29.400000
    endloop
  endfacet
endsolid Mesh
```


## License

This work is licensed under CC BY-NC-SA 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/ 






