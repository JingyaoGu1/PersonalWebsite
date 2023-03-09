<template>
    <div class="projects-container">

  
      <a class="projects-header">RECENT PROJECTS</a>

      <div class="project-container clickable">
        <a class="project-container__title">Online Petshop</a>
        <a class="project-container__sub-title">Full Stack Application</a>
        <a class="project-container__desc">
          I made a basic pet shop website that supports CRUD operations. 
          For pet shop owners, the application supports inserting, removing, or deleting a pet or a pet shop. 
          For the pet buyers, the application provides a search function so that users can quickly find the pets or pet shops they are interested in.
        </a>
      </div>

      <div class="project-container clickable">
        <div class="project-container__title">Website2023</div>
        <a class="project-container__sub-title">Personal Website</a>
        <a class="project-container__desc">
          The website you are currently viewing using Vue.js framework.
        </a>
      </div>

      <div class="project-container clickable">
        <a class="project-container__title">Music Orchard</a>
        <a class="project-container__sub-title">IOS APP</a>
        <a class="project-container__desc">
          A game with original graphics and audio that aims to teach young children music.
          I Designed User Interfaces, User Flows and usable interactions in Swift and in Xcode to track children’s click and turn
          that click into the sound, where each fruit tree represents an instrument and each fruit on the tree represents a note.
        </a>
      </div>

      <div class="project-container clickable">
        <a class="project-container__title">Speech Recognition</a>
        <a class="project-container__sub-title">AI</a>
        <a class="project-container__desc">
          I used data from TensorFlow's speech Commands Datasets and modified a Convolutional Neural Network to achieve a
          recognition of 30 different words with an accuracy of more than 90%
        </a>
      </div>

      <div class="project-container clickable">
        <div class="project-container__title">Predator-Prey System</div>
        <a class="project-container__sub-title">Parallel Computing</a>
        <a class="project-container__desc">
          I modeled the predator-prey system in c++ and created a CUDA random number generator for modeling.
          I Improved modeling efficiencies by using multi-core processors as well as openACC models by as much as 1000%.
        </a>
      </div>

      <div class="project-container clickable">
        <a class="project-container__title">Covid Prediction</a>
        <a class="project-container__sub-title">Bayesian Statistics</a>
        <a class="project-container__desc">
          I used Markov Chain Monte Carlo method to investigate how factors such as state and time can help us predict future
          COVID-19 outbreaks.
        </a>
      </div>

      <div class="project-container clickable">
        <a class="project-container__title">Saint Paul Crime</a>
        <a class="project-container__sub-title">Data Visualization</a>
        <a class="project-container__desc">
          I used data from Saint Paul public dataset, which includes over
            300,000 indivial incidents that happened between 2017 and 2021. We
            then created multiple interactive visualizations to tell a story.
        </a>
      </div>

      <div class="project-container clickable">
        <a class="project-container__title">BillBoard Top</a>
        <a class="project-container__sub-title">Survival Analysis</a>
        <a class="project-container__desc">
          This project aims to analyze how long a piece of music will last on
            the Billboard Weekly Top 100 chart based its attributes. We include
            models like Kaplan-Meier, Cox-PH model and AFT model to help better
            understand how the rankings change over time.
        </a>
      </div>

      <div class="project-container clickable">
        <a class="project-container__title">Beijing Air Quality</a>
        <a class="project-container__sub-title">Statistical Machine Learning</a>
        <a class="project-container__desc">
          I used two supervised learning methods, namely regression and
            classification, to analyze what's affecting Beijing's air quality
            and to predict what's tha air quality will be based on given data.
        </a>
      </div>

    </div>
  </template>
  
  <style scoped>


  .projects-container {
    position: absolute;
    top: 0%;
    right: 0%;
    width: 50%;
    height: auto;
    padding: 100px;
    overflow: none;
    display: flex;
    flex-direction: column;
  }

  .projects-header {
    color: #ac3b61;
    font-size: 44px;
    letter-spacing: 6px;
    margin-bottom: 20px;
    margin-top: 20px;
  }
  .project-container {
    position: relative;
    width: 100%;
    padding: 14px;
    margin-top: 20px;
    margin-bottom: 20px;
    background-color: #123c69;
    border: 1px solid #0071de;
    border-radius: 4px;
    transition: 1s cubic-bezier(0.075, 0.82, 0.165, 1) all;
    overflow: hidden;
    overflow-x: hidden;
    overflow-y: hidden;
    display: flex;
    flex-direction: column;
  }
  .clickable:hover {
    box-shadow: 0 0 8px 2px #0071de;
    transform: scale(1.01);
  }

  .project-container__title {
    font-size: 22px;
    color: #2ce692;
    margin-bottom: 10px;
  }
  .project-container__sub-title {
    font-size: 15px;
    color: #ffffff;
    margin-bottom: 10px;
  }
  .project-container__desc {
    font-size: 16px;
    line-height: 32px;
    color: #eee2dc;
    margin-bottom: 10px;
  }
  @media (max-width: 800px) {
    .projects-container {
      position: relative;
      width: 100%;
      height: auto;
      padding: 20px;
    }
  }
  </style>