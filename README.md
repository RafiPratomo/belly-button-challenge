# Belly Button Biodiversity Dashboard

This repository contains a web-based dashboard to visualize and explore the Belly Button Biodiversity dataset using D3.js and Plotly.js.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Introduction

The Belly Button Biodiversity Dashboard is an interactive web application designed to help users explore the dataset related to belly button biodiversity. The dashboard includes visualizations like bar charts and bubble charts to represent the data effectively.

## Features

- Dropdown menu to select different test subject IDs.
- Horizontal bar chart displaying the top 10 Operational Taxonomic Units (OTUs) found in the selected individual.
- Bubble chart showing the distribution of OTUs for each sample.
- Demographic information panel for the selected test subject.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bellybutton-biodiversity.git
   cd bellybutton-biodiversity
   ```
2. Ensure you have a local server to serve the HTML file, such as http-server for Node.js
3. Open your browser and navigate to the local server URL (e.g., http://127.0.0.1:8080)
4. Interact with the dashboard by selecting different test subject IDs from the dropdown menu.

## Dependencies

D3.js: A JavaScript library for producing dynamic, interactive data visualizations in web browsers.
Plotly.js: A graphing library that makes interactive, publication-quality graphs online.
