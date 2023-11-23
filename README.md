<h1 align="center">Mini-SurveyMonkey [Group 5] <a href="https://circleci.com/gh/Imcool4789/Mini-SurveyMonkey/tree/master"><img src="https://circleci.com/gh/Imcool4789/Mini-SurveyMonkey/tree/master.svg?style=svg"></a></h1>

<p align="center">
  <a href="https://spring.io/">
    <img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" alt="Spring">
  </a>
  <a href="https://www.thymeleaf.org/">
    <img src="https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white" alt="Thymeleaf">
  </a>
  <a href="https://circleci.com/">
    <img src="https://img.shields.io/badge/circle%20ci-%23161616.svg?style=for-the-badge&logo=circleci&logoColor=white" alt="CircleCI">
  </a>
  <a href="https://www.mongodb.com/">
    <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white"
  </a>
</p>

<p align="justify">
 The Mini-SurveyMonkey Spring Boot application is a platform for creating and managing surveys. It supports a variety of question types such as multiple choice, number range, and open-ended, and allows surveyors to close surveys and retrieve responses at any time. Users can view and complete surveys, with their responses securely stored. The application generates outputs for each question in various formats based on the question type.
</p>

## 📑 Table of Contents

- [📑 Table of Contents](#-table-of-contents)
- [🌟 Features](#-features)
- [📋 Pre-requisites](#-pre-requisites)
- [⚙️ Setup](#️-setup)
- [🚀 Run Instructions](#-run-instructions)
- [🔍 Testing](#-testing)
- [🔗 Relevant Links](#-relevant-links)
- [👥 Authors](#-authors)

## 🌟 Features

- The ability to login and navigate as a `surveyor` or a `user`
- A `surveyor` can:
  - Create surveys with questions of various types such as multiple choice, number range, and open-ended
  - Add new questions to an existing survey
  - Delete individual questions within an existing survey
  - Close surveys at any time and view results instantaneously
  - Can switch between `user` and `surveyor` view at any time
- A `user` can:
  - Answer questions within a survey
  - View their progress throughout the survey via the progress bar shown at the bottom of the page
  - View the result of a survey upon completion
- Results can be viewed as a whole spanning the entire survey and each question separately
  - Results will be displayed as simple text, histogram, or a pie chart based on the question type
- Survey results can be exported to a .pdf file

## 📋 Pre-requisites

Ensure that the following dependencies are installed onto your machine by following the [Setup Instructions](#⚙️-setup).

- [Java](https://www.java.com/en/download/manual.jsp)
- [Maven](https://maven.apache.org/download.cgi)

## ⚙️ Setup

1. Clone this repository to your local machine.

```bash
git clone https://github.com/vikiru/Mini-SurveyMonkey.git
cd Mini-SurveyMonkey
```

2. Download and install all dependencies.

```bash
mvn install
```

## 🚀 Run Instructions

1. Clean and package the project.

```bash
mvn clean package
```

2. Run the main program.

```bash
java -jar ./target/Mini-SurveyMonkey-0.0.1-SNAPSHOT.jar
```

## 🔍 Testing

Run the following command to execute all of the tests:

```bash
mvn test
```

## 🔗 Relevant Links

- [CircleCI Pipeline](https://circleci.com/gh/Imcool4789/Mini-SurveyMonkey/tree/master)
- [Kanban Project Board](https://github.com/Imcool4789/Mini-SurveyMonkey/projects/1)
- [Project Wiki](https://github.com/Imcool4789/Mini-SurveyMonkey/wiki)

<h2>📊 Diagrams</h2>
<p align="center">
    <img src="https://user-images.githubusercontent.com/56265739/162431989-f7d0e994-a048-4459-9915-1956ad734a3d.png" alt="Database Diagram">
    <p align="center">  Fig. 1 Database Diagram</p>
    <img src="https://github.com/Imcool4789/Mini-SurveyMonkey/blob/master/diagrams/Group5_Class_UML_Vis_Kirubakaran.png" alt="UML Class Diagram">
    <p align="center"> Fig. 2 UML Class Diagram</p>
</p>

## 👥 Authors

- John Warde
- Kashish Saxena
- Vis Kirubakaran
