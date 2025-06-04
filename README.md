
---

# Fundamental of Big-Data Analysis Project

## Course Name:

Fundamental of Big-Data Analysis

## SUBMITTED BY:
- **Umaima Hashmi (22I-1984)**
- **Nooran Ishtiaq (22I-2010)**
- **M. Manhab Zafar (22I-1957)**

## Project Description:

This project aims to develop a streamlined alternative to Spotify, focusing on implementing a music recommendation system, playback, and streaming capabilities, alongside real-time suggestions derived from user activity. The project is divided into three phases: Extract, Transform, Load (ETL) Pipeline, Music Recommendation Model, and Deployment.

### Phase #1: Extract, Transform, Load (ETL) Pipeline:

In the first phase, we created an ETL pipeline using the Free Music Archive (FMA) dataset, comprising 106,574 tracks spanning 161 unevenly distributed genres. We extracted important features from audio files using techniques like Mel-Frequency Cepstral Coefficients (MFCC), spectral centroid, and zero-crossing rate. Additionally, normalization, standardization, and dimensionality reduction techniques were explored to enhance recommendation model accuracy. The transformed data was stored in MongoDB for scalability and accessibility.

### Music Recommendation Model:

The music recommendation model analyzes the listening habits or behavior of the user. Upon selecting a song, the model extracts its features and compares them with a vast dataset using NearestNeighbors to suggest the top 5 songs that match the user's audio.

### Webpage Through Flask:

The final phase involved deploying our Music Recommendation Model named "BeatBox" on a web page using Flask. The webpage offers a user-friendly interface, responsive design, vibrant colors, and sections such as header, footer, contact us page, and music section. Upon selecting a song, the model applies the MFCC mechanism to suggest further audios, and the process continues. Easy navigation is facilitated with buttons like "MUSIC" and "LISTEN MUSIC". Additionally, a guide on how the model works is provided within the website, along with a contact us page and footer.

---
