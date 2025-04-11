# MTDF
# Title: MTDF: A Multi-Task-based X-ray Weld Image Detection Framework via State Space Model
This is the open source code for the paper "MTDF: A Multi-Task-based X-ray Weld Image Detection Framework via State Space Model" submitted to Automation in Construction. 

We have released our multi-task datasets soon.

# Supplementary material of Demo Video
You can directly click on the link [YouTube](https://youtu.be/vKmVoBKwP0Q) to watch our video. Thank you for your watching.
This is a demonstration video of MTDF method in engineering practice. Currently, our method is in the experimental stage.
We instantiate MTDF framework in the hardware platform and the constructed intelligent software. 
The proposed framework demonstrates measurable superiority over conventional manual inspection in practical deployment scenarios.  
This implementation significantly enhances the objectivity of inspection procedures.  
# Ongoing Plans
Furthermore, a QR code tracing module is currently under development within the software ecosystem, designed to facilitate more secure and efficient quality control processes.  Specifically, this innovative module enables the generation of concise digital inspection reports when scanning QR codes affixed to individual steel pipes.  These comprehensive reports document critical quality parameters including: 1) quantitative analysis and categorical classification of manufacturing defects;  2) temporal records of defect identification;  and 3) traceable accountability through identification of responsible inspection personnel.  This dual-component system architecture establishes an auditable quality assurance mechanism while optimizing operational workflow efficiency.

# SDL/WES/DIS Dataset
Datasets  can be found at [BaiduYun Drive](https://pan.baidu.com/s/1XbtjL58-aiNg1DxeQo6hmQ?pwd=wm4e) (code: wm4e)

# system

<img width="698" alt="MTDF_系统_Elsevier" src="https://github.com/user-attachments/assets/e42f0cab-34c5-4c80-98a1-d40a740894a5" />


# Framework


<img width="615" alt="模型框架_MTDF_Elsevier_gai" src="https://github.com/user-attachments/assets/639e0942-49a8-44ff-89c2-bf09e3f9274a" />


# Main results
The main experimental results are provided in [BaiduYun Drive](https://pan.baidu.com/s/1-qM-CVTsBcnjglNJwNkLyQ?pwd=w4ho) (code: w4ho)

# Training
1. Download the pre-trained model Swin-T [BaiduYun Drive](https://pan.baidu.com/s/1cIX3ruaQqEG6jgb9yCWDqg) (code: 6686)
2. Modify the configuration in `main.py`
3. Run `python main.py` to start training
# Testing
1. Modify the configuration in `main.py` and `utils.py`
2. Run `python main.py` to start testing

This paper improves and innovates on the basis of RCN.


