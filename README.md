# Safe Integration of Automated Vehicles into Work Zones

<img src="https://github.com/PAWorkzoneAutomation/PAWorkzoneAutomation.github.io/blob/main/Documents/Images/WorkZone_v2x.png?raw=true" > 


Welcome to the Penn State wiki page for details on the Automated Driving System Workzone project. This page presents details primarily focused on the Penn State team activity. Additional details can be found at the PennDOT's public ADS page, which can be found [here](https://www.penndot.gov/ProjectAndPrograms/ResearchandTesting/Autonomous%20_Vehicles/Pages/ADS-Demonstration.aspx)

# Table of Contents
<details open>
  <summary> Click to see/unsee </summary>
  <ol>
    <li>
        <a href="#project-vision-mission-goals-and-objectives">Project Vision, Mission, Goals, and Objectives</a>
        This introduces the project vision, mission, goals and objectives.
    </li>
    <li>
        <a href="#coordinate-systems-used-for-large-area-spatial-simulations">The Motivation for the Safe Integration of Automated Vehicles into Work Zones</a>
        This introduces the motivation for the Safe Integration of Automated Vehicles into Work Zones.
    </li>
    <li>
        <a href="#team-members">Team Members</a> 
        The introduces Penn State team members.
    </li>
    <li>
        <a href="#project-activity-by-year">Project activity by year</a>
        This categorizes project activity by year.
    </li>
    <li>
        <a href="#project-activity-by-topic">Project activity by topic</a>
        This categorizes project activity by topic.
    </li>
    <li>
        <a href="#project-activity-by-modality">Project activity by modality</a>
        This categorizes project activity by modality (Simulation,Test Track, or Field Data).
    </li>
    <li>
        <a href="#project-activity-by-topic">Project activity by member</a>
        This categorizes project activity by member.
    </li>
  </ol>
</details>

# Project Vision, Mission, Goals, and Objectives
***
This section introduces the project vision, mission, goals and objectives. Please click to see details.
<details closed> 
<summary> Click to see/unsee </summary>
Vision – Enable automated vehicles to safely operate in work zones without human intervention.

Mission – Reduce traffic fatalities and increase mobility for all Americans in work zones through automated vehicles.

Goals – Achieve safe navigation of automated vehicles within work zones.

Objectives of this project:
1. Evaluate the impact of improved connectivity between the AVs and the work zone artifacts using DSRC/C-V2X.
2. Evaluate the impact of increased visibility (machine vision) of pavement markings and work zone artifacts on AVs through innovative coatings
3. Evaluate the impact of providing high definition mapping of work zone artifacts (i.e. cones, barrels, workers, vehicles)
4. Improve the map information dissemination process from the mapping providers and/or infrastructure owners/operators to the AVs through standardization of digital mapping information for work zones.
</details>
<a href="#safe-integration-of-automated-vehicles-into-work-zones">Back to top</a>

# The Motivation for the Safe Integration of Automated Vehicles into Work Zones
***
This section introduces the motivation of this project. Please click to see details.
<details closed> 
<summary> Click to see/unsee </summary>
In 2015 there were an estimated 96,626 crashes in work zones, an increase of 7.8 percent from 2014. This makes 2015 the second year in a row that work zone crashes rose after a low of 67,887 in 2013.  For comparison, in 2009 there were 667 work zone fatalities. Crashes in highway work zones have killed at least 4,700 Americans – more than two a day – and injured 200,000 in the last five years alone. There are more than 40,000 injuries in work zones each year. About 85 percent of people killed in work zones are motorists, not workers.

In Pennsylvania, the number of work zone crashes has steadily increased since 2007. Pennsylvania has also consistently appeared in the top 10 states with the most commercial motor vehicle-related work zone crashes. 

