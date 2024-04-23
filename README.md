# Diamond group
Group created for tackling the group project 2 (Data science and explainability of models evaluation) for the comp5013 module. 

### Group project 2 details:
Given the Titanic dataset. Use the dataset to generate AI models which can make accurate predictions. This will require data analysis/exploration, data preprocessing, model generation and evaluation. You must consider a minimum of 4 models (linear regression, random forest, deep neural network, shallow neural network) and contrast their accuracy, appropriability and explainability. You may also recommend/evaluate common XAI techniques on the models, such as SHAP or LIME, when appropriate.

---

<details>
  <summary>What is your team? (team name, team members, individual responsibilities)</summary>
  <blockquote>
     
- Team name: Diamond
- Team members: 10649798, 10775412, 10788032
- Individual responsibilities: All responsibilities are shared
   
</details>
<details>
  <summary>How do you start the artefact you developed? How do you open and control the software you wrote?</summary>
  <blockquote>
   
- You can start the developed artefact by either cloning the repository into your preferred jupyter notebook IDE. Or by manually downloading the repository as a ZIP, extracting the ZIP into a folder of your choosing, and then accessing the folder with your preferred jupyter notebook IDE.
- The jupyter notebook is for viewing only, there is nothing to control. This is because the task was to only contrast the differences between the different models.
   
</details>
<details>
  <summary>How does the program code work?</summary>
  <blockquote>
     
- The program code works by importing the titanic dataset -> analysing and exploring the data -> preprocessing the data -> then generating models and evaluating them -> and finally explaining the models with XAI techniques such as SHAP
   
</details>
<details>
  <summary>What is your contribution to the research/methodology?</summary>
  <blockquote>
  <details>
    <summary>Where did you get the idea from?</summary>

 - We used the idea suggestion from the slides on the DLE, which were put together by our module leaders.

  </details>
  <details>
    <summary>What did you start with?</summary>

 - We did not start with anything out of the ordinary. We used official and community approved libraries to create our own code, which we learned how to do during our course and independent studies. 

  </details>
  <details>
    <summary>How did you make yours unique?</summary>

 - There is not much uniqueness to it, we used well known and used methods to put the code together. If there is something unique about it, it is how the code is structured and put together

  </details>
  <details>
    <summary>Did you start with a given project?</summary>

 - We were given the idea by our module leaders, but no code was given to us.

  </details>
  <details>
    <summary>Key findings</summary>

 - In the case of the titanic dataset, the accuracy does not seem to change much based on the hyperparameters of our models. On the other hand, the data manipulation and pre-processing seems to affect the accuracy much more.

  </details>
  <details>
    <summary>Results</summary>

 - We ended up with the following cross-validation accuracy scores for our models:
   - Accuracy score for Logistic Regression: 0.834
   - Accuracy score for Random Forest: 0.851
   - Accuracy score for Deep Neural Network: 0.840
   - Accuracy score for Shallow Neural Network 0.834
 - We also found that all of our models can be relatively easily explainable with the SHAP library. However, some models take much more time to explain than others. This was especially the case for the DNN where the SamplingExplainer took around an hour to produce the explanations for the testing dataset, whereas other models took between couple of seconds to no more than 10 minutes.
 - Additionaly, we swapped Linear Regression for Logistic Regression. We did this because we found it more appropriate, after reading through the documentation on the input data of the models. With that change, all of the models that were used are appropriate for the task.

  </details>
  <details>
    <summary>Analysis</summary>

 - During our project we analysed how the different data handling and hyperparameters tuning affects the accuracy, for more details please view the jupyter notebook. 

  </details>
  <details>
    <summary>Metrics</summary>
     
 - We mainly focused on accuracy, as that was our main goal. But we kept track of few more metrics to make sure our models are performing as we are expecting them.

  </details>
</details>



https://user-images.githubusercontent.com/57765511/233865556-a0974d6b-efef-4a20-856f-33e3b6773835.mp4


   
[**⬆ back to top ⬆**](#top)
