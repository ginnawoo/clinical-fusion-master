# clinical-fusion-master

NOTE: Original adaptation from Combining structured and unstructured data for predictive models: a deep learning approach ([clinical-fusion](https://github.com/onlyzdd/clinical-fusion)).

Healthcare industries have access to vast amounts of data that can be used to improve patient outcomes and care. Specifically, EHRs contain a large amount of patient information in both structured (e.g. patient demographics, vital signs, lab tests) and unstructured (e.g. clinical notes) data format. However, most existing predictive modeling research focuses on using only structured data or unstructured data. While structured data is easily quantifiable and analyzable, unstructured data contains nuanced information that, when properly interpreted, offers a deeper insight into patient conditions and outcomes. The challenge, however, lies in effectively integrating these disparate data types to leverage their full potential in enhancing predictive modeling in healthcare.

This research seeks to address the development of effective methods to fuse and learn from structured and unstructured EHR data to improve patient representation and risk prediction of important clinical outcomes such as in-hospital mortality, 30-day hospital readmission, and long-length of stay prediction [1]. It proposes two innovative deep learning frameworks, Fusion-CNN (Convolutional Neural Network) and Fusion-LSTM (Long Short-Term Memory), designed to harness the complementary strengths of sequential clinical notes (unstructured data) and temporal signals (structured data). By fusing these data modalities, the proposed models aim to capture a more comprehensive picture of patient health trajectories.

## Cloning the Repository Locally

Clone the Repository:
Open a terminal or command prompt and run the following command:

```bash
git clone https://github.com/ginnawoo/clinical-fusion-master.git
```
## Uploading to Google Drive
To use the files in Google Colab, you need to upload them to your Google Drive.

1. Open your Google Drive: Go to drive.google.com.

2. Create a new folder (optional): For better organization.

3. Upload the cloned repository: Drag and drop the "clinical-fusion-master" folder to Google Drive.

## Using Google Colab
Follow the steps to run the notebook in Google Colab: CS589_DLH_Team_42.ipynb

## Authors
- Ginna Woo
- Zongyu Li
- Xuanwei Liu