With Autonmous Vehciles being increasingly deployed to public roads, construction zones may present challenges to these vehicles, construction zone operators, and the surrounding traffic. Construction zones, by definition, are new areas with features that did not exist earlier, that are dynamic, and that may not follow typical conventions. The AV behaviors in workzones may not follow human-driven vehicle behavior, which can confuse construction zone operators that may assume human driving behavior. And as both AVs and construction environments interact with each other, the vehicles nearby the AV may also need to respond to new behaviors. Our project intends to investigate these behaviors to improve safety in and around work zones for AVs. This is achieved by increasing identification and connectivity with work zone artifacts, improving visibility by coating pavement marking and work zone artifacts, and improving mapping of work zones.
</details>
<a href="#safe-integration-of-automated-vehicles-into-work-zones">Back to top</a>

# Team members (Penn State Only)
***
 
* Project PIs
  
  Dr. Sean Brennan  
<img src="https://github.com/ForgetfulDatabases/ForgetfulDatabases.github.io/blob/main/assets/images/brennan-sean_2017.jpg?raw=true" height = "260" width= "200">  

 


 * Students

 Maddipatla Satya Prasad   |  Wushuang Bai             | Liming Gao                | Xinyu Cao
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
<img src ="https://github.com/psuadsworkzone/psuadsworkzone.github.io/blob/main/SatyaPrasadMaddipatla.jpg?raw=true" height = "200" width= "200">  |<img src="https://github.com/psuadsworkzone/psuadsworkzone.github.io/blob/main/WushuangBai_photo.jpg?raw=true" height = "200" width= "200"> | <img src="https://user-images.githubusercontent.com/66030812/148875266-8b5677b8-01df-46fd-8fbd-e02e0ea36858.jpg?raw=true" height = "200" width= "200"> |  <img src="https://github.com/psuadsworkzone/psuadsworkzone.github.io/blob/main/XinyuCao.jpg?raw=true" height = "200" width= "200">



# Project activity by year
---
## Year 1 Planning
### Prepare mapping van systems for field testing including:
  
<details closed>
  <summary> Click to see/unsee </summary>
  <ul>
    <li> Time Synchonization: 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal">      
         FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal
      </a>
      <br>
      Methods to externally trigger FLIR cameras to external trigger signals. 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSync_ArduinoUsingGPSPPS">      
         FieldDataCollection_TypicalHardwareSetups_TimeSync_ArduinoUsingGPSPPS
      </a>
      <br>
      Producing tight time-trigger pulses (less than 20 microseconds jitter) via Arduinos. 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox">      
         FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox
      </a>
      <br>
      Producing tight time-trigger pulses (less than 20 microseconds jitter) via Arduinos.       
    </li>
    <li> Camera subsystems redesign: 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal">      
         Hardware_MappingVanHardware_Camera
      </a>
      <br>
      Remounting the cameras to improve regidity, water intrusion, and hardware faults
      <br>
      <a href="https://github.com/ivsg-psu/ivsg_master/tree/master/CameraCalibration_wiki">      
         Camera Calibration
      </a>
      <br>
      Methods used to calibrate the camera system
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox">      
         FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox
      </a>
      <br>
      Producing tight time-trigger pulses (less than 20 microseconds jitter) via Arduinos.       
    </li>
    <li> LiDAR subsystems redesign: 
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_LiDAR">      
         Hardware_MappingVanHardware_LiDAR
      </a>
      <br>
      Documents of LiDAR specs
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_LIDARs_CeptonX90Install">      
         FieldDataCollection_TypicalHardwareSetups_LIDARs_CeptonX90Install
      </a>
      <br>
      Procedure of installing CeptonX90 LiDAR
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_LIDARs_VelodyneVLP16Install">      
         FieldDataCollection_TypicalHardwareSetups_LIDARs_VelodyneVLP16Install
      </a>
      <br>
      Procedure of installing VelodyneVLP16 LiDAR       
    </li>   
    <li> Redesign of other hardware subsystems: 
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_Encoder">      
         Hardware_MappingVanHardware_Encoder
      </a>
      <br>
      Setup of encoders
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_Radar">      
         Hardware_MappingVanHardware_Radar
      </a>
      <br>
      Setup of Radar
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_PowerSystem">      
         Hardware_MappingVanHardware_PowerSystem
      </a>
      <br>
      Setup of power system   
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_GPS">      
         Hardware_MappingVanHardware_GPS
      </a>
      <br>
      Setup of GPS
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_IMU">      
         Hardware_MappingVanHardware_IMU
      </a>
      <br>
      Setup of IMU
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_SteeringSystem">      
         Hardware_MappingVanHardware_SteeringSystem
      </a>
      <br>
      Setup of steering system    
    </li>  
    <li> Data parsing: 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_ParseRawDataToDatabase">      
         FieldDataCollection_DataCollectionProcedures_ParseRawDataToDatabase
      </a>
      <br>
      Parse raw data (.bag) to raw data database
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_DataTransferWithDMS">      
      FieldDataCollection_DataCollectionProcedures_DataTransferWithDMS
      </a>
      <br>
      Transfer data to PennDOT DMS
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_AutomatingDataTransferToDMSUsingCommandLine">      
      FieldDataCollection_DataCollectionProcedures_AutomatingDataTransferToDMSUsingCommandLine
      </a>
      <br>
      Transfer data to PennDOT DMS using command line tools   
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_StitchingImagesToVideo">      
      FieldDataCollection_DataCollectionProcedures_StitchingImagesToVideo
      </a>
      <br>
      Stitching parsed images into a video
      <br>   
    </li>    
  </ul>
