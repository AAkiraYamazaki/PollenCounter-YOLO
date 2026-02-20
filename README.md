# PollenCounter-YOLO

Deep learning–based inference tool for pollen germination rate and viability estimation from microscopic images.


> ⚠ License Notice  
> This project is based on YOLOv5 by Ultralytics and is distributed under the GNU General Public License v3.0 (GPL-3.0).  
> Modifications have been made to the original training and inference workflow. See the LICENSE file for details.  


## 🚀 Run on Google Colab (No installation required)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/AAkiraYamazaki/PollenCounter-YOLOv5/blob/main/colab/PollenCounter_YOLOv5.ipynb)

Click the button above and run all cells.

## 📌 What this repository provides
		•	✅ Trained weights for:
	    	Pollen germination model
	    	Pollen viability model
		• 	✅ Modified inference pipeline supporting merged multi-dataset result export

		•	✅ Executable Google Colab notebook

## 🔧 About the YOLOv5 Base

This repository is derived from YOLOv5 (Ultralytics), originally released under the GPL-3.0 license.  

Original repository:  
https://github.com/ultralytics/yolov5  

Modifications in this project include:  
	•	Customized output format for pollen trait quantification  
	•	Added functionality to merge multiple datasets into unified result files  
	•	Adjusted inference pipeline for pollen germination and viability estimation  

All modifications are released under GPL-3.0 in accordance with the original license.  

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

## 📜 License

This repository is distributed under the GNU General Public License v3.0 (GPL-3.0).  

A copy of the license is provided in the LICENSE file.  
This project includes modified components of YOLOv5, which is also licensed under GPL-3.0.  

## 🙏 Acknowledgments

This research was supported by the Research and implementation promotion program through open innovation grants (JPJ011937) from the Project of the Bio-oriented Technology Research Advancement Institution (BRAIN).
