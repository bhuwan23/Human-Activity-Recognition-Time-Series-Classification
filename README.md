# Human-Activity-Recognition-Time-Series-Classification

Human Activity Recognition (HAR) using smartphones dataset. Classifying the type of movement amongst six categories:
```bash
1. Walking
2. Walking Upstairs
3. Walking Downstairs
4. Sitting
5. Standing
6. Laying
```

## Details about the input data
```bash
We will be using an LSTM and CNN + LSTM model on the data to learn (as a cellphone attached on the waist) to
recognise the type of activity that the user is doing. The dataset's description goes like this:
The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in
fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings (features) per window). The sensor
acceleration signal, which has gravitational and body motion components, was separated using a Butterworth
low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency
components, therefore a filter with 0.3 Hz cutoff frequency was used.
There are three main signal types in the raw data: total acceleration, body acceleration, and body gyroscope. Each
has 3 axises of data. This means that there are a total of nine variables for each time step.
```
