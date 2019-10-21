# Effective Use of Color in Climate Science Visualizations

**Launch a binder here to run our notebooks and import custom colormaps:**

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bradyrx/climate_science_colormapping/master)

Riley X. Brady and Luke Davis

This repository holds materials for a 90-minute workshop on building and utilizing effective colormaps for climate science visualizations. The workshop begins with a 15-minute presentation on colormap basics (e.g., different types of colormaps with examples and best practices for usage), followed by a 15-minute presentation on the more quantitative aspects of evaluating colormaps, and then a 60-minute period (including presentations) where participants use online tools to build their own colormaps.

You can find the color usage documentation for `proplot` [here](https://proplot.readthedocs.io/en/latest/colors.html) as well as installation instructions. `proplot` is a `matplotlib` wrapper written by Luke Davis with an extremely robust colormapping and color cycling module. We use it under the hood in this tutorial, but you can find more details on the documentation for building your own colormaps and color cycles through `proplot`.

## Helpful Links

### Downloadable Colormaps

Here you can download colormaps for your language/GUI of choice.

1. [cpt-city](http://soliton.vm.bytemark.co.uk/pub/cpt-city/) - Not well screened for _good_ colormaps, but a huge library of them to look through.
2. [SciVisColor](https://sciviscolor.org/) - Science-focused colormaps created by the viz team at UT Austin.
3. [cmocean](https://matplotlib.org/cmocean/) - Perceptually uniform colormaps for oceangoraphy. 
4. [Fabio Crameri](http://www.fabiocrameri.ch/colourmaps.php) - Perceptually uniform colormaps for geosciences.
5. [Color Brewer](http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3) - One of the original resources for perceptually uniform colormaps. The strings from this page can be passed directly into `matplotlib`.

### Color Palettes

Can serve as inspiration when making qualitative colormaps (color cycles).

1. [Color Hunt](https://colorhunt.co/)
2. [Color Drop](https://colordrop.io/)
3. [Adobe Color](https://color.adobe.com/explore)
4. [Proplot API](https://proplot.readthedocs.io/en/latest/colors.html#making-your-own-colormaps)

### Design Your Own Colormaps

1. [HCL Picker](http://tristen.ca/hcl-picker/#/hlc/6/1/15534C/E2E062)
2. [Chroma.js](https://gka.github.io/palettes/)
3. [HCL Wizard](http://hclwizard.org:64230/hclwizard/)
4. 

### Design Your Own Color Cycles

1. [Color Cycle Picker](https://colorcyclepicker.mpetroff.net/)
2. [i want hue](http://medialab.github.io/iwanthue/)
3. [Coolors](https://coolors.co/)
4. [Proplot API](https://proplot.readthedocs.io/en/latest/colors.html#making-your-own-color-cycles)

### Testing Your Color Maps and Color Cycles

1. [Viz Palette](https://projects.susielu.com/viz-palette) - Will check colorblind friendliness, contrast, and even whether or not they have "name" conflicts for when pointing out colors during a talk.
