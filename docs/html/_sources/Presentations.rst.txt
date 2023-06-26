Presentations
================================

Automatic generation of work zone simulation scenarios
---------------------------------------------------------

The automatic generation of scenarios for simulation that follow the workflow as below:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/AutomaticGenerationOfScenarios.drawio.png
   :align: center


The source file of this workflow diagram can be found here: https://drive.google.com/file/d/18G0Bb3WNbk9Mf6DgM548p8j4xtOKnf1m/view?usp=sharing

Scenarios defined in KMZ format are loaded into GIS software, such as Google Earth.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/googleEarth.png
   :align: center

   This contains all data for the CAD definition, but most of this is not needed within final road definition as per ASAM OpenDRIVE.

The KMZ definition is then parsed to KML, where coordinates are readable. 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/KML.PNG
   :align: center

Using the KML data, we can plot all the scenarios with each other to identify common lane markers and road segments. 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/testTrackENU.png
   :align: center

The driving lanes in LLA coordinates are then transformed into ENU coordinates. This uses the Cartesian coordinates to ease the creation of XODR definitions. 

The ENU coordinates are then resampled for geometric smoothness and to avoid large gaps which cause problems with XODR formats. 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/resampleEnuData.png
   :align: center

The resampled ENU coordinates are then converted to XODR definition.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/testTrack_xodrviewer.png
   :align: center

The XODR file is then editable to apply to different scenarios, for example, changing the lane width. Below shows an example of increasing the right driving lane width. 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

+----------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------+
| .. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/laneWidth_original.png       | .. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/laneWidth_increased.png      |
|    :width: 100%                                                                                                |    :width: 100%                                                                                                |
|    :align: center                                                                                              |    :align: center                                                                                              |
|                                                                                                                |                                                                                                                |
|    Original                                                                                                    |    Lane width increased                                                                                        |
+----------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------+




Below shows another example of increasing the right driving lane width at 500 meters from the start line.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/changeLaneWidthDynamically.png
   :align: center


XODR can be imported into RoadRunner. 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

+----------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------+
| .. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/testTrack_xodrviewer.png     | .. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/testTrack_RR.png             |
|    :width: 80%                                                                                                 |    :width: 100%                                                                                                |
|    :align: center                                                                                              |    :align: center                                                                                              |
|                                                                                                                |                                                                                                                |
|    Road imported into XODR viewer (open-source)                                                                |    Road imported into RoadRunner (commercial)                                                                  |
+----------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------+

RoadRunner exports into CARLA and SUMO. 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+----------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------+
| .. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/testTrack_xodrviewer.png     | .. figure:: Images/Presentations/AutomaticGenerationOfWorkZoneSimulationScenarios/testTrack_SUMO.png           |
|    :width: 80%                                                                                                 |    :width: 100%                                                                                                |
|    :align: center                                                                                              |    :align: center                                                                                              |
|                                                                                                                |                                                                                                                |
|    Test track imported into CARLA                                                                              |    Test track imported into SUMO                                                                               |
+----------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------+