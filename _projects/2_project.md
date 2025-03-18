---
layout: page
title: Spotify 2023 Streaming Analysis
description: Exploring the most streamed artists, songs, and industry trends of 2023 through interactive data visualization.
img: assets/img/Spotify_analysis.jpeg
importance: 2
category: work
---

    ---
    Source Code available in the repository
    Github handle: saileshdwivedy30
    Project: Spotify 2023 Streaming Analysis
    Deployed App: https://my-example-project-719255-kngkr5dp-ndjz2ws6la-ue.a.run.app/
    Demo Video: https://drive.google.com/file/d/13TnESRwxw4Eew5h-zCw-aM1MxVO8Ncld/view?usp=sharing
    Dataset Link: https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023/data
    ---

Deployed App: <a href="https://my-example-project-719255-kngkr5dp-ndjz2ws6la-ue.a.run.app/" target="_blank">Click here</a>\
Demo Video: <a href="https://drive.google.com/file/d/13TnESRwxw4Eew5h-zCw-aM1MxVO8Ncld/view?usp=sharing" target="_blank">Watch Demo</a>\
Dataset Link: <a href="https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023/data" target="_blank">View Dataset</a>

## **Overview**
The **Spotify 2023 Streaming Analysis App** is an **interactive data visualization platform** that explores **top streamed songs, artists, and industry trends**. It enables **music analysts, data enthusiasts, and industry professionals** to analyze how **song characteristics, playlist placements, and seasonal trends** influence streaming performance.

For a detailed walkthrough, please check out the **demo video** linked above.

---

## **Tech Stack**
- **Python** – Backend scripting and data processing.
- **Pandas & NumPy** – Data analysis and manipulation.
- **Plotly & Seaborn** – Interactive visualizations and charts.
- **Preswald** – UI framework for interactive dashboards.
- **Flask** – Backend for web app deployment.
- **Git & GitHub** – Version control and project collaboration.

---

## **Dataset Overview**
The project utilizes the **Most Streamed Spotify Songs 2023** dataset from **Kaggle** (linked above), containing:
- **Top streamed songs & artists**
- **Streaming counts and ranking trends**
- **Song attributes** (BPM, energy, danceability, valence, etc.)
- **Playlist placements across streaming platforms**

---
## **Features & Insights**
This app provides **interactive visualizations and insights** into the world of **Spotify streaming trends**:

### **1️. Top Artists by Total Streams**
- **Bar chart** showcasing **most streamed artists globally**.
- Analyze **trends in artist dominance** over the year.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot1.png" title="p1_plot1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### **2️. Most Streamed Songs**
- **Interactive ranking chart** of viral hits and long-lasting chart-toppers.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot2.png" title="p1_plot2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### **3️. Impact of BPM on Song Popularity**
- **Scatter plot** analyzing the correlation between **tempo (BPM) and total streams**.
- Do **high-energy songs** perform better, or do **slow-tempo ballads** dominate?

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot3.png" title="p1_plot3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### **4️. Trends in Song Releases Over the Years**
- **Line chart** tracking **evolution of song releases** over time.
- Assess **the impact of streaming platforms** on **independent artists**.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot4.png" title="p1_plot4" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### **5️. How Do Song Characteristics Affect Popularity?**
- **Energy vs. Streams, Danceability vs. Streams (Scatter Plots)**
- **Happiness (Valence) Analysis using Box Plot**
- Identifying **traits that define viral hits**.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot5.png" title="p1_plot5" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot6.png" title="p1_plot6" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### **6️. Influence of Playlist Placements on Streams**
- **Comparison of playlist placements** across **Spotify, Apple Music, and Deezer**.
- **Scatter plot:** Does **playlist exposure** significantly boost **streaming numbers**?

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot7.png" title="p1_plot7" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### **7️. Seasonal Trends in Song Releases & Streaming**
- **Monthly trends in song releases and streaming activity**.
- Identify **peak months** for **new music releases** and **streaming surges**.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot10.png" title="p1_plot10" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### **8️. Key & Mode Distribution of Popular Songs**
- **Bar chart** for **most common musical keys**.
- **Pie chart** analyzing **major vs. minor modes** in **top songs**.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot8.png" title="p1_plot8" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p1_plot9.png" title="p1_plot9" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

## **Key Takeaways**
- **Data-driven insights** into **Spotify’s 2023 streaming trends**.
- **Interactive visualizations** to explore **artist & song performance**.
- **Seasonal and playlist-driven impact** on **streaming numbers**.
- **Deployable web app** with **easy-to-use filtering & analysis**.

---
This **interactive dashboard** is designed for **music analysts, content creators, and industry professionals** to explore **Spotify’s 2023 streaming trends dynamically**.