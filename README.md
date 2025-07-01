<p align="center">
   <a href="https://chatmeter.streamlit.app/">
        <img src="./img/Banner_PFACD.png" alt="ChatMeter Banner" width="800">
    </a>
</p>


# 💬 ChatMeter : AI Competitive Intelligence Solution 💡

<p align="center">
    <!-- Project Repository and Streamlit App Badges -->
    <a href="https://github.com/Silvestre17/ChatMeter_FinalProject.inDataScience"><img src="https://img.shields.io/badge/Project_Repo-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo"></a>
    <a href="https://chatmeter.streamlit.app/"><img src="https://img.shields.io/badge/Streamlit_App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit App"></a>
</p>

## 📝 Description

ChatMeter is an AI-powered solution designed to analyze and understand the competitive landscape of **telecommunications operators** in the **Portuguese** 🇵🇹 market. By monitoring social media, it provides businesses with crucial insights into customer sentiment, emerging topics, and competitor strategies, acting as a real-time "thermometer" for the market.

<p align="center">
    <a href="https://www.vodafone.pt/"><img src="https://img.shields.io/badge/Vodafone-FF0000?style=for-the-badge&logo=vodafone&logoColor=white" alt="Vodafone" /></a>
    <a href="https://www.meo.pt/"><img src="https://img.shields.io/badge/MEO-0052CC?style=for-the-badge&logo=meo&logoColor=white" alt="MEO" /></a>
    <a href="https://www.nos.pt/"><img src="https://img.shields.io/badge/NOS-000?style=for-the-badge&logo=nos&logoColor=white" alt="NOS" /></a>
    <a href="https://www.digi.pt/"><img src="https://img.shields.io/badge/DIGI-FFD700?style=for-the-badge&logo=digi&logoColor=white" alt="DIGI" /></a>
</p>

## 🎓 Project Context

