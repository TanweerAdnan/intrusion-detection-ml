Note: Platform Constraint & Execution Instructions
This project was developed and executed entirely in Google Colab, an online Jupyter notebook environment provided by Google. Therefore, it is recommended to open and run the project exclusively in Google Colab to ensure compatibility and proper execution of all code blocks and dependencies.

Steps to Open and Run the Project in Google Colab:
* Upload the .ipynb file to Google Drive (or access the shared link if provided).

* Right-click the file in Google Drive → Click "Open with" → Choose "Google Colaboratory".

* If prompted, connect to a runtime environment by clicking "Connect" in the top-right corner.

* Ensure all required libraries (pandas, numpy, seaborn, matplotlib, scikit-learn) are available.
  These are pre-installed in Colab by default.

* If using a local dataset:

  Upload the dataset manually using the upload widget:

  *  from google.colab import files
  *  uploaded = files.upload()

  Alternatively, mount Google Drive to access files:

  *  from google.colab import drive
  *  drive.mount('/content/drive')
Run all cells sequentially using Runtime > Run all, or execute each cell step-by-step manually.

Review outputs including confusion matrix visualizations and prediction results.

🔒 Note: Do not attempt to run this notebook in local Jupyter environments without adapting file handling and execution paths accordingly