</details>

### Prepare tools for traffic simulation including:
<details closed>
  <summary> Click to see/unsee </summary>
  <ul>
    <li> Microscopic traffic simulation: 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA">     TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA
      </a>
      <br>
      Launch page to get started with CARLA 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO">      TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO
      </a>
      <br>
      Launch page to get started with SUMO 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation">      
      TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation
      </a>
      <br>
      Launch page to get started with CARLA-SUMO cosimulation    
    </li>
     
  </ul>
</details>

To be added:

Prepare V2x systems for comms

Prepare road-side devices for connectivity and position measurement

Develop code to parse mapping van data for work-zone objects 

Develop code that determines safety metrics for work zones (--)

(etc).

## Year 2 Simulation

### Simulating construction scenarios
<details closed>
<summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO/blob/main/Documents/Simulating%20test%20track%20in%20SUMO.pptx">
    Simulating a traffic flow on Penn State test track. 
      </a>
      <br>
    The work in this area involves information to guide how to simulate a traffic flow on Penn State test track. 
    </li>
   
  </ul>
  
To be added: 
- Set up work zone in closed track
- Map work zone
- Process/Upload map
- Conduct simulation
- Collect/Process/Upload/Analyze simulation data
</details>

## Year 3 Closed track testing
<details closed>
<summary> Click to see/unsee </summary>

To be added: 
- Conduct closed track testing
- Collect/Process/Upload/Analyze closed track test data
</details>


## Year 4 Live on-road testing
<details closed>
<summary> Click to see/unsee </summary>

To be added: 
- Set up work zone in live on-road
- Map work zone in live on-road
- Process/Upload map
- Conduct live on-road testing
- Collect/Process/Upload/Analyze live on-road testing data
</details>




# Project activity by topic
---
## Simulation:
<details closed>
  <summary> Click to see/unsee </summary>
  <ul>
    <li> Microscopic traffic simulation: 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA">     TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA
      </a>
      <br>
      Launch page to get started with CARLA 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO">      TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO
      </a>
      <br>
      Launch page to get started with SUMO 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation">      
      TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation
      </a>
      <br>
      Launch page to get started with CARLA-SUMO cosimulation    
    </li>
     
  </ul>
</details>

## Mapping:
<details closed>
  <summary> Click to see/unsee </summary>
  <ul>
    <li> Time Synchonization: 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal">      
         FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal
      </a>
      <br>
      Methods to externally trigger FLIR cameras to external trigger signals. 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSync_ArduinoUsingGPSPPS">      
         FieldDataCollection_TypicalHardwareSetups_TimeSync_ArduinoUsingGPSPPS
      </a>
      <br>
      Producing tight time-trigger pulses (less than 20 microseconds jitter) via Arduinos. 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox">      
         FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox
      </a>
      <br>
      Producing tight time-trigger pulses (less than 20 microseconds jitter) via Arduinos.       
    </li>
    <li> Camera subsystems redesign: 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal">      
         Hardware_MappingVanHardware_Camera
      </a>
      <br>
      Remounting the cameras to improve regidity, water intrusion, and hardware faults
      <br>
      <a href="https://github.com/ivsg-psu/ivsg_master/tree/master/CameraCalibration_wiki">      
         Camera Calibration
      </a>
      <br>
      Methods used to calibrate the camera system
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox">      
         FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox
      </a>
      <br>
      Producing tight time-trigger pulses (less than 20 microseconds jitter) via Arduinos.       
    </li>
    <li> LiDAR subsystems redesign: 
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_LiDAR">      
         Hardware_MappingVanHardware_LiDAR
      </a>
      <br>
      Documents of LiDAR specs
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_LIDARs_CeptonX90Install">      
         FieldDataCollection_TypicalHardwareSetups_LIDARs_CeptonX90Install
      </a>
      <br>
      Procedure of installing CeptonX90 LiDAR
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_LIDARs_VelodyneVLP16Install">      
         FieldDataCollection_TypicalHardwareSetups_LIDARs_VelodyneVLP16Install
      </a>
      <br>
      Procedure of installing VelodyneVLP16 LiDAR       
    </li>   
    <li> Redesign of other hardware subsystems: 
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_Encoder">      
         Hardware_MappingVanHardware_Encoder
      </a>
      <br>
      Setup of encoders
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_Radar">      
         Hardware_MappingVanHardware_Radar
      </a>
      <br>
      Setup of Radar
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_PowerSystem">      
         Hardware_MappingVanHardware_PowerSystem
      </a>
      <br>
      Setup of power system   
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_GPS">      
         Hardware_MappingVanHardware_GPS
      </a>
      <br>
      Setup of GPS
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_IMU">      
         Hardware_MappingVanHardware_IMU
      </a>
      <br>
      Setup of IMU
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_SteeringSystem">      
         Hardware_MappingVanHardware_SteeringSystem
      </a>
      <br>
      Setup of steering system    
    </li>  
    <li> Data parsing: 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_ParseRawDataToDatabase">      
         FieldDataCollection_DataCollectionProcedures_ParseRawDataToDatabase
      </a>
      <br>
      Parse raw data (.bag) to raw data database
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_DataTransferWithDMS">      
      FieldDataCollection_DataCollectionProcedures_DataTransferWithDMS
      </a>
      <br>
      Transfer data to PennDOT DMS
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_AutomatingDataTransferToDMSUsingCommandLine">      
      FieldDataCollection_DataCollectionProcedures_AutomatingDataTransferToDMSUsingCommandLine
      </a>
      <br>
      Transfer data to PennDOT DMS using command line tools   
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_StitchingImagesToVideo">      
      FieldDataCollection_DataCollectionProcedures_StitchingImagesToVideo
      </a>
      <br>
      Stitching parsed images into a video
      <br>   
    </li>    
  </ul>
</details>

## Workzone Instrument:
<details closed>
<summary> Click to see/unsee </summary>

To be added:
- V2X
- Smart traffic cone
- Vests
- Over head cameras
</details>


# Project activity by modality
---
## Simulation:
<details closed>
  <summary> Click to see/unsee </summary>
  <ul>
    <li> Microscopic traffic simulation: 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA">     TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA
      </a>
      <br>
      Launch page to get started with CARLA 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO">      TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO
      </a>
      <br>
      Launch page to get started with SUMO 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation">      
      TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation
      </a>
      <br>
      Launch page to get started with CARLA-SUMO cosimulation    
    </li>
     
  </ul>
</details>

## Test track
To be added
## Field test
To be added
# Project activity by member
---
## Penn State team
### Prepare mapping van systems for field testing including:
  
