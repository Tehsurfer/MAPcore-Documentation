3-D organ map viewer
====================

.. contents:: Contents: 
   :local:
   :depth: 2
   :backlinks: top
   
Overview
********
   
This document describes how to use the 3-D organ map viewer tool available on the SPARC Data Portal. Examples of this tool in action are available (link to specific use case pages here).

.. todo::
    Alan - can you write a short paragraph explaining the technology used here.

Viewer configuration
^^^^^^^^^^^^^^^^^^^^
.. todo::
    Check that all config ooptions are mentioned and remove the ones that no longer exist. Also need to update the "open controls" to be the hamburger icon.

The :guilabel:`Open Controls` button at the top-left corner of this tool provides access to the configuration of this organ map viewer. This allows the user to choose which aspect of the mapped data to visualize, reset the view, etc.

Functionality of different *configuration options*:

* **View All** - this control ensures the entire organ map is visible.

* **Mesh Types** - displays various kinds of organs/shapes supported by the underlying scaffolding tools, but presently only the heart related choices are functional. The default organ which is showcased is "3d_heart1".

* **Parameters** - the configuration defining the various attributes of the organ scaffold. The default values have been preset to provide a reasonable configuration of the organ.

* **Regions** - the currently defined anatomical regions of the displayed organ scaffold. Currently, this functionality works only for the heart. Hovering over the different regions highlights the particular selected area of the organ; unchecking the region will cause the region surface to be hidden in the current scaffold visualisation. 

The :guilabel:`Close Controls` button closes the expanded controls panel.
 

Interactive Graphics Controls
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The table below describes the effect of different mouse buttons in manipulating the 3-D scene being displayed in this organ viewer.

======================= ==============
Mouse Button            Transformation
======================= ==============
Left                    Rotate
----------------------- --------------
Middle 				    Zoom
----------------------- --------------
Right 					Pan
======================= ==============

