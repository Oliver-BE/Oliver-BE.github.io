# Oliver's Portfolio

Welcome to my portfolio! Click the name of a project to see its corresponding GitHub page, website, or  `pdf` (when applicable).

## Technical Projects

<img src="images/ring-of-fire.png?raw=true" width="20%" align="right"/>

#### [Ring of Fire: Evolving a Wildfire Simulator using Genetic Programming](https://github.com/Oliver-BE/ring-of-fire)

A parallelized **Genetic Program** for evolving rules to describe a cellular automaton based wildfire simulation with an error function based on data from Canadian wildfires. Both the genetic program and the wildfire simulator were written in **Clojure** by [@icaruso21](https://github.com/icaruso21), [@MGlusker](https://github.com/MGlusker), and myself.

<img src="images/fire-scar-comparison.png"/>

---

#### [Classifying Fake News Using Natural Language Processing and Machine Learning](/pdf/fake-news-nlp.pdf)

A formal report written in **R** that uses **Natural Language Processing** and **Machine Learning** to classify news claims as either true or false. 

This project used a dataset of **1,911** unique [PolitiFact](https://www.politifact.com/) claims and their associated truth ratings. Features were extracted from each claim using a [bag-of-n-grams model](https://machinelearning.wtf/terms/bag-of-n-grams/) with [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) as the scoring metric (the vocabulary size was first reduced using using lemmatization and stop word removal among other text cleaning procedures). 

Seven machine learning classification models (including **a random forest**, **a multilayer perceptron**, and **a recurrent neural network**) were fit and a maximum classification accuracy of **71%** was achieved.

---

#### [Intellage: An Intelligent Photo Collage Creator](https://github.com/Oliver-BE/intellage)

Written entirely from scratch in **Java** by [@icaruso21](https://github.com/icaruso21) and myself, `Intellage` recreates a desired photo from a user-specified collection of `.jpg` images. `Intellage` was used as an exemplar of a final project in subsequent semesters of the introductory computer science class for which it was written. 

The following outputs from `Intellage` each utilized an input folder containing **26,000** stock images:

<img src="images/intellage-sample.png?raw=true"/>

---

#### Various Pacman Artificial Intelligence Projects

Using **Python**, [@MGlusker](https://github.com/MGlusker) and I implemented various **Artificial Intelligence** algorithms in a Pacman setting including:
- Exact inference and particle filtering to read noisy data using Bayes' Nets
- Reinforcement learning algorithms such as Temporal Difference Q-learning
- DFS, BFS, UCS, and A* to find food pellets

We also created a team of agents to play a capture the flag version of Python. We used **particle filtering** to estimate the position of enemy Pacman agents, a **minimax algorithm** with **alpha-beta pruning** to select our agents' next move, and different evaluation functions for offensive/defensive moves. 

---

## Data Visualizations 

#### [Interactive Directed Graph Creator](https://oliver-be.ml/interactive-directed-graph-creator/)

A fully interactive web app for creating directed graphs using **D3.js**'s force layout with the ability to save a snapshot of the graph’s layout as a JSON file for future use. This was built as a prototype for a [state chart](https://www.tutorialspoint.com/uml/uml_statechart_diagram.html) as part of the work I did as a research assistant for the [Tulane Visualization and Graphics Group](https://tulanevisgraphics.bitbucket.io/) during the summer of 2019.

<img src="images/directed-graph.png?raw=true"/>

---

#### [Visualizing Sorting Algorithms using Empirical](https://oliver-be.ml/sorting-algorithms-d3/)

A web app written entirely in **C++** that utilizes the Empirical D3-wrapper that I helped to write as a Summer 2020 [WAVES](https://mmore500.com/waves/index.html) participant. This project is meant to serve as a demo for how the new D3-wrapper can be used with [Empirical](https://github.com/devosoft/Empirical) (a library for building web interfaces with C++ and [Emscripten](https://emscripten.org/)) to create powerful web apps.

Along with [@elizabethcarney](https://github.com/elizabethcarney), [@amlalejini](https://github.com/amlalejini), and [@emilydolson](https://github.com/emilydolson) I spent the summer creating a C++ wrapper for **[D3.js](https://D3js.org)**, a JavaScript library that allows for custom-made, interactive visualizations. We began the process of overhauling Empirical's web visualization support for use in the next version of [Avida-ED](https://avida-ed.msu.edu/) (an award-winning piece of digital evolution education software).

For more information on what I did, see **[this blog post I wrote.](https://mmore500.com/waves/blog/d3-sorting.html)**

<img src="images/d3-sorting.png"/>

---

#### [COVID-19 D3 Visualization](https://oliver-be.ml/covid-d3/) 

An interactive visualization of COVID-19 data obtained from the [New York Times](https://github.com/nytimes/covid-19-data) built from scratch using **D3.js**. Note that this is still a work in progress and is very rough and buggy!

---
 
## Smaller Assorted Projects

#### [Public Transit in US Cities](https://github.com/Oliver-BE/transit-gdp-project)

An exploration of predicting GDP per capita from transit statistics using an aggregation of 30+ datasets and regression trees in **R**.
Built a **Shiny app** with **Leaflet** to display transportation stats for 50 largest US cities, created an **R Package** to contain  data.

<img src="images/transit-shiny-app.png"/>

---

#### [Sentiment Analysis Shiny App](https://r.amherst.edu/apps/obaldwinedwards21/AmherstHistory/)

An **R Shiny app** created to visualize sentiment analysis and topic modeling of the book *"History of Amherst College during the First Half Century"*.


<img src="images/amherst-shiny.png"/>

---

#### [COVID Race Data — R Package](https://github.com/Oliver-BE/CovidRaceData)

An **R Package** containing two (wrangled) datasets on the COVID-19 pandemic in the US by race/ethnicity (as of 10/07/2020). More specifically, it has data for the number of COVID-19 cases and deaths by race/ethnicity for each state.

The raw data used to wrangle the datasets in this R package was obtained from [The COVID
Tracking
Project](https://covidtracking.com/race/about#download-the-data).
 
<img src="images/covid-race-1.png?raw=true"/> 

> *An example visualization I created using the data in this package.*

---

#### [Connect Four](https://oliver-be.ml/connect-four/)

A **JS/CSS/HTML** implementation of Connect Four written from scratch as a way to help teach myself web development.

<img src="images/connect-four.png"/>

---
 
## Technical Skills 

Proficient in:
* **Python**, **Java**, **R**, **Git**

Meaningful experience with:
* **JavaScript**, **C++**, **Clojure**, **HTML**, **CSS**, **R Shiny Apps**


Exposure to:
* **SQL**, **C**