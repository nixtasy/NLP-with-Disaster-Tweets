# NLP-with-Disaster-Tweets
<a name="readme-top"></a>


<!-- PROJECT SHIELDS -->
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Natural Language Processing with Disaster Tweets</h3>
  <p align="center">
    Repository for the Kaggle competition Natural Language Processing with Disaster Tweets
    <br />
    <a href="https://www.kaggle.com/competitions/nlp-getting-started/overview"><strong>Competition Overview on Kaggle »</strong></a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#model">Model</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#useful-links">Useful Links</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified. If this is your first time working on an NLP problem, we've created a quick tutorial to get you up and running.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Model -->
## Model

Model Card: [diaster_distilbert_base_uncased](https://huggingface.co/nixtasy/diaster_distilbert_base_uncased)


Training Hyperparameters:

|           model          | learning rate | epochs | batch size |
|--------------------------|---------------|--------|------------|
| distilbert-base-uncased  |      2e-5     |    3   |     16     |

Performance:

| Accuracy | validation |  test  |
|----------|------------|--------|
|          |   0.83519  | 0.8265 |



<!-- ROADMAP -->
## Roadmap

- [x] Build a baseline version of tweet classifer with BERT sentence classifier without using keyword and location attributes
- [ ] Utilize keyword and location attributes for higher accuracy

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Tianxiang Wang  - tianxiang.wang@nixtasy.com

[Project Link](https://github.com/nixtasy/NLP-with-Disaster-Tweets)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Useful Links

* [Real or Not? NLP with Disaster Tweets (Classification using Google BERT)](https://levelup.gitconnected.com/real-or-not-nlp-with-disaster-tweets-classification-using-google-bert-76d2702807b4)
* [NLP with Disaster Tweets - EDA, Cleaning and BERT](https://www.kaggle.com/code/gunesevitan/nlp-with-disaster-tweets-eda-cleaning-and-bert/notebook)
* [Tips on using keyword and location?](https://www.kaggle.com/c/nlp-getting-started/discussion/123343)
* [Topic Modeling with BERT](https://medium.com/@angelamarieteng/topic-modeling-with-bert-2e3218723373)
* [Text Classification](https://huggingface.co/docs/transformers/tasks/sequence_classification)
* [Triple Branch BERT Siamese Network for fake news classification on LIAR-PLUS dataset](https://github.com/manideep2510/siamese-BERT-fake-news-detection-LIAR)
* [https://www.kaggle.com/code/philculliton/nlp-getting-started-tutorial/notebook](https://www.kaggle.com/code/philculliton/nlp-getting-started-tutorial/notebook)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/nixtasy/music-search/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/tianxiangwang/

