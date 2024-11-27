# **Nvidia AI Specialist Certification**

<aside>
✅ **OverView of the Project**

- Opening background information 

- General description of the current project 

- Proposed idea for enhancements to the project 

- Value and significance of this project 

- Current limitations 

- Literature review

</aside>

# Title

REAL-TIME SAFETY HELMET DETECTION SYSTEM USING YOLO FOR CONSTRUCTION SITE SAFETY MONITORING

---

# Opening background information

<aside>
✅ - Workplace safety, particularly in construction sites, remains a critical concern in industrial environments. With ongoing incidents related to non-compliance with safety helmet regulations, there is a pressing need for automated monitoring systems that can enhance safety oversight and prevent accidents.

</aside>

---


# General description of the current project

<aside>
✅ - This project develops an AI-powered real-time monitoring system using the YOLOv5 deep learning model to detect safety helmet usage among construction workers. The system identifies and tracks three key elements: persons, heads, and safety helmets, enabling automatic compliance verification with safety regulations.

</aside>

---


# **Proposed idea for enhancements to the project**

<aside>
✅ - The implementation leverages YOLOv5's capabilities for real-time processing, ensuring rapid detection and response. The system features optimized datasets for reliable detection across various environmental conditions and includes an integrated alert system for immediate notification of safety violations. The model architecture has been fine-tuned to balance accuracy with processing speed.

</aside>

---


# Value and signifiance of the project

<aside>
✅ - This system addresses the limitations of manual monitoring by providing continuous, 24/7 safety oversight. It offers significant value through accident prevention, potential reduction in workplace injuries, and decreased safety management costs. The automated approach ensures consistent monitoring without human fatigue or oversight limitations.

</aside>

---


# **Current limitations**

<aside>
✅ - The system currently faces challenges in varying lighting conditions and occluded scenarios. Performance optimization is needed for scenarios involving multiple workers in close proximity. Additionally, computing resource requirements for real-time processing need further optimization to ensure broader deployability across different hardware configurations.

</aside>

---


# **Literature review**

<aside>
✅ - Computer vision applications in safety equipment detection have evolved significantly with the advancement of deep learning technologies. The YOLO family of models has revolutionized real-time object detection, with recent developments incorporating transformer architectures for improved accuracy. Studies consistently demonstrate the effectiveness of AI-based safety monitoring systems in industrial settings, showing marked improvements in accident prevention and compliance rates.
- The integration of automated safety monitoring systems represents a significant step forward in industrial safety management, with potential applications extending beyond construction to various industrial sectors where personal protective equipment compliance is crucial.

</aside>

---

# **Dataset acquisition process**

### 1.https://universe.roboflow.com/ Go to the link

![스크린샷 2024-11-27 211828](https://github.com/user-attachments/assets/36de3ae2-b25a-47f7-9dbd-bddf2ea1a71f)


### Find the ping pong ball dataset and download the yolov5 dataset.

![스크린샷 2024-11-27 211900](https://github.com/user-attachments/assets/e0ee67a6-3ddd-454a-b814-84bc4539fadf)
![스크린샷 2024-11-27 211925](https://github.com/user-attachments/assets/6ec875a0-6cbc-4e56-8dbe-4b5d91a511c0)

### Use Google Collaboration to create code.

### 1.Google Drive integration.

### Connect to Google Drive from Google Collection.
![스크린샷(34)](https://github.com/user-attachments/assets/a7f4426b-68b5-49be-a673-c073272c07f2)


### 2. Install yolov5.
![스크린샷(47)](https://github.com/user-attachments/assets/e914556a-a768-4e79-bd89-1dfab27556cf)

### 3.Image File Management

### Creates a folder to manage image files.
![스크린샷(36)](https://github.com/user-attachments/assets/0bbb8d2e-55fb-44b8-899f-ed0b27ec426d)

### We will put the data files received from roboflow into the path accordingly.

![스크린샷(31)](https://github.com/user-attachments/assets/d7fff744-6e16-49dd-aa1f-8d72a143f434)

### You need to modify the data.yml file you received from roboflow

![스크린샷 2024-11-27 211957](https://github.com/user-attachments/assets/abee7f36-5ac8-4c9a-a3a0-b495a1ddd768)

![스크린샷(46)](https://github.com/user-attachments/assets/1684c4dc-ea7b-41a1-8a93-f866c1369c4e)
### You can put it in like the pictures above


### 4.Generates verification data.

![스크린샷(37)](https://github.com/user-attachments/assets/4f7c1df9-6864-4c13-877c-a25fbb20adca)

![스크린샷(38)](https://github.com/user-attachments/assets/59eba4c0-a985-47c6-9647-e3c4c0a34cf1)

### 5. Gets the required library.

![스크린샷(39)](https://github.com/user-attachments/assets/7b43e8ce-0892-4ec8-8a8e-1a678d8ab9c9)

![스크린샷(40)](https://github.com/user-attachments/assets/06fcbfbe-5ff1-4211-a824-c8c8571ddfb3)

### 6. Let them learn

![스크린샷(41)](https://github.com/user-attachments/assets/806bdfbf-6bf8-429b-8869-2ac7a289e62e)

### 7. learning outcome

![스크린샷 2024-11-27 213920](https://github.com/user-attachments/assets/73b891c6-4927-4633-9941-6e6ad83940d8)

![스크린샷 2024-11-27 214135](https://github.com/user-attachments/assets/aeae705f-3ec4-4e4d-a0e5-938135010d62)

![스크린샷 2024-11-27 214140](https://github.com/user-attachments/assets/3775c6ae-603d-4cae-8576-e665a010effb)

![스크린샷 2024-11-27 214144](https://github.com/user-attachments/assets/593c7ec1-b660-47a4-ac33-ceb68626e203)

![스크린샷 2024-11-27 214149](https://github.com/user-attachments/assets/ef790276-450f-4954-9490-9e93b3c8fb91)

### 8. Validate model results
python detect.py --weight runs/train/exp/weights/best.pt --source [Path of the image to be tested] --img 640 --conf 0.8
