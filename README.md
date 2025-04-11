# MTDF
# Title: MTDF: A Multi-Task-based X-ray Weld Image Detection Framework via State Space Model
This is the open source code for the paper "MTDF: A Multi-Task-based X-ray Weld Image Detection Framework via State Space Model" submitted to Automation in Construction. 

We have released our multi-task datasets soon.

# Supplementary material of Demo Video (Inspection Process)
To provide readers with a clearer understanding of the spiral steel pipe production and defect detection process, we have included a demonstration video.
You can directly click on the link [YouTube](https://youtu.be/vKmVoBKwP0Q) to watch our video. Thank you for your watching.
This is a demonstration video of MTDF method in engineering practice. We instantiate MTDF framework in the hardware platform and the constructed intelligent software. 
The proposed framework demonstrates measurable superiority over conventional manual inspection in practical deployment scenarios.  
Future research directions prioritize the deployment of this software framework within practical edge computing infrastructure, constituting a critical focus of our ongoing investigations.
# Supplementary material of Demo Video (Transmission Device)
Due to the presence of radioactivity in the testing process, we can only take photos of the returned process of the tested steel pipe in the NDT room after the testing process. The video can be viewed in the Youtube [Transmission Device](https://youtu.be/77YTBS7kYqM).Thank you for your watching. 
# Supplementary material of Demo Video (X-ray Emitter)
To better understand the acquisition principle, we recorded the actual video of the X-ray emission source and the receiver board. You can directly click on the link [X-ray Emitter](https://youtu.be/0UJoFMqeVMY) to watch our video.  A mechanical scribing device integrated with the detector housing is mounted next to the receiver plate, which makes an actual symbol marking on the steel tube surface when a defect is detected.  This synchronous defect marking protocol enhances traceability while maintaining the continuity of uninterrupted inspection.
# The other Ongoing Plans
Furthermore, a QR code tracing module is currently under development within the software ecosystem, designed to facilitate more secure and efficient quality control processes.  Specifically, this innovative module enables the generation of concise digital inspection reports when scanning QR codes affixed to individual steel pipes.  These comprehensive reports document critical quality parameters including: 1) quantitative analysis and categorical classification of manufacturing defects;  2) temporal records of defect identification;  and 3) traceable accountability through identification of responsible inspection personnel.  This dual-component system architecture establishes an auditable quality assurance mechanism while optimizing operational workflow efficiency.

# SDL/WES/DIS Dataset
Datasets  can be found at [BaiduYun Drive](https://pan.baidu.com/s/1XbtjL58-aiNg1DxeQo6hmQ?pwd=wm4e) (code: wm4e)

# system

<img width="698" alt="MTDF_系统_Elsevier" src="https://github.com/user-attachments/assets/e42f0cab-34c5-4c80-98a1-d40a740894a5" />

# Framework

<img width="615" alt="模型框架_MTDF_Elsevier_gai" src="https://github.com/user-attachments/assets/639e0942-49a8-44ff-89c2-bf09e3f9274a" />


# Main results
The main experimental results are provided in [MTDF_Results](https://pan.baidu.com/s/1o0zEplwmF3jEZj8ghe14Wg?pwd=erui) (code: erui)



# User interface
![image](https://github.com/cuiwq777/TRDM/assets/154526698/8ba32b78-daa8-4d96-938e-cd9db82515b6)

# Demo of User interface
![ezgif com-video-to-gif-converted (3)](https://github.com/cuiwq777/TRDM/assets/154526698/0a1213c3-5744-46c5-a2a7-6e7302359a0c)

# Demo of the inspection process
![ezgif com-video-to-gif-converted (4)](https://github.com/cuiwq777/TRDM/assets/154526698/2c2e5eab-8e9c-4ffe-943a-fc65c5512635)

![ezgif com-video-to-gif-converted (5)](https://github.com/cuiwq777/TRDM/assets/154526698/d51f12da-204e-4e10-b900-c5e48b4c1940)


# Training
We will make our code public soon.
1. Download the pre-trained model [VMamba-S]([https://pan.baidu.com/s/1cIX3ruaQqEG6jgb9yCWDqg](https://github.com/MzeroMiko/VMamba)
2. Modify the configuration in `train.py`
3. Run `python train.py` to start training




