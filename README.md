<p align="center">
  <a href="https://github.com/king-technologies/Project-Initiator" title="Speech Audio Data Compression Using Machine Learning Dimensionality Reduction ">
    
  </a>
</p>
<h1 align="center">🌟 Speech Audio Data Compression Using Machine Learning Dimensionality Reduction 🌟</h1>
<p align="center">Start your project with Single Command</p>

## 🚀 Main files in the project 

You are just one command away to start your next project

- **MFCC.ipynb**

- **PCA.ipynb**

- **Readme.md**

## 🦋 Prerequisite

- [Python](https://www.python.org/ "Python") Installed

- Python Basics Understanding

- Librosa library Installed

- Anaconda


## 🛠️ Description 

Audio speech data is used in many applications throughout the world. Data compression has been around for decades and is one of the most effective ways to save storage space. This study looks at the possibilities of compressing and representing an original audio data file in the storage using machine learning dimensionality reduction algorithm called the principal component analysis (PCA). After then, the reduced audio file will be compared to the original audio file size. Experiment is carried out using two different approaches. 


1. MFCC

Audio file is converted to a multi-dimensional array using MFCC.Dimensions of the multi-dimensional array are further reduced using PCA. Memory allocation for this compact audio representation is then compared with the original audio file size. However, the sound quality comparison is beyond the scope of this research.  

- Notebook will load the data file using librosa library
- MFCC feautes are created using **build_estimates** function 
- Display results for different MFCC nubers
- Recreate the audio

2. PCA

instead of using MFCC we directly used PCA with padding to convert the audio file

- Notebook will load the data file using sci.io library
- Do padding for the one dimensional audio array
- Different PCA were done and compared
- Recreate the audio

