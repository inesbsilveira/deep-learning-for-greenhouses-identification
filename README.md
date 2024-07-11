# Deep Learning Application for Identifying Greenhouses in Sentinel-2 Images in Southwestern Alentejo
Inês Silveira - Instituto Superior de Agronomia, 2023

## Overview
This project focuses on the development of a deep learning algorithm to identify greenhouses in Sentinel-2 satellite images in the Southwestern Alentejo region, specifically within the Natural Park of Southwestern Alentejo and Costa Vicentina (PNSACV) and the Mira Irrigation Perimeter (PRM). Plastic greenhouses in agriculture have significantly increased in recent years due to their advantages in climate control for growing vegetables and fruits. However, this growth brings environmental and social challenges, including water scarcity, plastic waste management, and labor migration issues.

## Project Motivation
Manual mapping of greenhouses is time-consuming and inefficient. This project aims to automate the identification process using image segmentation techniques with a U-net deep learning model, achieving high accuracy in detecting greenhouses from Sentinel-2 satellite images. The project leverages greenhouse maps obtained through photo identification and Sentinel-2 images using bands B2 and B8, along with the NDVI (Normalized Difference Vegetation Index).

## Challenges
One of the key challenges in using Sentinel-2 images is the spectral signature of plastic structures, which can be confused with other types of land cover. Spatial context is crucial, which is implicitly utilized through these deep learning techniques.

## Prerequisites
Python 3.8 or higher\
Required Python packages (listed in requirements.txt)
