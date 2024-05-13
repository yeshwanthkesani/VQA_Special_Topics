# Project Overview

We got our dataset from Yeshiva University’s deep learning course and creating an advanced multimodal VQA model are the two goals of this work, which falls under the category of Visual Question Answering (VQA). Natural language processing and computer vision groups have both shown a great deal of interest in Visual Question Answering (VQA), in part because it provides insight into the connections between two crucial sources of data. Existing datasets and the models constructed from them have concentrated on answering questions that can be resolved by analyzing the query and image separately. Each notebook is dedicated to a specific model or a variant of the Pix2Struct and Blip-Clip models.

## Notebooks Description

### `clip-blip-model.ipynb`

- **Purpose**: This notebook explores the integration of CLIP and BLIP models for enhanced image understanding and text generation. 
- **Features**: It includes model loading, data preprocessing, visualization of model outputs, and performance evaluation metrics.
- **Usage**: Ideal for understanding how combined models work in processing and answering visual questions.

### `pix2struct-Base.ipynb`

- **Purpose**: Focuses on the base version of the Pix2Struct model, examining its fundamental architectural components and performance.
- **Features**: Includes detailed steps for model setup, training procedures, evaluation, and visualization of results.
- **Usage**: Use this notebook to replicate the basic experiments or as a foundation for further experimentation with the Pix2Struct model.

### `pix2struct_7b.ipynb`

- **Purpose**: Dedicated to a smaller variant of the Pix2Struct model, known as Pix2Struct-7B, which is optimized for faster computations.
- **Features**: Outlines the adjustments made to the base model to enhance speed and efficiency, and compares performance metrics with the base model.
- **Usage**: Best for scenarios where computational resources are limited or where quick prototyping is required.

## Getting Started

To run these notebooks:
1. Ensure that Python 3.x is installed on your machine.
2. Install Jupyter Notebook or JupyterLab:


## Example Dataset
Our Dataset consists of instructions, response, category, week, page, context.
![image](https://github.com/yeshwanthkesani/VQA_Special_Topics/assets/150316790/892573ec-0de8-41b2-ba73-2d9e789e0cfc)

## Dataset Distribution
![image](https://github.com/yeshwanthkesani/VQA_Special_Topics/assets/150316790/62e33b05-a455-4d6c-a5d1-176071f2d312)


## Before Training
![image](https://github.com/yeshwanthkesani/VQA_Special_Topics/assets/150316790/a9d6b22a-62a7-4e01-adf7-4ccb1a812533)

## After Training 
![image](https://github.com/yeshwanthkesani/VQA_Special_Topics/assets/150316790/fbfe65a0-d2f8-4fa3-baa5-081504d552b3)


