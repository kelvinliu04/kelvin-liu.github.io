


# <span style="color:blue">Computer Vision</span>

---
## Projects:
   * [Car Counting System](#1.-Car-Counting-System)
   * [Face Mask Detection Alarm](#2.-Face-Mask-Detection-Alarm)
   * [Smart Attendance System](#3.-Smart-Attendance-System)
   * [Smart Digital Signage](#4.-Smart-Digital-Signage)
   * [Social Distancing Alarm](#5.-Social-Distancing-Alarm)

---

## 1. Car Counting System  
<img src="/images/car_counting.png" alt="car-counting">

#### Objective:  
> Counting car from CCTV perspective based on Jakarta-Indonesia road environment.   

#### Feature:  
- Edge-Computing  
- Low budget cost  
- Real-Time FPS  

#### Technical Details:  
- using NUC I5 (CPU-only)  
- using Mobilenet-V2 SSD  
- using Intel OpenVINO as an Inference  
- using Counting and Tracking (Deep-SORT) algorithm  

#### Keywords:  
*Video Surveillance, Object Detection, Object Tracking, Object Counting*  

---


## 2. Face Mask Detection Alarm  
<img src="/images/face_mask.png" alt="face-mask">

#### Objective:  
> Automatic face mask alarm for people who does not use face mask. Giving sound alert alarm and collecting information to know the awareness of citizen to use mask. This solution is needed because of Corona Virus in 2020.   

#### Feature:  
- Detect and classify face masked and non face masked
- Playing sound alert(output) as an alarm   
- Real-Time FPS  

#### Technical Details:  
- using Mobilenet-V2 SSD  
- using Intel OpenVINO as an Inference  
- using Tracking (Deep-SORT) algorithm  


#### Keywords:  
*Video Surveillance, Object Detection, Object Classification*  

---

## 3. Smart Attendance System  
#### Objective:  
> Smart attendance system in office using Face Recognition. The employees do not need to stop in front of the camera. There will be no more queue lines.  

#### Feature:  
- Recognize numerous faces in one time  
- Faces and attendances database  
- Real-Time FPS  

#### Technical Details:  
- using Intel OpenVINO as an Inference  
- using Face Detection model  
- transform image face detected into front and stright face orientation  
- using Face Reidenficiation model  

#### Keywords:  
*Video Surveillance, Object Detection, Face Recognition*  

---

## 4. Smart Digital Signage  
<img src="/images/digital_signage.png" alt="digital_signage">  

NB: This picture only demo, the real implementation documentation cannot be shared.  

#### Objective:  
> Smart digital signage is used in public place to give the right ads to the visitors.  

#### Feature:  
- Extract the metadata of the visitors  
- Classify visitors who seeing and not seeing our digital signage 
- Giving right ads to the current visitor based on age, gender and expression  
- Real-Time FPS  

#### Technical Details:  
- using Intel OpenVINO as an Inference  
- using Face Detection model  
- using Age, Gender and Expression classification model
- using Eye gazeture detection model

#### Keywords:  
*Video Surveillance, Object Detection, Metadata Classification, Eye Gazeture Detection*  

---

## 5. Social Distancing Alarm  
<img src="/images/sosdis_alrm.png" alt="sosdis-alrm">

#### Objective:  
> Automatic social distancing alarm for people who close together and crowded in public places.his solution is needed because of Corona Virus in 2020.   

#### Feature:  
- People Mapping based from CCTV view  
- Playing sound alert(output) as an alarm   
- Real-Time FPS  

#### Technical Details:  
- using Mobilenet-V2 SSD  
- using Intel OpenVINO as an Inference  
- using Tracking (Deep-SORT) algorithm  
- Transforming CCTV view perspective into Bird's view perspective
- Projecting and creating real-time Map  

#### Keywords:  
*Video Surveillance, Object Detection, Perspective Transformation*  

---