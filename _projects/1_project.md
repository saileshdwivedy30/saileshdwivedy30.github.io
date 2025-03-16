---

layout: page
title: Spotify 2023 Streaming Analysis
description: Exploring the most streamed artists, songs, and industry trends of 2023 through interactive data visualization.
img: assets/img/spotify\_analysis.png
importance: 1
category: work
--------------

```
---
Source Code available in the repository
Github handle: saileshdwivedy30
Project: Spotify 2023 Streaming Analysis
Deployed App: https://my-example-project-719255-kngkr5dp-ndjz2ws6la-ue.a.run.app/
Demo Video: https://drive.google.com/file/d/13TnESRwxw4Eew5h-zCw-aM1MxVO8Ncld/view?usp=sharing
Dataset Link: https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023/data
---
```

**Overview**\
The **Spotify 2023 Streaming Analysis App** provides an **interactive** way to explore **top streamed songs, artists, and streaming trends**. This web-based tool allows users to analyze how song characteristics, playlist placements, and seasonal trends impact streaming performance.

This project is built for **music analysts, data enthusiasts, and industry professionals** who want to gain insights from Spotify's 2023 streaming data.

For a detailed walkthrough, please check out the demo video above.

---

**Dataset Overview**\
This project utilizes the **Most Streamed Spotify Songs 2023** dataset from **Kaggle** linked above.

Key Dataset Features:

- **Top streamed songs & artists**
- **Streaming counts and ranking insights**
- **Song attributes (BPM, energy, danceability, valence, etc.)**
- **Playlist placements across streaming platforms**

---

**Features & Insights**\
The app provides multiple **visualizations and insights** to understand streaming trends:

1. **Top Artists by Total Streams**

   - Bar chart showing the most streamed artists globally.
   - Analyze trends in artist dominance over the year.

   <div class="row">
       <div class="col-sm mt-3 mt-md-0">
           {% include figure.liquid path="assets/img/p1_plot1.png" title="Plot_1" class="img-fluid rounded z-depth-1" %}
       </div>
   </div>

2. **Most Streamed Songs**

   - Interactive chart of viral songs and long-lasting chart-toppers.
   
   <div class="row">
       <div class="col-sm mt-3 mt-md-0">
           {% include figure.liquid path="assets/img/p1_plot2.png" title="plot_2" class="img-fluid rounded z-depth-1" %}
       </div>
   </div>

3. **Impact of BPM on Song Popularity**

   - Scatter plot analyzing the correlation between **tempo (BPM) and streams**.
   - Insights into whether high-energy or slow-tempo songs perform better.

   <div class="row">
       <div class="col-sm mt-3 mt-md-0">
           {% include figure.liquid path="assets/img/p1_plot3.png" title="plot_3" class="img-fluid rounded z-depth-1" %}
       </div>
   </div>
4. **Trends in Song Releases Over the Years**

   - Line chart showing how song releases have evolved over time.
   - Impact of streaming platforms on independent artists.

   <div class="row">
       <div class="col-sm mt-3 mt-md-0">
           {% include figure.liquid path="assets/img/p1_plot4.png" title="plot_4" class="img-fluid rounded z-depth-1" %}
       </div>
   </div>

5. **How Do Song Characteristics Affect Popularity?**

   - **Energy vs. Streams, Danceability vs. Streams (Scatter Plots)**
   - **Happiness (Valence) Analysis using Box Plot**
   - Identifying traits that define viral hits.

   <div class="row">
       <div class="col-sm mt-3 mt-md-0">
           {% include figure.liquid path="assets/img/p1_plot5.png" title="plot_5" class="img-fluid rounded z-depth-1" %}
       </div>
   </div>

   
   <div class="row">
       <div class="col-sm mt-3 mt-md-0">
           {% include figure.liquid path="assets/img/p1_plot6.png" title="plot_6" class="img-fluid rounded z-depth-1" %}
       </div>
   </div>




6. **Influence of Playlist Placements on Streams**

   - **Comparison of playlist placements on Spotify, Apple Music, Deezer.**
   - **Scatter plot:** Does playlist exposure boost streaming numbers?

   <div class="row">
       <div class="col-sm mt-3 mt-md-0">
           {% include figure.liquid path="assets/img/p1_plot7.png" title="plot_7" class="img-fluid rounded z-depth-1" %}
       </div>
   </div>



7. **Seasonal Trends in Song Releases & Streaming**

   - Monthly trends in **song releases** and **streaming activity**.
   - Identifying peak months for new releases.

8. **Key & Mode Distribution of Popular Songs**

   - **Bar chart for most common musical keys.**
   - **Pie chart analyzing major vs. minor modes in top songs.**

   <div class="row">
       <div class="col-sm mt-3 mt-md-0">
           {% include figure.liquid path="assets/img/p1_plot8.png" title="plot_8" class="img-fluid rounded z-depth-1" %}
       </div>
   </div>

   <div class="row">
       <div class="col-sm mt-3 mt-md-0">
           {% include figure.liquid path="assets/img/p1_plot9.png" title="plot_9" class="img-fluid rounded z-depth-1" %}
       </div>
   </div>


---

**Key Takeaways**

- **Data-driven insights into Spotify’s 2023 streaming trends.**
- **Interactive visualizations to explore artist & song performance.**
- **Seasonal and playlist-driven impact on streaming numbers.**
- **Deployable app with easy-to-use filtering & analysis.**

