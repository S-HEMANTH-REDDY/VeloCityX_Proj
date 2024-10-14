# VeloCityX Fan Engagement Data Analysis

## Overview

This repository contains an analysis of user engagement data from the VeloCityX app, designed to enhance the spectator experience during major racing events. The analysis focuses on understanding fan behavior, optimizing fan challenges, merchandise sales, and sponsorship integration.

## Dataset

The dataset used for this analysis is named `2025-VeloCityX-Expanded-Fan-Engagement-Data.csv` and includes the following columns:

- **User ID**: Unique identifier for each user.
- **Fan Challenges Completed**: Number of challenges completed by the user.
- **Predictive Accuracy (%)**: Accuracy percentage of predictions made by the user.
- **Virtual Merchandise Purchases**: Number of virtual merchandise items purchased.
- **Sponsorship Interactions (Ad Clicks)**: Number of ad clicks by the user.
- **Time on Live 360 (mins)**: Total time spent on Live 360 coverage (in minutes).
- **Real-Time Chat Activity (Messages Sent)**: Total number of messages sent in real-time chat.

### Sample Data

| User ID | Fan Challenges Completed | Predictive Accuracy (%) | Virtual Merchandise Purchases | Sponsorship Interactions (Ad Clicks) | Time on Live 360 (mins) | Real-Time Chat Activity (Messages Sent) |
|---------|--------------------------|-------------------------|------------------------------|--------------------------------------|--------------------------|-----------------------------------------|
| U001    | 5                        | 80                      | 3                            | 10                                   | 120                      | 20                                      |
| U002    | 8                        | 60                      | 1                            | 8                                    | 100                      | 35                                      |
| ...     | ...                      | ...                     | ...                          | ...                                  | ...                      | ...                                     |

## Installation

To run the analysis, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
