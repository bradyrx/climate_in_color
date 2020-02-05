**Launch a binder here to run our notebooks and import custom colormaps:**

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bradyrx/climate_science_colormapping/master)

---

# Effective Use of Color in Climate Science Visualizations

[Riley X. Brady](https://github.com/bradyrx) and [Luke L. B. Davis](https://github.com/lukelbd)

Contact: 
* riley.brady@colorado.edu
* luke.davis@colostate.edu

This repository holds materials for a 90-minute workshop on building and utilizing effective colormaps for climate science visualizations. The workshop begins with a 15-minute presentation on colormap basics (e.g., different types of colormaps with examples and best practices for usage), followed by a 15-minute presentation on the more quantitative aspects of evaluating colormaps, and then a 60-minute period (including presentations) where participants use online tools to build their own colormaps.

You can find the color usage documentation for `proplot` [here](https://proplot.readthedocs.io/en/latest/colormaps.html) as well as installation instructions. `proplot` is a `matplotlib` wrapper written by Luke Davis with an extremely robust colormapping and color cycling module. We use it under the hood in this tutorial, but you can find more details on the documentation for building your own colormaps and color cycles through `proplot`.

## Helpful Links

### Downloadable Colormaps

Here you can download colormaps for your language/GUI of choice.

1. [cpt-city](http://soliton.vm.bytemark.co.uk/pub/cpt-city/) - Not well screened for _good_ colormaps, but a huge library of them to look through.
1. [SciVisColor](https://sciviscolor.org/) - Science-focused colormaps created by the viz team at UT Austin.
1. [cmocean](https://matplotlib.org/cmocean/) - Perceptually uniform colormaps for oceangoraphy. 
1. [Fabio Crameri](http://www.fabiocrameri.ch/colourmaps.php) - Perceptually uniform colormaps for geosciences.
1. [Color Brewer](http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3) - One of the original resources for perceptually uniform colormaps. The strings from this page can be passed directly into `matplotlib`.

### Color Palettes

Can serve as inspiration when making qualitative colormaps (color cycles).

1. [Color Hunt](https://colorhunt.co/)
1. [Color Drop](https://colordrop.io/)
1. [Adobe Color](https://color.adobe.com/explore)

### Design Your Own Colormaps

Resources for making your own colormaps from scratch.

1. [CCC Tool](https://ccctool.com/)
    * See the accompanying manuscript here: https://ieeexplore.ieee.org/abstract/document/8939459
1. [HCL Picker](http://tristen.ca/hcl-picker/#/hlc/6/1/15534C/E2E062)
1. [Chroma.js](https://gka.github.io/palettes/)
1. [HCL Wizard](http://hclwizard.org:64230/hclwizard/)
1. [Proplot API](https://proplot.readthedocs.io/en/latest/colors.html#making-your-own-colormaps)

### Design Your Own Color Cycles

Resources for making your own color cycles from scratch.

1. [Color Cycle Picker](https://colorcyclepicker.mpetroff.net/)
1. [i want hue](http://medialab.github.io/iwanthue/)
1. [Coolors](https://coolors.co/)
1. [Proplot API](https://proplot.readthedocs.io/en/latest/colors.html#making-your-own-color-cycles)

### Testing Your Colormaps and Color Cycles

It's always good to test your colormaps and color cycles to check that they are perceptually uniform and colorblind-friendly.

1. [Viz Palette](https://projects.susielu.com/viz-palette) - Will check colorblind friendliness, contrast, and even whether or not they have "name" conflicts for when pointing out colors during a talk.
1. [Sim Daltonism](https://michelf.ca/projects/sim-daltonism/) and [Color Oracle](https://colororacle.org) - See what your screen looks like to people with various color vision deficiencies. Note that on Mac, you may have to give these applications permission to record your screen by going to System Preferences --> Security and Privacy --> Screen Recording and checking the box next to the application name.
1. [Proplot API](https://proplot.readthedocs.io/en/latest/colors.html#perceptually-uniform-colormaps) -- The [plot.show_channels](https://proplot.readthedocs.io/en/latest/api/proplot.styletools.show_channels.html) function can be used to test the linearity of transitions in hue, chroma, luminance, and saturation.
