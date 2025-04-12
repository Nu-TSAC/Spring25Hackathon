# Spring25Hackathon Guidelines

## Overview

Choose between two predictive modeling tracks:

* Basketball Track: Predict NBA players' Field Goal Percentage (FG%) for the 2025 season.

* Baseball Track: Predict baseball exit velocity based on pre-contact metrics.

## Basketball Track

### Objective

Predict the FG% for players based on provided shot-level data.

### Data

`basketball_track/train.csv.zip`

Player and team names are anonymized.

### Submission

`basketball_track/submission.csv`

Format: CSV

Structure: Player IDs as index, predicted FG% as values.

### Evaluation

Metric: Mean Squared Error (MSE)

## Baseball Track

### Objective

Predict exit velocity using pre-contact metrics such as bat speed, pitch speed, etc.

### Data

Statcast Dataset

`baseball_track/train.csv`

Exit velocity and hit location data will be removed.

### Submission

`baseball_track/test.csv`

`baseball_track/submission.csv`

Format: CSV

Structure: Play IDs as index, predicted Exit Velocity as values.

### Evaluation

Metric: Mean Squared Error (MSE)

## General Instructions

Teams or individuals can participate.

Submissions must be clear, well-formatted, and adhere strictly to submission guidelines.

Ensure reproducibility of your approach (clearly documented code or notebooks are encouraged).

Each submission should have an acompanying powerpoint presenation that will be presented with.

Submission CSV + Powerpoint can be emailed to neusportsanalytics@gmail.com as either seperate files or a link to a github repo.

### Submission Deadline

4:00 on April 12th 2025

### Judging Criteria

Accuracy (MSE)

Methodological robustness

Creativity and innovation

Code clarity and reproducibility
