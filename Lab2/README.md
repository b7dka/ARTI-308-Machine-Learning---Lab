# Lab 2: Phishing Email Detection Methodology

## 1. Problem Statement
[cite_start]This project addresses a **Classification** problem[cite: 7]. [cite_start]The goal is to develop a machine learning model that predicts whether an email is a "Phishing Email" or a "Safe Email" based on its content[cite: 22, 31].

## 2. Dataset Description
* [cite_start]**Source:** Kaggle (Phishing Email Dataset)[cite: 14].
* [cite_start]**Shape:** 18,650 rows and 3 columns[cite: 37].
* [cite_start]**Target Variable:** 'Email Type' (Safe Email vs. Phishing Email)[cite: 9, 30].
* [cite_start]**Features:** 'Email Text' content[cite: 39].

## 3. Methodology
As illustrated in the methodology diagram, the workflow follows these stages:
* [cite_start]**Data Collection & Loading:** Loading the CSV dataset using Pandas[cite: 36, 44, 45].
* [cite_start]**Text Preprocessing:** Cleaning the email text for analysis[cite: 46].
* [cite_start]**Model Training:** Using classification algorithms to learn patterns[cite: 48].
* [cite_start]**Evaluation:** Measuring performance through accuracy and other metrics[cite: 49, 50].
