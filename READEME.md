# Cross Lingual Style Transfer for Soliga: A low resource Tribal language of India with abstract

Voice conversion is the art of mimicking different speaker voices and styles. In this paper, we present a cross-lingual speaker style adaptation based on a multi-scale loss function, using a deep learning framework for syntactically similar languages Kannada and Soliga, under a low resource setup. The existing speaker adaptation methods usually depend on monolingual data and cannot be directly adopted for cross-lingual data.

## Overview

This repository contains the code and trained models for the paper "Cross Lingual Style Transfer for Soliga: A low resource Tribal language of India with abstract" published in [Interspeech 2023](https://www.interspeech2023.org/).

## Methodology

We propose a method that calculates multi-scale reconstruction loss on the mel-spectrogram generated with that of the original mel-spectrogram and adopts its weights based on the loss function for various scales. Extensive experimental results illustrate that the multi-scale reconstruction resulted in a significant reduction of generator noise compared to the baseline model and faithfully transfers Soliga speaker styles to Kannada speakers while retaining the linguistic aspects of Soliga.

## Data

The low resource dataset used in this paper consists of X hours of speech data from Y speakers in Soliga and Kannada. Due to data privacy restrictions, we cannot release the dataset publicly. However, we provide the code for data preprocessing and feature extraction.

## Usage

The code for our experiments is available in the `src` directory. Detailed instructions for replicating our experiments are provided in the README file of the directory.


## Results

We report the following results:

- Comparison with existing methods
- Multi-scale reconstruction results

## Citation

If you use our code or models in your research, please cite our paper:
