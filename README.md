# Arthritis_Classification

### Purpose
관절염 수술을 위해 한국에 방문하는 관광객이 늘어나고 있음 
해외환자유치를 위해 의사가 직접 해외로 나가 진료를 보거나 원격진료로 환자유치를 대신하고 있음 
한국과는 달리 개개인이 DICOM파일 혹은 간단한 JPEG, PNG 엑스레이 사진을 가지고 있으며 에이전시 혹은 개인이 한국 정형외과에 직접 문의하는 경우가 있음 
환자의 병원접근성과 마케팅을 위해 웹기반 UI를 제작하여, 엑스레이사진과 간단한 데이터(이름, 나이, 증상, 연락처)를 입력하면 데이터베이스에 저장이 되고, 환자는 자신의 엑스레이를 통해 관절염의 단계를 판단한 후 바로 한국의 병원에 문의를 할 수 있는 플랫폼을 만들고자 함
해당 연구는 웹UI를 만드는 것이 아닌 딥러닝을 학습시켜 관절염의 정도를 파악하고자 함

### Data
https://www.kaggle.com/tommyngx/kneeoa


### Preprocessing
Using U-net
Segmentation - By Proreator

### Classification Methodology
VG616 
Pretrained VGG16 + Random Forest Classification 

### 
