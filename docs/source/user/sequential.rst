.. _sequential:

Sequential
==========
Sequential colormaps (that are perceptually uniform of course) are basic colormaps that start at a reasonably low lightness value and uniformly increase to a higher value.
They are commonly used to represent information that is ordered.
The *matplotlib* package already has a few great sequential colormaps readily available for the user, mainly the colormaps named *viridis*; *plasma*; *inferno*; *magma*; and *cividis*.
However, three of these colormaps use the color red as its main color and none of them uses the full lightness range.
As it might sometimes be desirable to use a different main color or maximize the perceptual range of the colormap, *CMasher* provides a few sequential colormaps that do exactly that.
These colormaps are shown below.

.. _PRISM: https://github.com/1313e/PRISM

Arctic
------
.. figure:: ../../../cmasher/colormaps/arctic/arctic.png
    :alt: Visual representation of the *arctic* colormap.
    :width: 100%
    :align: center
    :name: arctic_cmap

.. figure:: ../../../cmasher/colormaps/arctic/arctic_viscm.png
    :alt: Statistics of the *arctic* colormap.
    :width: 100%
    :align: center
    :name: arctic_viscm

The *arctic* colormap is a visual representation of the cold landscape of the Arctic.
It covers the full lightness range and solely uses the color blue.
As the *arctic* colormap uses softer colors, it can be used as an alternative to the *freeze* colormap.


Chroma
------
.. figure:: ../../../cmasher/colormaps/chroma/chroma.png
    :alt: Visual representation of the *chroma* colormap.
    :width: 100%
    :align: center
    :name: chroma_cmap

.. figure:: ../../../cmasher/colormaps/chroma/chroma_viscm.png
    :alt: Statistics of the *chroma* colormap.
    :width: 100%
    :align: center
    :name: chroma_viscm

The *chroma* colormap is a visual representation of all major colors.
It covers the full lightness range and shows all major colors in roughly equal ratio.
Because it uses all major colors, this colormap is excellent for representing information where small adjacent differences should be clearly visible.
Keep in mind that the *chroma* colormap is not as colorblind-friendly as the other colormaps.


Dusk
----
.. figure:: ../../../cmasher/colormaps/dusk/dusk.png
    :alt: Visual representation of the *dusk* colormap.
    :width: 100%
    :align: center
    :name: dusk_cmap

.. figure:: ../../../cmasher/colormaps/dusk/dusk_viscm.png
    :alt: Statistics of the *dusk* colormap.
    :width: 100%
    :align: center
    :name: dusk_viscm

The *dusk* colormap is a visual representation of what the sky looks like during dusk (with the black/blue representing the dark sky and the red/white the last few sunrays above the horizon).
It covers the full lightness range and has the colors blue and orange as its main colors.
It features a greyish area in the middle, making it great for representing ordered information where the extremes should be the main focus of the image.


Flamingo
--------
.. figure:: ../../../cmasher/colormaps/flamingo/flamingo.png
    :alt: Visual representation of the *flamingo* colormap.
    :width: 100%
    :align: center
    :name: flamingo_cmap

.. figure:: ../../../cmasher/colormaps/flamingo/flamingo_viscm.png
    :alt: Statistics of the *flamingo* colormap.
    :width: 100%
    :align: center
    :name: flamingo_viscm

The *flamingo* colormap is a visual representation of the bird with the same name.
It covers the full lightness range and solely uses the color red.
It is the most useful for representing information where the center should be the main focus, but is also great for smoothly varying information.


Freeze
------
.. figure:: ../../../cmasher/colormaps/freeze/freeze.png
    :alt: Visual representation of the *freeze* colormap.
    :width: 100%
    :align: center
    :name: freeze_cmap

.. figure:: ../../../cmasher/colormaps/freeze/freeze_viscm.png
    :alt: Statistics of the *freeze* colormap.
    :width: 100%
    :align: center
    :name: freeze_viscm

The *freeze* colormap is one of the two main colormaps used in `PRISM`_, and is a visual representation of a large body of water freezing over.
It covers the full lightness range and solely uses the color blue.
As it only uses a single color, this colormap is excellent for representing information that varies smoothly, like density/intensity values in a scientific plot.