This project was developed for the **Projeto Final Aplicado a Ciência de Dados** (*Final Applied Project in Data Science I & II*) courses. This semester-long capstone project is a central part of the 3rd and final year of the **[Licenciatura em Ciência de Dados](https://www.iscte-iul.pt/degree/code/0322/bachelor-degree-in-data-science)** (*Bachelor Degree in Data Science*) at **ISCTE-IUL**, completed in the 2023/2024 academic year. With this project, we aim to apply the knowledge and skills acquired throughout the course to a real-world problem, leveraging data science techniques to provide actionable insights and solutions for a real business challenge.

## ✨ Objective

The primary objective of ChatMeter is to develop a **"Sentiment and Topic Thermometer"** for Portuguese telecommunications operators. This tool enables stakeholders to:

*   Identify user needs, preferences, and behaviors on social media.
*   Discover new opportunities, trends, and challenges within the sector.
*   Support data-driven, informed decision-making in a competitive market.



<p align="center">
    <a href="https://facebook.com/vodafonept">
        <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
    </a>
</p>


## 🏗️ Project Workflow (CRISP-DM)

This project followed the CRISP-DM methodology for data mining. Here's a breakdown of the key activities in each phase:

1.  **Business Understanding:** 💡
    *   Defined project goals: Analyze social media data to understand the competitive landscape of telecom operators.
    *   Identified key players: **`Vodafone`** 🔴, **`MEO`** 🔵, **`NOS`** ⚫, and **`DIGI`** 🟡.

  
<p align="center">
    <a href="https://www.python.org/">
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    </a>
    <a href="https://www.beautifulsoup.org/">
        <img src="https://img.shields.io/badge/BeautifulSoup-59666C?style=for-the-badge&logo=beautifulsoup&logoColor=white" alt="Beautiful Soup" />
    </a>
    <a href="https://www.selenium.dev/">
        <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium" />
    </a>
</p>

2.  **Data Understanding:** 🔍
    *   Collected data from Facebook pages of telecom operators using web scraping.
    *   Explored the structure and format of the collected data (posts, comments, user information).
    *   Assessed data quality and identified potential issues (missing values, duplicates).

<p align="center">
    <a href="https://www.pandas.pydata.org/">
        <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
    </a>
    <a href="https://www.numpy.org/">
        <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
    </a>
    <a href="https://www.matplotlib.org/">
        <img src="https://img.shields.io/badge/Matplotlib-D3D3D3?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib" />
    </a>
    <a href="https://www.seaborn.pydata.org/">
        <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn" />
    </a>
</p>

3.  **Data Preparation:** 🛠️
    *   **Data Cleaning:** Removed duplicate entries, handled missing values, and corrected inconsistencies in the data.
    *   **Text Preprocessing:** Converted text to lowercase, removed URLs, punctuation, stopwords, and applied stemming and lemmatization.
    *   **Feature Engineering:** Created new features, such as a binary variable to indicate if the text mentions a specific operator.
 
<p align="center">
    <a href="https://www.NLTK.org/">
        <img src="https://img.shields.io/badge/NLTK-FFC700?style=for-the-badge&logo=nltk&logoColor=white" alt="NLTK" />
    </a>
    <a href="https://www.Scikit-Learn.org/">
        <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
    </a>
    <a href="https://www.wordcloud.com/">
        <img src="https://img.shields.io/badge/WordCloud-FF4500?style=for-the-badge&logo=wordcloud&logoColor=white" alt="WordCloud" />
    </a>
    <a href="https://www.spacy.io/">
        <img src="https://img.shields.io/badge/Spacy-000000?style=for-the-badge&logo=spacy&logoColor=white" alt="Spacy" />
    </a>
    <a href="https://www.textblob.readthedocs.io/">
        <img src="https://img.shields.io/badge/TextBlob-FFC700?style=for-the-badge&logo=textblob&logoColor=white" alt="TextBlob" />
    </a>
</p>


4.  **Modeling:** 🤖 
   
    *   **Sentiment Analysis:** Applied pre-trained transformer models (**[`TXRBSF`](https://huggingface.co/citizenlab/twitter-xlm-roberta-base-sentiment-finetunned)** and **[`mDeBERTa`](https://huggingface.co/MoritzLaurer/mDeBERTa-v3-base-xnli-multilingual-nli-2mil7)**) to ***classify the sentiment*** of the text **(<span style="color:green"> positive </span> / <span style="color:grey"> neutral </span> / <span style="color:red"> negative </span>**).
  
    <center><img src="./img/combine-modelos.png" /></center><br>
      
    *   **Topic Analysis:** Utilized ***Zero-Shot Classification*** with the **`mDeBERTa`** model to identify the main topics discussed in the text.

<p align="center">
    <a href="https://www.huggingface.co/">
        <img src="https://img.shields.io/badge/Hugging_Face-FFC700?style=for-the-badge&logo=huggingface&logoColor=white" alt="Hugging Face Transformers" />
    </a>
</p>  
  

5.  **Evaluation:** ✅
    *   Create a new matrix to combine the sentiment and topic analysis results.
    *   Tested for significance using the Chi-Squared Test.
  
<p align="center">
    <a href="https://www.scipy.org/">
        <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy" />
    </a>
    <a href="https://www.r-project.org/">
        <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" />
    </a>
</p>


6.  **Deployment:** 🚀

    *   Developed an interactive dashboard using **[Streamlit](https://chatmeter.streamlit.app/)** to visualize the results and insights.
  
<p align="center">
    <a href="https://www.streamlit.io/">
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
    </a>
    <a href="https://www.plotly.com/">
        <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly" />
    </a>
</p>

<br>

---

<br>

## **🗺️ Workflow**

The project's end-to-end workflow is summarized below:

<p align="center">
   <img src="./img/MasterPlanChatMeter.svg" alt="Project Workflow" width="800" height="auto" style="background-color: white; display: block;">
</p>

---

## 📊 Interactive Dashboard

Access the live interactive dashboard here: **[ChatMeter - Streamlit App](https://chatmeter.streamlit.app/)**

<p align="center">
   <a href="https://chatmeter.streamlit.app/">
      <img src="https://storage.googleapis.com/s4a-prod-share-preview/default/st_app_screenshot_image/a1424bf0-49e9-45ec-aab3-e3487d9f7e8e/Raw_App_Screenshot.png" alt="ChatMeter Streamlit" width="800" height="auto" style="background-color: white; display: block;">
   </a>
</p>

## 👥 Team Members (Group 5)

*   **André Silvestre** (Nº104532)
*   **Eliane Gabriel** (Nº103303)
*   **Maria João Lourenço** (Nº104716)
*   **Maria Margarida Pereira** (Nº105877)
*   **Umeima Adam Mahomed** (Nº99239)

## 🇵🇹 Note

This project was developed in **PT-🇵🇹**.
