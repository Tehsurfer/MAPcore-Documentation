Cell Body Segmentation and Electrophysiology Data: Stellate Ganglion
====================================================================

.. |open-control| image:: /_images/open_control.png
                      :width: 2 em			
		
.. contents:: Contents: 
   :local:
   :depth: 2
   :backlinks: top
   
Overview
********

Mouse stellate ganglion neuronal cell shape data from the Shivkumar/Tompkins group are displayed in a 3D stellate scaffold. 15 neurons, including their cell bodies, axons and dendrites, are displayed on five cross-sections of the stellate with the high resolution image displayed as a texture map. Electrophysiological data from these cells can be visualized by clicking on the cell. *Note* that the scaffold in this example is a geometrically simple shape designed to register the images in the appropriate anatomical location. The shape of the scaffold will be improved once more data are available to define the stellate boundaries.

This document guides a user of the SPARC Data Portal through the steps required to discover a collection of segmented cell bodies from the stellate ganglion which have been mapped to a common coordinate framework for visualization purposes. The user is able to discover any electrophysiology data that has been recorded for each of the cell bodies.

.. todo::
    add link to final portal URL that takes user straight to this dataset display.

Step-by-step instructions 
*************************

.. todo:: check these steps and update screen shot

Follow these step-by-step instructions to familiarise yourself with the flow of the web interface.

**Step 1**. Click on the **Stellate Ganglion** on the Flatmap.

.. figure:: _images/sg_snip11.png
   :figwidth: 95%
   :width: 95%
   :align: center
   
**Step 2**. A new tab called Scaffold Viewer will open to display the anatomical organ scaffold of the stellate. The current
scaffold is a rectangular cube with slots to contain the stellate image stacks using texture mapping techniques within
the scaffold elements. Segmented cells (Soma) with associated axon and dendrites have been mapped and embedded in
the image-scaffold structure. Each cell will have electro-physiological data properly registered.

.. figure:: _images/stellate_scaffold_image01.png
   :figwidth: 95%
   :width: 95%
   :align: center

**Step 3**. Click on a cell in a sample to visualise the electro-physiological data associated with the cell. The data
is illustrated within a new tab called Data Viewer. You can select different sweep or channel data for that cell in this
tab.

.. figure:: _images/stellate_scaffold_image_02.png
   :figwidth: 95%
   :width: 95%
   :align: center

**Step 4**. You can select different sweep or channel data for that cell in this tab.

.. figure:: _images/sg_snip5.png
   :figwidth: 95%
   :width: 95%
   :align: center

Working with the interface
**************************
This section explains how to use more specific features of the interface.

.. todo::
      Highlight features/capabilities that are particular to this use-case.

:ref:`Flatmap-Viewer`
^^^^^^^^^^^^^^^^^^^^^
The :ref:`Flatmap-Viewer` represents a high-level view of overall connectivity of the autonomic nervous system.
	
:ref:`Scaffold-Viewer`
^^^^^^^^^^^^^^^^^^^^^^
:ref:`Scaffold-Viewer` is used to view the anatomical organ scaffold of the specific organ selected on the Flatmap.
	
:ref:`Data-Viewer`
^^^^^^^^^^^^^^^^^^
This viewer is used to view the *Electrocardiograph* data recorded with the experiment video. Refer the section :ref:`Data-Viewer`.

