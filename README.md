
# Music Genre Classification using Gammatonegram and Transfer Learning  

This project is a machine learning application designed to classify music into genres using audio features extracted as gammatonegrams. It employs transfer learning techniques to leverage pre-trained models for improved accuracy and performance.  

## Table of Contents  
1. [Overview](#overview)  
2. [Dataset](#dataset)  
3. [Features](#features)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Contributing](#contributing)  

## Overview  
The goal of this project is to identify the genre of a given music track. Using gammatonegram representations of audio and transfer learning, the model can effectively analyze patterns and classify the music into various genres such as rock, pop, jazz, and more.  

## Dataset  
The project uses the [GTZAN Dataset for Music Genre Classification](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/code). This dataset includes 1,000 audio tracks across 10 genres, each 30 seconds long.  

## Features  
- **Gammatonegram Extraction:** Converts audio signals into gammatonegram representations, which capture important spectral and temporal features.  
- **Transfer Learning:** Utilizes pre-trained models to enhance classification performance.  
- **Genre Classification:** Predicts the genre of a given audio sample.  

## Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/music-genre-classification.git  
   cd music-genre-classification  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

## Usage  
1. Prepare the dataset: Download the GTZAN dataset and extract the files into the `data/` folder.  
2. Run the preprocessing script to generate gammatonegrams:  
   ```bash  
   python preprocess.py  
   ```  
3. Train the model:  
   ```bash  
   python train.py  
   ```  
4. Test the model:  
   ```bash  
   python test.py  
   ```  

## Contributing  
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.  

