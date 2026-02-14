# PollenCounter-YOLOv5

Deep learning–based inference tool for pollen germination rate and viability estimation from microscopic images.

## 🚀 Run on Google Colab (No installation required)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/AAkiraYamazaki/PollenCounter-YOLOv5/blob/main/PollenCounter_YOLOv5.ipynb)

Click the button above and run all cells.

## 📌 What this repository provides
	•	✅ Trained weights for:
	    	Pollen germination model
	    	Pollen viability model
	•	✅ Executable Google Colab notebook

## 📷 Input Image Requirements
	•	Microscopic image (JPG or PNG)
	•	Recommended resolution: 640px (long side)
	•	Bright-field microscope images

## 📊 Output

The model automatically:  
	•	Detects pollen grains  
  
Classifies them as:  
	•	Germinated / Non-germinated  
	•	Viable / Non-viable  
  
Calculates:  
	•	Pollen germination rate (%)  
	•	Pollen viability (%)  

## 📂 How to Use (Step-by-step)
	1.	Open Colab
	2.	Upload your microscopic image
	3.	Select model type:
	      •	Germination
	      •	Viability
	4.	Run inference
	5.	Download result image and CSV summary

## 🔬 Model Information

Architecture: YOLOv5m  
Framework: PyTorch  
Training image size: 640 px  

## 📖 Citation

If you use this model, please cite:  

  *Akira Yamazaki, Natsuki Uematsu, Taro Sano, Yoshito Tatsumi, Keiji Mine, Hiroshi Asao, Haruyuki Atsumi, Yuhei Ueda, Ginyu Inaba, Kyosuke Kawabe, Kenichiro Yasuba, Yuichi Yoshida.
Deep learning–based phenotyping of strawberry pollen reproductive capacity robust to imaging conditions enables multi-site analysis of environmental influences. Under Review.*


## 🙏 Acknowledgments

This research was supported by the Research and implementation promotion program through open innovation grants (JPJ011937) from the Project of the Bio-oriented Technology Research Advancement Institution (BRAIN).
