# COS80028-S2-Foram-Aghara-102633961

# Programming Code Analysis

 

# Introduction

 

Programmers employ a variety of coding methods. Because multiple coding techniques can yield software with the same functionality, the level of code complexity may vary. Furthermore, this can be dependent on programmers' ability to build high-quality software. However, there is no clear and widespread agreement on how to define software complexity. Several studies have been undertaken on various elements of complexity, including the reason of code complexity, the usage of complexity measures, and code characteristics. In the world of cyber security, software vulnerability is a crucial concern. Machine learning (ML) approaches have been effectively employed in various real-world situations such as software vulnerability identification, virus detection, and function recognition for high-quality feature representation learning, error detection, and many more approaches.

 

# Configuration of Google Colaboratory Interface and Environment

 

As the project execution was done in Google Colaboratory, it does not require any software environment setup. Just proper connection of Google Colaboratory file with the Google Drive is mandatory and following the folder structure mentioned below is to be maintained for the successful execution of the project. Go through the below steps properly to set the files and folder structure for execution, running scripts and generating the outputs.

**Step 1:** Download the project source files in a .zip file from the GitHub repository.

**Step 2:** Open Google Drive and create new folder named “Colab Notebooks”

```

NOTE: Follow this guide if got any issues in creating new folder – [Guide to create new folder in Google Drive](https://www.ryerson.ca/content/dam/digital-media-projects/gsuite/google-folder-01-create.png)

```

**Step 3:** Open the newly created “Colab Notebooks” folder and then upload the Dataset folder and all .ipynb files   that were unzipped from the GitHub Repository.

