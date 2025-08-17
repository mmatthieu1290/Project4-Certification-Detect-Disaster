<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# PROJECT4-CERTIFICATION-DETECT-DISASTER

<em>Detect Disasters Fast, Save Lives Instantly</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/mmatthieu1290/Project4-Certification-Detect-Disaster?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/mmatthieu1290/Project4-Certification-Detect-Disaster?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/mmatthieu1290/Project4-Certification-Detect-Disaster?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)

---

## Overview

Project4-Certification-Detect-Disaster is a comprehensive framework that leverages machine learning to identify disaster-related tweets, enabling automated social media monitoring and rapid response. The tool integrates data preprocessing, model training, and prediction steps into a seamless pipeline suitable for real-time or batch analysis.

**Why Project4-Certification-Detect-Disaster?**

This project aims to simplify disaster detection on social media platforms. The core features include:

- **🧩** **Data Preprocessing:** Cleans and prepares raw tweet data for analysis.
- **🚀** **Model Training:** Utilizes labeled datasets to build accurate classifiers.
- **🔍** **Prediction & Classification:** Automates the identification of disaster-related content.
- **⏱️** **Real-time & Batch Support:** Offers flexible deployment options for timely alerts.
- **🔧** **Modular Architecture:** Easily extendable for custom use cases.

**Video link:** https://share.vidyard.com/watch/f2FMJX9CcXhMZCcdWjo1Zj?

---

## Description of the files.

**Version_finale_projet1_Matthieu_Marechal.ipynb:** code

**train.csv:** labeled database which contains 7613 tweets. The column "target" is equal to 1 if the tweet is relative to a disaster, else 0. The column "text" contains the tweet, "keyword" contains one or two words related to the tweet (less than 1% of missing values) and "location" contains two many missing values.

**test.csv:** unlabeled database with same features that train.csv.

**sample_submission.csv:** prediction on test.csv.

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** JupyterNotebook

### Installation

Build Project4-Certification-Detect-Disaster from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/mmatthieu1290/Project4-Certification-Detect-Disaster
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Project4-Certification-Detect-Disaster
    ```

3. **Install the dependencies:**

echo 'INSERT-INSTALL-COMMAND-HERE'

### Usage

Run the project with:

echo 'INSERT-RUN-COMMAND-HERE'

### Testing

Project4-certification-detect-disaster uses the {__test_framework__} test framework. Run the test suite with:

echo 'INSERT-TEST-COMMAND-HERE'

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
