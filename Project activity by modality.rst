.. test documentation master file, created by
   sphinx-quickstart on Tue Dec 13 19:15:30 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Project activity by modality
================================

Traffic and Vehicle Simulation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: Images/ADS_overview_diagram.png

* `TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA`_: Launch page to get started with CARLA. (IVSG - PSU internal)
* `TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO`_:Launch page to get started with SUMO. (IVSG - PSU internal) 
* `TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation`_: Launch page to get started with CARLA-SUMO cosimulation. (IVSG - PSU internal) 

* The following table shows the three roadway situations for the simulation: urban, artirial and highway, including the location we picked in State College and the corresponding data link.

.. csv-table:: 3 Situations Sumamry
   :file: tables/three_situations.csv
   :header-rows: 1

* The following table shows the summary about whether the considered three roadway situations could be applied to each of the proposed 20 scenarios. 

.. csv-table:: 20 Scenarios - 3 Situations Sumamry
   :file: tables/20scenarios.csv
   :header-rows: 1

The data flow of the simulation is below: 

.. image:: Images/PennDOT_Simulation_Workflow_V2.drawio.png

Simulating construction scenarios:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
* `Simulating a traffic flow on Penn State test track`_: The work in this area involves information to guide how to simulate a traffic flow on Penn State test track. (IVSG - PSU internal)

.. image:: Images/simulateFlowOnTrack.png

* The following table shows the three roadway situations for the simulation: urban, artirial and highway, including the location we picked in State College and the corresponding data link.

.. csv-table:: 3 Situations Sumamry
   :file: tables/three_situations.csv
   :header-rows: 1

* The following table shows the summary about whether the considered three roadway situations could be applied to each of the proposed 20 scenarios. 

.. csv-table:: 20 Scenarios - 3 Situations Sumamry
   :file: tables/20scenarios.csv
   :header-rows: 1

Simulation post processing:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
* `FeatureExtraction_Association_PointToPointAssociation`_: Functions are provided to determine matches between data sets of (X,Y) points, store and compare groups of associated points (patch objects), and determine intersections between patch objects and circular arcs (useful for collision detection).

.. image:: Images/fcn_Points_fillPointSampleSets_Ex3.jpg

* `FeatureExtraction_SafetyMetrics_SafetyMetricsClass`_: MATLAB code implementation of functions that perform safety metric calculations given a set of objects and a path through them.

.. figure:: Images/TTC.png
   :align: center

   Time to collision

.. figure:: Images/lanechange.gif
   :align: center

   Demo of vehicle doing a lane change


Test track
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
To be added

Field test
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
To be added














.. _Simulating a traffic flow on Penn State test track: https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO/blob/main/Documents/Simulating%20test%20track%20in%20SUMO.pptx
.. _TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation: https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation
.. _TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO: https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO
.. _TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA: https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA
.. _Mapping_MappingVan_About: https://connectedvehicles.psu.edu/
.. _Mapping_CoordinateSystems_WideAreas: https://github.com/PAWorkzoneAutomation/TrafficSimulators_WideAreaCoordinateSystems
.. _DataProcessing_GPS_GPSConversionMethods: https://github.com/PAWorkzoneAutomation/FieldDataCollection_GPSRelatedCodes_GPSClass
.. _FieldDataCollection_DataCollectionProcedures_StitchingImagesToVideo: https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_StitchingImagesToVideo
.. _FieldDataCollection_DataCollectionProcedures_AutomatingDataTransferToDMSUsingCommandLine: https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_AutomatingDataTransferToDMSUsingCommandLine
.. _FieldDataCollection_DataCollectionProcedures_DataTransferWithDMS: https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_DataTransferWithDMS
.. _FieldDataCollection_DataCollectionProcedures_ParseRawDataToDatabase: https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_ParseRawDataToDatabase
.. _FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal: https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal
.. _FieldDataCollection_TypicalHardwareSetups_TimeSync_ArduinoUsingGPSPPS: https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSync_ArduinoUsingGPSPPS
.. _FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox: https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox
.. _Hardware_MappingVanHardware_Camera: https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal
.. _Camera Calibration: https://github.com/ivsg-psu/ivsg_master/tree/master/CameraCalibration_wiki
.. _Hardware_MappingVanHardware_LiDAR: https://github.com/ivsg-psu/Hardware_MappingVanHardware_LiDAR

.. _FieldDataCollection_TypicalHardwareSetups_LIDARs_VelodyneVLP16Install: https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_LIDARs_VelodyneVLP16Install
.. _Hardware_MappingVanHardware_Encoder: https://github.com/ivsg-psu/Hardware_MappingVanHardware_Encoder
.. _Hardware_MappingVanHardware_Radar: https://github.com/ivsg-psu/Hardware_MappingVanHardware_Radar
.. _Hardware_MappingVanHardware_PowerSystem: https://github.com/ivsg-psu/Hardware_MappingVanHardware_PowerSystem
.. _Hardware_MappingVanHardware_GPS: https://github.com/ivsg-psu/Hardware_MappingVanHardware_GPS
.. _Hardware_MappingVanHardware_IMU: https://github.com/ivsg-psu/Hardware_MappingVanHardware_IMU
.. _Hardware_MappingVanHardware_SteeringSystem: https://github.com/ivsg-psu/Hardware_MappingVanHardware_SteeringSystem

.. _FieldDataCollection_TypicalHardwareSetups_LIDARs_CeptonX90Install: https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_LIDARs_CeptonX90Install
.. _FieldDataCollection_VisualizingFieldData_PlotWorkZone: https://github.com/ivsg-psu/FieldDataCollection_VisualizingFieldData_PlotWorkZone

.. _Hardware_MappingVanHardware_CADdrawings: https://github.com/ivsg-psu/Hardware_MappingVanHardware_CADdrawings
.. _FieldDataCollection_GPSRelatedCodes_RTKCorrectionService: https://github.com/ivsg-psu/FieldDataCollection_GPSRelatedCodes_RTKCorrectionService
.. _FeatureExtraction_Association_PointToPointAssociation: https://github.com/ivsg-psu/FeatureExtraction_Association_PointToPointAssociation
.. _FeatureExtraction_SafetyMetrics_SafetyMetricsClass: https://github.com/ivsg-psu/FeatureExtraction_SafetyMetrics_SafetyMetricsClass