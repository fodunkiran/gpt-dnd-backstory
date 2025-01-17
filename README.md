# gpt-dnd-backstory


## Overview

This project involves analyzing character bios from a fantasy setting using Python and pandas. The primary aim is to clean, manipulate, and analyze a dataset containing character names, races, classes, and backstories. Additionally, the project explores the fine-tuning of a GPT model to generate character stories based on the dataset.

## Table of Contents

- [Installation](#installation)
- [Data](#data)
- [Analysis Steps](#analysis-steps)
- [Fine-Tuning GPT](#fine-tuning-gpt)
- [Results](#results)

## Installation

To run this project, ensure you have Python installed. You will also need the following packages:

- pandas
- openpyxl (for reading Excel files)
- transformers (for fine-tuning GPT)

## Data
The dataset used in this project is an Excel file named dd_bios.xls, which contains character bios in the following format:

Timestamp: The time of entry
Character's Name: Name of the character
Character's Race: Race of the character (e.g., human, elf, dwarf)
Character's Class: Class of the character (e.g., rogue, wizard, cleric)
Character's Backstory: A narrative detailing the character’s background and motivations

## Analysis Steps
Loading Data: The dataset is loaded using pandas.
Data Cleaning:
- Dropped unnecessary columns (e.g., Timestamp).
- Renamed columns for clarity.
- Removed rows with missing values.
- Cleaned backstory text (removed HTML tags and links).
- Data Exploration: Analyzed character counts and displayed backstories.

## Fine-Tuning GPT
In this project, we also explore the fine-tuning of a GPT model to generate character stories. The steps involved are:

Preparing the Dataset: Format the character backstories into a suitable format for training.
Fine-Tuning: Use the transformers library to train the GPT model on the character backstories.
Generating New Characters: After fine-tuning, generate new character stories based on prompts.

## Results
The project outputs a cleaned dataset ready for analysis. The backstories provide insights into character development and narrative depth, which can be further explored for storytelling or game design purposes. The fine-tuned GPT model can also generate new and unique character stories.
