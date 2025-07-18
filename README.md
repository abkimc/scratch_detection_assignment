# Scratch Detection Assignment

This repository contains a data science assignment focused on detecting scratches on semiconductor wafers using wafer map data. The goal is to automate the detection process to improve quality control and efficiency in semiconductor manufacturing.

<img src="assets/NI_logo.png" width="100" height="100" alt="NI Logo">

---

## Table of Contents

- [Introduction](#introduction)
- [Assignment Overview](#assignment-overview)
- [Data Description](#data-description)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling and Evaluation](#modeling-and-evaluation)


---

## Introduction

In the semiconductor industry, wafers are thin discs used to fabricate microelectronic devices. Identifying and isolating defects such as scratches is crucial, as these can affect the performance and reliability of the devices.

A scratch is defined as an elongated cluster of bad dies with a high aspect ratio, potentially caused by equipment misalignment, handling errors, etc. Manual scratch detection is expensive and error-prone; automating this process is the primary business goal.

## Assignment Overview

You are provided with wafer map data and tasked with building a model to predict whether a given die belongs to a scratch. The assignment includes both training and test datasets.

**Business Goals:**
- Automate scratch detection to save time and reduce errors.
- Improve die quality while balancing yield.
- Enable both die-level and wafer-level predictions.

## Data Description

Each record in the dataset includes:
- `WaferName`: Identifier for each wafer.
- `DieX`: Horizontal position of the die.
- `DieY`: Vertical position of the die.
- `IsGoodDie`: Boolean, indicating if the die is good.
- `IsScratchDie`: Boolean, indicating if the die is part of a scratch (provided only in training data).

**Files:**
- `wafers_train.csv`: Training data with labels.
- `wafers_test.csv`: Test data without scratch labels.
- `data.zip`: Contains both train and test CSVs.
- `scratch_detection_assignment.ipynb`: Main notebook for analysis and modeling.
- `assets/`: Folder containing images for visualization.
