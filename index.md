---
layout: single
author_profile: true
---
# Welcome To My Portfolio! 👨‍💻

*(Optional: Add a brief 2-3 sentence introduction here. Who are you? What are your key interests or career goals? e.g., "I'm Suleman, passionate about leveraging data analysis and machine learning techniques to solve complex problems, with a background in Mechanical Engineering. This portfolio showcases some of my key projects.")*

Find me on: [LinkedIn](Your-LinkedIn-URL) | [GitHub](https://github.com/king-sules)

---

## 🛠️ Skills Overview

### 📊 Language Proficiency / Usage

<style>
  .skill-bar-container { margin-bottom: 8px; font-size: 10px; }
  .skill-bar-bg { background-color: #e9ecef; border-radius: 3px; height: 12px; width: 80%; }
  .skill-bar { height: 100%; border-radius: 3px; line-height: 12px; color: white; text-align: center; }
</style>

<div class="skill-bar-container">
  <strong>Python</strong>
  <div class="skill-bar-bg">
    <div class="skill-bar" style="background-color: #007bff; width: 85%;">85%</div>
  </div>
</div>

<div class="skill-bar-container">
  <strong>JavaScript</strong>
  <div class="skill-bar-bg">
    <div class="skill-bar" style="background-color: #f0db4f; color: #323330; width: 60%;">60%</div>
  </div>
</div>

<div class="skill-bar-container">
  <strong>R</strong>
  <div class="skill-bar-bg">
    <div class="skill-bar" style="background-color: #276DC3; width: 70%;">70%</div>
  </div>
</div>

<div class="skill-bar-container">
  <strong>SQL</strong>
  <div class="skill-bar-bg">
    <div class="skill-bar" style="background-color: #CC2927; width: 65%;">65%</div>
  </div>
</div>

<div class="skill-bar-container">
  <strong>MATLAB</strong>
  <div class="skill-bar-bg">
    <div class="skill-bar" style="background-color: #0076A8; width: 75%;">75%</div>
  </div>
</div>


| Category             | Technologies & Concepts                                                     |
| :------------------- | :-------------------------------------------------------------------------- |
| **Data Science & ML**| Pandas, NumPy, Scikit-learn (GMM, RandomForest), Geopy, GeoPandas, fbprophet, Regression Analysis, Clustering |
| **Databases** | PostgreSQL (Basic)                                                          |
| **Engineering & Sim**| ANSYS, Minitab, Design of Experiments (Taguchi), Vibration Analysis         |
| **Tools & Reporting**| Git, GitHub, Jupyter Notebooks, RStudio, LaTeX                               |
| **Domains** | Machine Learning, Data Analysis, Mechanical Engineering                     |

---

<style>
.project-container {
  border: 1px solid #ccc;
  padding: 15px;
  margin-bottom: 15px;
  border-radius: 5px;
}
.project-title {
  font-size: 1.2em;
  font-weight: bold;
  margin-bottom: 5px;
}
.tech-badges img {
  margin-right: 5px;
}
</style>

## 🤖 Machine Learning

<div class="project-container">
  <div class="project-title">Project 1: Covid-19 Effects on Yellow Taxi in NYC</div>
  <img width="650" alt="NYC Borough Taxi Pickups/Dropoffs" src="https://user-images.githubusercontent.com/54907087/142779263-b1ac2b05-a04d-4aea-a0d0-13323740f9e1.png">
  <ul>
    <li>Analyzed the impact of Covid-19 restrictions on NYC yellow taxi usage by comparing data from 2018 and 2020, focusing on lockdown vs. less restricted months.</li>
    <li>Utilized ML models including **1D Gaussian Mixture Model** and **Random Forest Regression**, along with **Clustering**.</li>
    <li>Evaluated model performance using **MSE** and **MAE**.</li>
  </ul>
  <div class="tech-badges">
    ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
    ![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)
    ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
    *(Replace badges with actual URLs or just list: **Python, Scikit-learn, Pandas, Jupyter Notebook**)*
  </div>
  [View Notebook](https://github.com/king-sules/Covid_Taxi/blob/main/Covid-19%20Taxi.ipynb)
</div>

<div class="project-container">
  <div class="project-title">Project 2: Housing Prices vs. Nuclear Power Plants (Undergraduate Thesis)</div>
  <img width="300" img height="300" alt="Map of Plymouth MA area" src="https://user-images.githubusercontent.com/54907087/140659135-7cc55f6b-087c-4d19-9b3c-298bfdbbee41.png">
  <ul>
    <li>Investigated house price variations in Plymouth, MA, based on distance from a nearby nuclear power plant, specifically examining effects post-Fukushima Daiichi event.</li>
    <li>Cleaned housing data and calculated distances using **Geopy** and **GeoPandas**.</li>
    <li>Created dummy variables and distance categories to control for factors in the analysis.</li>
    <li>Performed **multiple regression analysis** using **R** to determine correlations.</li>
  </ul>
  <div class="tech-badges">
    ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
    ![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
    ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
    *(Replace badges or list: **Python, R, Geopy, GeoPandas, Pandas**)*
  </div>
  [View Code Repository](https://github.com/king-sules/Nuclear_Matrix_Data) | [Read Thesis Paper](https://github.com/king-sules/Nuclear_Matrix_Data/blob/master/Final%20Thesis.pdf)
</div>

## 📊 Data Analysis

<div class="project-container">
  <div class="project-title">Project 3: Covid-19 Breakout Analysis</div>
  <ul>
    <li>Tracked and analyzed the initial Covid-19 outbreak (Dec 2019 - May 2020) using data from Johns Hopkins University.</li>
    <li>Focused on identifying the most affected countries during the early phase.</li>
    <li>Visualized the spread and impact using **RStudio**.</li>
  </ul>
  <div class="tech-badges">
    ![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
    ![RStudio](https://img.shields.io/badge/RStudio-75AADB?style=flat&logo=RStudio&logoColor=white)
    *(Replace badges or list: **R, RStudio, Data Visualization**)*
  </div>
  [View Code Repository](https://github.com/king-sules/Covid)
</div>

<div class="project-container">
  <div class="project-title">Project 4: Taxi vs. Uber/FHV Analysis in NYC</div>
  <ul>
    <li>Analyzed the impact of the Aug 2018 TLC policy change on yellow cab vs. For-Hire Vehicle (Uber/Lyft) ride volume in NYC.</li>
    <li>Queried ride data using **PostgreSQL**.</li>
    <li>Visualized daily and monthly ride trends using **Python**.</li>
    <li>Predicted future ride trends for both taxi and FHV sectors using Facebook's **fbprophet** library.</li>
  </ul>
  <div class="tech-badges">
    ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
    ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white)
    ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
    ![Prophet](https://img.shields.io/badge/Prophet-007afe?style=flat)
    *(Replace badges or list: **Python, SQL (PostgreSQL), Pandas, fbprophet**)*
  </div>
  [View Code Repository](https://github.com/king-sules/Taxi)
</div>

## ⚙️ Mechanical Engineering

<div class="project-container">
  <div class="project-title">Project 5: Airplane Wing Vibration Analysis</div>
  <img width="451" alt="ANSYS Vibration Mode Shape" src="https://user-images.githubusercontent.com/54907087/143794858-40ba1d3a-aab5-4643-87a4-627a041bd47f.png">
  <ul>
    <li>Analyzed vibration effects on a sample airplane wing modeled with multiple degrees of freedom.</li>
    <li>Determined vibration modes using a custom **MATLAB** code.</li>
    <li>Visualized results using **ANSYS** software.</li>
    <li>Compiled findings into a comprehensive report using **LaTeX**.</li>
  </ul>
  <div class="tech-badges">
    ![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white)
    ![Ansys](https://img.shields.io/badge/ANSYS-FFB71B?style=flat)
    ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=flat&logo=latex&logoColor=white)
    *(Replace badges or list: **MATLAB, ANSYS, LaTeX**)*
  </div>
  [View MATLAB Code](https://github.com/king-sules/Vibrations/blob/main/Multi_DOF_Response.m) | [Read Full Report (LaTeX PDF)](https://github.com/king-sules/Vibrations/blob/main/Vibration_Project%20(2).pdf)
</div>

<div class="project-container">
  <div class="project-title">Project 6: Design for Manufacturability (Tire Wear Optimization)</div>
  <ul>
    <li>Applied the **Taguchi method** (Design of Experiments) to optimize tire design parameters (slip angle, tension strength, friction) for improved manufacturability and reduced wear.</li>
    <li>Analyzed parameter effects and determined optimal settings using **Minitab**.</li>
    <li>Documented the methodology and results in a formal report.</li>
  </ul>
  <div class="tech-badges">
    ![Minitab](https://img.shields.io/badge/Minitab-4C8F2F?style=flat)
    ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=flat&logo=latex&logoColor=white)
    *(Replace badges or list: **Minitab, Design of Experiments (Taguchi), LaTeX**)*
  </div>
  [Read Full Report](https://github.com/king-sules/Vibrations/blob/main/Taguchi%20Project%20Tire%20Wear.pdf)
</div>