Gothic
------
.. figure:: ../../../cmasher/colormaps/gothic/gothic.png
    :alt: Visual representation of the *gothic* colormap.
    :width: 100%
    :align: center
    :name: gothic_cmap

.. figure:: ../../../cmasher/colormaps/gothic/gothic_viscm.png
    :alt: Statistics of the *gothic* colormap.
    :width: 100%
    :align: center
    :name: gothic_viscm

The *gothic* colormap is a visual representation of the stereotypical gothic colors.
It covers the full lightness range and solely uses the color purple.
As with the *freeze* colormap, this colormap is excellent for representing information that varies smoothly.


Heat
----
.. figure:: ../../../cmasher/colormaps/heat/heat.png
    :alt: Visual representation of the *heat* colormap.
    :width: 100%
    :align: center
    :name: heat_cmap

.. figure:: ../../../cmasher/colormaps/heat/heat_viscm.png
    :alt: Statistics of the *heat* colormap.
    :width: 100%
    :align: center
    :name: heat_viscm

The *heat* colormap is a visual representation of the typical blue/orange gas flame.
It covers the full lightness range and mainly uses the colors blue/purple and orange.
It should mainly be used for representing information where the center values are important.


Horizon
-------
.. figure:: ../../../cmasher/colormaps/horizon/horizon.png
    :alt: Visual representation of the *horizon* colormap.
    :width: 100%
    :align: center
    :name: horizon_cmap

.. figure:: ../../../cmasher/colormaps/horizon/horizon_viscm.png
    :alt: Statistics of the *horizon* colormap.
    :width: 100%
    :align: center
    :name: horizon_viscm

The *horizon* colormap is a visual representation of the horizon, from the green colors of the land to the calm colors of the clouds.
It covers the full lightness range and has the colors green and blue as its main colors.
It features a brownish area close to the minimum, making it great for representing ordered information where the minimum is not important.


Jungle
------
.. figure:: ../../../cmasher/colormaps/jungle/jungle.png
    :alt: Visual representation of the *jungle* colormap.
    :width: 100%
    :align: center
    :name: jungle_cmap

.. figure:: ../../../cmasher/colormaps/jungle/jungle_viscm.png
    :alt: Statistics of the *jungle* colormap.
    :width: 100%
    :align: center
    :name: jungle_viscm

The *jungle* colormap is a visual representation of a jungle.
It covers the full lightness range and solely uses the color green.
As with the other single-color colormaps, this colormap is excellent for representing smooth information.


Rainforest
----------
.. figure:: ../../../cmasher/colormaps/rainforest/rainforest.png
    :alt: Visual representation of the *rainforest* colormap.
    :width: 100%
    :align: center
    :name: rainforest_cmap

.. figure:: ../../../cmasher/colormaps/rainforest/rainforest_viscm.png
    :alt: Statistics of the *rainforest* colormap.
    :width: 100%
    :align: center
    :name: rainforest_viscm

The *rainforest* colormap is one of the two main colormaps used in `PRISM`_, and is a visual representation of Mother Nature, in particular a dense rainforest (with blue representing the water; green the trees/plants; and yellow/red the Sun).
It covers the full lightness range and uses basically all major colors (red might be hard to see) as it was created by an attempt to improve the *jet* colormap.
Because it uses all major colors, this colormap is excellent for representing information where small adjacent differences should be clearly visible.
This also makes *rainforest* a good standard colormap choice as it treats all information as equally important, in addition to being colorblind-friendly.


Sunburst
--------
.. figure:: ../../../cmasher/colormaps/sunburst/sunburst.png
    :alt: Visual representation of the *sunburst* colormap.
    :width: 100%
    :align: center
    :name: sunburst_cmap

.. figure:: ../../../cmasher/colormaps/sunburst/sunburst_viscm.png
    :alt: Statistics of the *sunburst* colormap.
    :width: 100%
    :align: center
    :name: sunburst_viscm

The *sunburst* colormap is a visual representation of a sunburst or solar flare.
It covers the full lightness range and uses the colors red and orange.
Its smoothly varying coloring makes it a good choice for representing data that varies smoothly as well (like intensity or temperature maps).