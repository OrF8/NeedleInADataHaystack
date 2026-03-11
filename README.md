# 🎬 Reel Patterns

**Reel Patterns** is a data science project that uncovers hidden structures and surprising trends in cinema.  
Instead of asking _“What makes a movie successful?”_, we dive into unconventional questions like:  
- Which actors form tight-knit cliques?  
- When should a franchise stop producing sequels before brand fatigue sets in?  
- Do blockbuster movies also create hit soundtracks?

This project was created by [**Or Forshmit**](https://github.com/OrF8), [**Noam Kimhi**](https://github.com/noam-kimhi) and [**Adir Tuval**](https://github.com/AdirTuval)
as part of the course [**67978: A Needle in a Data Haystack – Introduction to Data Science**](https://shnaton.huji.ac.il/index.php/NewSyl/67978/2/2025/)
at the Hebrew University of Jerusalem ([**HUJI**](https://en.huji.ac.il/)).

Full paper available [here](https://github.com/OrF8/Reel-Patterns/blob/main/Reel%20Patterns%20-%20by%20Noam%20Kimhi%2C%20Or%20Forshmit%20and%20Adir%20Tuval.pdf).

> 🎓 Final Grade: **100**

<p align="center">
	<img src="https://img.shields.io/github/license/OrF8/Reel-Patterns?style=default&logo=opensourceinitiative" alt="license">
	<img src="https://img.shields.io/github/languages/top/OrF8/Reel-Patterns?style=default&logo=python&color=A40000" alt="repo-top-language">
</p>
<p align="center">
  <!-- Tech stack / deps -->
  <img src="https://img.shields.io/badge/Streamlit-1.49.1-FF4B4B?logo=streamlit" alt="streamlit">
  <img src="https://img.shields.io/badge/Pandas-2.3.2-150458?logo=pandas" alt="pandas">
  <img src="https://img.shields.io/badge/NumPy-2.0.2-013243?logo=numpy" alt="numpy">
  <img src="https://img.shields.io/badge/Matplotlib-3.9.4-11557C" alt="matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-0.13.2-4E9CAB" alt="seaborn">
  <img src="https://img.shields.io/badge/Plotly-6.3.0-3F4F75?logo=plotly" alt="plotly">
  <img src="https://img.shields.io/badge/NetworkX-3.2.1-0A66C2" alt="networkx">
  <br>
  <img src="https://img.shields.io/badge/SciPy-1.13.1-8CAAE6?logo=scipy" alt="scipy">
  <img src="https://img.shields.io/badge/Spotipy-2.25.1-1DB954?logo=spotify" alt="spotipy">
  <img src="https://img.shields.io/badge/Python--Dotenv-0.9.9-306998?logo=dotenv" alt="dotenv">
  <img src="https://img.shields.io/badge/tqdm-4.67.1-FFD43B?logo=tqdm" alt="tqdm">
  <img src="https://img.shields.io/badge/RapidFuzz-3.13.0-6E40C9?logo=rapidfuzz" alt="rapidfuzz">
  <img src="https://img.shields.io/badge/Requests-2.32.5-FF6C37?logo=requests" alt="requests">
</p>
<br>

## 🔗 Table of Contents

- [📍 Overview](#-overview)
- [👾 Features](#-features)
- [📁 Project Structure](#-project-structure)
  - [📂 Project Index](#-project-index)
- [🚀 Getting Started](#-getting-started)
  - [☑️ Prerequisites](#%EF%B8%8F-prerequisites)
  - [⚙️ Installation](#%EF%B8%8F-installation)
  - [🤖 Usage](#-usage)
- [🔰 Contributing](#-contributing)
- [🎗 License](#-license)
- [🙌 Acknowledgments](#-acknowledgments)

---

## 📍 Overview

Reel Patterns explores cinema data through three unconventional lenses:

Actor communities – uncovering hidden cliques and bridge actors using collaboration networks.

Franchise dynamics – analyzing how sequel performance evolves and identifying when franchises fall into brand fatigue.

Soundtrack correlations – testing whether popular soundtracks align with box-office success and audience ratings.

By combining large-scale datasets with graph analysis, statistical modeling, and interactive dashboards, we reveal structures and trends that go beyond traditional movie success metrics.

---

## 👾 Features

- Actor community detection using collaboration graphs  
- Franchise sequel performance analysis  
- Soundtrack vs. movie success correlations  
- Interactive visualizations with **Streamlit** in [the web app](https://wecliqued.streamlit.app/)
  > [![Watch Demo](https://img.shields.io/badge/Watch%20Demo-YouTube-red)](https://youtu.be/7dYvg-mgV4M)
<p align="center">
  <a href="https://youtu.be/7dYvg-mgV4M">
    <img src="https://img.youtube.com/vi/7dYvg-mgV4M/maxres2.jpg"
         alt="Reel Patterns – Demo" width="800">
  </a>
</p>


---

## 📁 Project Structure

```sh
└── Reel-Patterns/
    ├── Curtain call, please
    │   ├── constants.py
    │   ├── curtain_call_visualizations.py
    │   ├── preprocessing.py
    │   └── query_wikidata_script.py
    ├── README
    ├── Reel Hits Meet Real Hits
    │   ├── organize_data.py
    │   └── reel_hits_viz.py
    ├── What Can I Say, We Cliqued
    │   ├── constants.py
    │   ├── organize_data.py
    │   └── streamlit_app.py
    ├── data
    │   ├── collabs.csv
    │   ├── LICENSE.md
    │   └── entire_data_link
    ├── figures
    │   ├── corr_pop_rating.png
    │   ├── movies_per_sequel_index.png
    │   ├── prob_of_success_audience_rating.png
    │   ├── prob_of_success_critic_rating.png
    │   ├── prob_of_success_roi.png
    │   ├── reel_hits_pearson_heatmap.png
    │   └── reel_hits_spearman_heatmap.png
    ├── LICENSE
    └── requirements.txt
```

### 📂 Project Index
<details open>
	<summary><b>REEL-PATTERNS</b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>Root</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/requirements.txt'>requirements.txt</a></b></td>
				<td><code>❯ Python dependencies required to run the project</code></td>
			</tr>
      <tr>
        <td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/main/LICENSE'>LICENSE</a></b></td>
				<td><code>❯ License for the code and non-data files (MIT)</code></td>
      </tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- Reel Hits Meet Real Hits Submodule -->
		<summary><b>Reel Hits Meet Real Hits</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/Reel Hits Meet Real Hits/organize_data.py'>organize_data.py</a></b></td>
				<td><code>❯ Collects and prepares soundtrack and movie data for analysis</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/Reel Hits Meet Real Hits/reel_hits_viz.py'>reel_hits_viz.py</a></b></td>
				<td><code>❯ Creates visualizations of correlations between soundtracks and movies</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- Curtain call, please Submodule -->
		<summary><b>Curtain call, please</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/Curtain call, please/query_wikidata_script.py'>query_wikidata_script.py</a></b></td>
				<td><code>❯ Script to fetch additional metadata from Wikidata</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/Curtain call, please/constants.py'>constants.py</a></b></td>
				<td><code>❯ Constants and parameters for franchise analysis</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/Curtain call, please/curtain_call_visualizations.py'>curtain_call_visualizations.py</a></b></td>
				<td><code>❯ Visualizations of sequel success and franchise dynamics</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/Curtain call, please/preprocessing.py'>preprocessing.py</a></b></td>
				<td><code>❯ Data cleaning and preparation for sequel performance analysis</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- What Can I Say, We Cliqued Submodule -->
		<summary><b>What Can I Say, We Cliqued</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/What Can I Say, We Cliqued/streamlit_app.py'>streamlit_app.py</a></b></td>
				<td><code>❯ Interactive Streamlit dashboard for actor collaboration networks</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/What Can I Say, We Cliqued/constants.py'>constants.py</a></b></td>
				<td><code>❯ Constants and parameters for actor network analysis</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/OrF8/Reel-Patterns/blob/master/What Can I Say, We Cliqued/organize_data.py'>organize_data.py</a></b></td>
				<td><code>❯ Prepares collaboration data for graph-based analysis</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---

## 🚀 Getting Started

### ☑️ Prerequisites

Before getting started with Reel-Patterns, ensure your runtime environment meets the following requirements:

- Python 3.9
- pip

Also, make sure to download the available data from [Google Drive](https://drive.google.com/drive/folders/1NesVB8y9xm-_2s-kShLhZW3PF3YItkGM?usp=sharing).

### ⚙️ Installation

Install Reel-Patterns the following way:

1. Clone the Reel-Patterns repository:
```sh
git clone https://github.com/OrF8/Reel-Patterns
```

2. Navigate to the project directory:
```sh
cd Reel-Patterns
```

3. Install the project dependencies using [<img align="center" src="https://img.shields.io/badge/Pip-3776AB.svg?style={badge_style}&logo=pypi&logoColor=white" />](https://pypi.org/project/pip/):
```sh
pip install -r requirements.txt
```

### 🤖 Usage
Most modules in this repository are designed to **collect, preprocess, and analyze data**, and then generate plots or visualizations. 
They are not meant to be long-running services, but rather **scripts that prepare results and figures**.  
The main exception is the Streamlit app, which allows interactive exploration of results.

You _can_ run one of the modules directly, for example:
```sh
python "Reel Hits Meet Real Hits/reel_hits_viz.py"
```

This will collect the relevant data, process it, and produce the associated plots.

To explore the results of the `What can I say? We cliqued` section interactively, you can use the [web app](https://wecliqued.streamlit.app/),
or you can run the app locally:
```sh
python -m streamlit run "What Can I Say, We Cliqued\streamlit_app.py"
```

---

## 🔰 Contributing

- **💬 [Join the Discussions](https://github.com/OrF8/Reel-Patterns/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/OrF8/Reel-Patterns/issues)**: Submit bugs found for the `Reel Patterns` project.

### ⚠️ Contribution Policy
This is an **academic course project**, not a community-driven open-source project.  
We are **not seeking pull requests or code contributions**.  
However, we welcome:
- Feedback on our analysis and results  
- Suggestions for further exploration  
- Questions or discussions about the methods used

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/OrF8/Reel-Patterns/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=OrF8/Reel-Patterns">
   </a>
</p>
</details>

---

## 🎗 License

This project’s **code and non-dataset material** is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.  
Datasets are provided under their original licenses (see [data/LICENSE.md](data/LICENSE.md)).

### 📊 Data Licensing

This project combines multiple external datasets. To stay compliant with licensing and API terms, we distinguish between data we can share directly and data you must fetch yourself.

#### ✅ Included in this repository
- [**Kaggle TMDB dataset**](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies)
  → Licensed under [ODC Attribution License (ODC-By v1.0)](https://opendatacommons.org/licenses/by/1-0/index.html).
- [**Kaggle RT dataset**](https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset/data?select=rotten_tomatoes_movies.csv)
  → Licensed under [CC0 1.0 (Public Domain)](https://creativecommons.org/publicdomain/zero/1.0/).
- [**IMDb datasets**](https://datasets.imdbws.com/) → Provided under [IMDb non-commercial terms]([https://www.imdb.com/interfaces/](https://help.imdb.com/article/imdb/general-information/can-i-use-imdb-data-in-my-software/G5JTRESSHJBBHTGX#)).  
  Shared here strictly for **academic and research purposes only**.  
- **Wikidata** → Licensed under [CC0 1.0 (Public Domain)](https://creativecommons.org/publicdomain/zero/1.0/).  

#### ⚠️ Not included (must be fetched by users)
- **Spotify API data** → Due to [Spotify Developer Terms of Service](https://developer.spotify.com/terms/), we cannot redistribute Spotify-derived datasets (e.g., album or track popularity).  
  Instead, we provide code using [Spotipy](https://spotipy.readthedocs.io/) so you can re-fetch the data yourself with your own API key.
> [!NOTE]
> Our script uses heuristics to guess the correct soundtrack album.
> Because of that, it made some mistakes (about 5%), and we had to manually fix them.

**Note:** All datasets were processed (cleaned, merged, filtered) for analysis in this project.  
Processing does not change their original licensing terms.
More information can be found in the [data license](data/LICENSE.md) file.

---

## 🙌 Acknowledgments

- Information courtesy of [IMDb](https://www.imdb.com).
Used with permission.
- [Rotten Tomatoes dataset on Kaggle](https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset).  
- [TMDB dataset on Kaggle](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies).  
- [Wikidata](https://www.wikidata.org/wiki/Wikidata:Licensing) (CC0 public domain data).  
- [Spotify API](https://developer.spotify.com/) for soundtrack data (queried via [Spotipy](https://spotipy.readthedocs.io/)).  
- [Streamlit](https://streamlit.io/) for powering the interactive web app.  

---