NOTE: Follow this guide if got any issues uploading files  - [Guide to upload files in Google Drive](https://www.cbackup.com/screenshot/en/others/upload-files-to-shared-google-drive/google-drive-new-file-upload.png)

**Step 4:** Do follow the folder structure below, it should be as it is otherwise the scripts will show error while execution.

```

...
├── Colab Notebooks
... ├── Dataset
    |   ├── 1
    |   |   ├── files
    |   |   |   └── all the JavaScript source codes
    |   |   └── metadata-1.xlsx
    |   ├── 2
    |   |   ├── files
    |   |   |   └── all the JavaScript source codes
    |   |   └── metadata-2.xlsx
    |   ├── 3
    |   |   ├── files
    |   |   |   └── all the JavaScript source codes
    |   |   └── metadata-3.xlsx
    |   ├── 4
    |   |   ├── files
    |   |   |   └── all the JavaScript source codes
    |   |   └── metadata-4.xlsx
    |   ├── 5+
    |   |   ├── files
    |   |   |   └── all the JavaScript source codes
    |   |   └── metadata-5+.xlsx
    |   └── Results
    ├── Methodology-2-Evaluation.ipynb
    ├── Methodology-3.ipynb
    ├── Modelling-Testing-Methodology-1.ipynb
    ├── Modelling-Testing-Methodology-2(a.1).ipynb
    ├── Modelling-Testing-Methodology-2(a.2).ipynb
    ├── Modelling-Testing-Methodology-2(b.1).ipynb
    ├── Modelling-Testing-Methodology-2(b.2).ipynb
    └── Preprocessing-Feature Extraction.ipynb        

```

# Pre-processing and Feature Extraction

After collection and sorting of the dataset there were some pre-processing and feature extraction steps to be performed on the source codes. Below are the steps to execute the pre-processing and feature extraction script.

NOTE: For the execution of all the python scripts, the scripts must be mounted to the google drive. So, to mount colab notebook to the google drive, select the mount google drive icon in the left menu in colab notebook. Follow this guide to know how to mount google drive to colab notebook: [Guide to Mount Google Drive]( https://golangdocs.com/wp-content/uploads/2020/10/mount-drive-in-colab.png)

NOTE: Follow this guide on how to run all cells in colab notebook, and select run all option from menu: [Run Cells Guide](https://i.stack.imgur.com/735eb.png)

**Step 1: Execution of the Pre-processing and Feature extraction script.**

Open "Preprocessing-Feature Extraction.ipynb" in Google Colab and click Run all option from the Runtime in top menu.

**Step 2: Check the output of the Pre-processing and feature extraction script.**

Open “Dataset” folder and in that you will be able to find newly created “merged_dataset_processed.csv” file which indicates successful execution of the script. Also, there will be additional metadata processed csv files in each of the subfolders of 1,2,3,4 and 5+.

# Methodology 1

Methodology 1 is designed to answer the research question which states is Deep Learning or Machine Learning better in predicting number of contributors?

For the Methodology 1, you need to execute the script for that, below are the steps to execute methodology 1 script.

**Step 1: Execution of the methodology 1 script.**

Open "Modelling-Testing-Methodology-1.ipynb" in Google Colab and click Run all option from the Runtime in top menu.

**Step 2: Check the output of the methodology 1 script.**

If the execution of the script will be successful, you will be able to see some graphs at the end of the script comparing the performance of the machine learning and deep learning models.

# Methodology 2

Methodology 2 is designed to answer the research question which states for time cost analysis and prediction, is cyclomatic complexity an important feature when other code characteristics are taken into considerations?

For the Methodology 2, you need to execute the script for that, below are the steps to execute multiple scripts sequentially as mentioned in below steps.

**Step 1: Execution of the 1st script.**

Open "Modelling-Testing-Methodology-2(a.1).ipynb" in Google Colab and click Run all option from the Runtime in top menu.

**Step 2: Check the output of the 1st script.**

Open “Dataset” folder and then open “Results” folder, in that you will be able to find newly created “M2(a.1).csv” file which indicates successful execution of the 1st script.

**Step 3: Execution of the 2st script.**

Open "Modelling-Testing-Methodology-2(a.2).ipynb" in Google Colab and click Run all option from the Runtime in top menu.

**Step 4: Check the output of the 2st script.**

Open “Dataset” folder and then open “Results” folder, in that you will be able to find newly created “M2(a.2).csv” file which indicates successful execution of the 2nd script.

**Step 5: Execution of the 3rd script.**

Open "Modelling-Testing-Methodology-2(b.1).ipynb" in Google Colab and click Run all option from the Runtime in top menu.

**Step 6: Check the output of the 3rd script.**

Open “Dataset” folder and then open “Results” folder, in that you will be able to find newly created “M2(b.1).csv” file which indicates successful execution of the 3rd script.

**Step 7: Execution of the 4th script.**

Open "Modelling-Testing-Methodology-2(b.2).ipynb" in Google Colab and click Run all option from the Runtime in top menu.

**Step 8: Check the output of the 4th script.**

Open “Dataset” folder and then open “Results” folder, in that you will be able to find newly created “M2(b.2).csv” file which indicates successful execution of the 4th script.

**Step 9: Execution of the methodology 2 evaluation script.**

Open "Methodology-2-Evaluation.ipynb" in Google Colab and click Run all option from the Runtime in top menu.

**Step 10: Check the output of the methodology 2 evaluation script.**

If the execution of the script will be successful, you will be able to see some graphs in the script comparing the performance of the machine learning and deep learning models using different cases and also maximum performance accuracy of models with and without cyclomatic complexity feature.

# Methodology 3

Methodology 3 is designed to answer the research question which states how is time cost of code, cyclomatic complexity, other code characteristics and number of contributors related to each other?

For the Methodology 3, you need to execute the script for that, below are the steps to execute methodology 3 script.

**Step 1: Execution of the methodology 3 script.**

Open "Methodology-3.ipynb" in Google Colab and click Run all option from the Runtime in top menu.

**Step 2: Check the output of the methodology 3 script.**

If the execution of the script will be successful, you will be able to see one heatmap and 2 scatter plot graphs in the script comparing the correlation of the different code characteristics.