<details closed>
  <summary> Click to see/unsee </summary>
  <ul>
    <li> Time Synchonization: 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal">      
         FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal
      </a>
      <br>
      Methods to externally trigger FLIR cameras to external trigger signals. 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSync_ArduinoUsingGPSPPS">      
         FieldDataCollection_TypicalHardwareSetups_TimeSync_ArduinoUsingGPSPPS
      </a>
      <br>
      Producing tight time-trigger pulses (less than 20 microseconds jitter) via Arduinos. 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox">      
         FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox
      </a>
      <br>
      Producing tight time-trigger pulses (less than 20 microseconds jitter) via Arduinos.       
    </li>
    <li> Camera subsystems redesign: 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TriggerCameraUsingExternalSignal">      
         Hardware_MappingVanHardware_Camera
      </a>
      <br>
      Remounting the cameras to improve regidity, water intrusion, and hardware faults
      <br>
      <a href="https://github.com/ivsg-psu/ivsg_master/tree/master/CameraCalibration_wiki">      
         Camera Calibration
      </a>
      <br>
      Methods used to calibrate the camera system
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox">      
         FieldDataCollection_TypicalHardwareSetups_TimeSyncTriggerBox
      </a>
      <br>
      Producing tight time-trigger pulses (less than 20 microseconds jitter) via Arduinos.       
    </li>
    <li> LiDAR subsystems redesign: 
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_LiDAR">      
         Hardware_MappingVanHardware_LiDAR
      </a>
      <br>
      Documents of LiDAR specs
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_LIDARs_CeptonX90Install">      
         FieldDataCollection_TypicalHardwareSetups_LIDARs_CeptonX90Install
      </a>
      <br>
      Procedure of installing CeptonX90 LiDAR
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_TypicalHardwareSetups_LIDARs_VelodyneVLP16Install">      
         FieldDataCollection_TypicalHardwareSetups_LIDARs_VelodyneVLP16Install
      </a>
      <br>
      Procedure of installing VelodyneVLP16 LiDAR       
    </li>   
    <li> Redesign of other hardware subsystems: 
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_Encoder">      
         Hardware_MappingVanHardware_Encoder
      </a>
      <br>
      Setup of encoders
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_Radar">      
         Hardware_MappingVanHardware_Radar
      </a>
      <br>
      Setup of Radar
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_PowerSystem">      
         Hardware_MappingVanHardware_PowerSystem
      </a>
      <br>
      Setup of power system   
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_GPS">      
         Hardware_MappingVanHardware_GPS
      </a>
      <br>
      Setup of GPS
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_IMU">      
         Hardware_MappingVanHardware_IMU
      </a>
      <br>
      Setup of IMU
      <br>
      <a href="https://github.com/ivsg-psu/Hardware_MappingVanHardware_SteeringSystem">      
         Hardware_MappingVanHardware_SteeringSystem
      </a>
      <br>
      Setup of steering system    
    </li>  
    <li> Data parsing: 
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_ParseRawDataToDatabase">      
         FieldDataCollection_DataCollectionProcedures_ParseRawDataToDatabase
      </a>
      <br>
      Parse raw data (.bag) to raw data database
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_DataTransferWithDMS">      
      FieldDataCollection_DataCollectionProcedures_DataTransferWithDMS
      </a>
      <br>
      Transfer data to PennDOT DMS
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_AutomatingDataTransferToDMSUsingCommandLine">      
      FieldDataCollection_DataCollectionProcedures_AutomatingDataTransferToDMSUsingCommandLine
      </a>
      <br>
      Transfer data to PennDOT DMS using command line tools   
      <br>
      <a href="https://github.com/ivsg-psu/FieldDataCollection_DataCollectionProcedures_StitchingImagesToVideo">      
      FieldDataCollection_DataCollectionProcedures_StitchingImagesToVideo
      </a>
      <br>
      Stitching parsed images into a video
      <br>   
    </li>    
  </ul>
</details>

### Prepare tools for traffic simulation including:
<details closed>
  <summary> Click to see/unsee </summary>
  <ul>
    <li> Microscopic traffic simulation: 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA">     TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA
      </a>
      <br>
      Launch page to get started with CARLA 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO">      TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO
      </a>
      <br>
      Launch page to get started with SUMO 
      <br>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation">      
      TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation
      </a>
      <br>
      Launch page to get started with CARLA-SUMO cosimulation    
    </li>
     
  </ul>
</details>

## CMU team

## PennDOT team

## Deloitte Team

# Funding
---
This project is funded by USDOT via Pennsylvania Department of Transportation under NOFO # 693JJ319NF00001.
