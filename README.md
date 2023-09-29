<a name="readme-top"></a>
<div align="center">

[![alt text](https://github.com/Mysftz/Mysftz/blob/main/assets/READMEHeader.jpeg?raw=true)](https://github.com/Mysftz)
# Brain Computer Interface Classification Thesis
[![GitHub][GitHub-shield]](https://github.com/Mysftz/brain-computer-interface-classification-thesis)
[![Contributors][contributors-shield]](https://github.com/Mysftz/brain-computer-interface-classification-thesis/graphs/contributors)
[![Forks][forks-shield]](https://github.com/Mysftz/brain-computer-interface-classification-thesis/network/members)
[![Stargazers][stars-shield]](https://github.com/Mysftz/brain-computer-interface-classification-thesis/stargazers)
[![Issues][issues-shield]](https://github.com/Mysftz/brain-computer-interface-classification-thesis/issues)
[![License][license-shield]](https://github.com/Mysftz/brain-computer-interface-classification-thesis/blob/main/LICENSE.txt)
</div>

<p align="center">
  <a href="#about-the-project">About The Project</a> •
  <a href="#built-with">Built With</a> •
  <a href="https://github.com/Mysftz/brain-computer-interface-classification-thesis/archive/refs/heads/main.zip">Download</a> • 
  <a href="#usage">Usage</a> •
  <a href="#license">License</a> •
  <a href="#other-projects">Other Projects</a> •
  <a href="#contact">Contact</a>
</p>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#introduction">Infomation</a></li>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#other-infomation">Other Infomation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#other-projects">Other Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
### Introduction

This Project utilises Matlab to run variation of a convolutional neural network (CNN) which is located in the CNN folder, these file learns from dataset located in the dataset folder which contains 15 subjects and 7 session each with 9 files of data. The .m files in the CNN folder run session 1-7, 1-3 or 4-7 to which requests the appropriate data from the dataset file using a list that is located in the SBJ-S folder which contains subject, session numbers and cell range to which the results will be printed into a spreadsheet. These spreadsheet will write over each other so the results are copied into another spreadsheet in the results folder called All_Results_Data which contains all the project and experiment results, these are then organised further into spreadsheets for results for sessions 1-3, 4-7 and 1-7. The BCI_CNN_Function.m file in the CNN folder is the convolutional neural network that can be manipulated to run different variations of the CNN to improve the session accuracy.

This paper aims to improve a current paradigm, the accuracy within a P300 based brain computer interfaces (BCI), which uses a P300 dataset of 15 high-functioning patients who have Autism Spectrum Disorder (ASD), each patient underwent 7 sessions which extracted electroencephalogram (EEG), P300 based data. This research seeks to improve a current convolutional neural network (CNN) through pre-processing, training and testing the data by running multiple variations of the CNN to best fit the dataset. Two accuracy’s are given to improve: 67%, an average of all subjects of sessions 4 to 7 and 76%, an average of the highest accuracy session of each subject. It was found that one accuracy was improved, the accuracy from 76% to 84% by restructuring the dropout layers, decreasing its probabilities, the initial learning rate and the output size of the fully connected layer. The highest average accuracy achieved for session 4 to 7 was 64%, 3% under the objective accuracy due to computer and runtime complications of the amount of variations that could be explored, hindering a repetitive runs to forms pattern. It was also concluded that this CNN is subject dependent, in which subjects 2, 4, 8, 10 and 15 showed the highest accuracy’s of their sessions, indicating these individuals hold a greater influence on the dataset. Also proven is that this CNN could have be tailored to the dataset further to increase the accuracy and more so henceforth.



### Built With

LaTeX, Overleaf, BibTeX

### Other Infomation

The folder is roughly 6GB.

Project Source: https://www.kaggle.com/datasets/disbeat/bciaut-p300 </br>
MatLab Files: https://github.com/Mysftz/brain-computer-interface-classification-matlab </br>
Python Files: https://github.com/Mysftz/brain-computer-interface-classification-python </br>
LaTeX Thesis: https://github.com/Mysftz/brain-computer-interface-classification-thesis

<p align="right">(<a href="#readme-top">back to top</a>)</p> 

<!-- USAGE -->
## Usage

This report was submitted for the degree of a Bachelors of Science in Astronomy, Space Science and Astrophysics at the University of Kent in March 2020.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License
Distributed under the CC-BY-SA-4.0: Creative Commons Attribution Share Alike 4.0 International License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- OTHER PROJECTS --> 
## Other Projects
<div align="center">
<a href="https://github.com/stars/Mysftz/lists/data-science-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-DataScience.jpeg?raw=true" alt="Data Science Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/data-analysis-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-DataAnalysis.jpeg?raw=true" alt="Data Analysis Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/university-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-University.jpeg?raw=true" alt="University Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/python-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-Python.jpeg?raw=true" alt="Python Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/latex-projects" style="margin:10px; padding-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-Latex.jpeg?raw=true" alt="LaTeX Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/other-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-Other.jpeg?raw=true" alt="Other Projects Button" width="265" height="75"></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact
<div align="center">

GitHub: [@Mysftz](https://github.com/Mysftz) &nbsp;&middot;&nbsp; Portfolio: [Website](https://mysftz.github.io) &nbsp;&middot;&nbsp; LinkedIn: [@lrgtomaszewski](https://www.linkedin.com/in/lrgtomaszewski/) &nbsp;&middot;&nbsp; Instagram: [@Mysftz](https://www.instagram.com/mysftz/) &nbsp;&middot;&nbsp; Twitter: [@MysftzUK](https://twitter.com/MysftzUK)
</div>

[contributors-shield]: https://img.shields.io/github/contributors/mysftz/brain-computer-interface-classification-thesis.svg?style=for-the-badge
[forks-shield]: https://img.shields.io/github/forks/mysftz/brain-computer-interface-classification-thesis.svg?style=for-the-badge
[stars-shield]: https://img.shields.io/github/stars/mysftz/brain-computer-interface-classification-thesis.svg?style=for-the-badge
[issues-shield]: https://img.shields.io/github/issues/mysftz/brain-computer-interface-classification-thesis.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/mysftz/brain-computer-interface-classification-thesis.svg?style=for-the-badge
[github-shield]: https://img.shields.io/badge/-GitHub-black.svg?style=for-the-badge&logo=GitHub&colorB=555