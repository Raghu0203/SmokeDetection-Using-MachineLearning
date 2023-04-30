# Smoke Detection Using Supervised Machine Learning

###**Task 1: Business Understanding**

1. What is the main goal of the project?
    - The main goal of the project is to predict smoke as accurate as possible.

    ####**Task 1.2 Business Problem that can be solved.**

  -  With an increasing number of smoke alarms at homes, work places, shopping centers etc., the number of false fire alarms are increasing continuously. Which could be a serious issue.


  **<center><h4>Predictive analytics solution</h4></center>**

Possible predictive analytics solutions:

**Solution 1: Smoke detection using air particles**


*   A model could be built to detect smoke in different closed-space conditions and distinguisg between real smoke from fire and genral smoke.
*   **Required Data:** Temperature, Airpressure, genreal particulate matter information
* **Required Businees Capacity:**  Ability to collect information like different temperatures and airpressure during the event of a smoke and combine it with other factors like particulate matter information.


**Solution 2: Smoke Detection based on chemical analysis**


*   A model could be built to predict that particular smoke is a genuine smoke from fire or it is a smoke form some chemicals. Since some chemicals in the laboratory setting release smoke that looks and smells like smoke from fire. By predicting this will help reduce false alarms.
*   **Required Data:** Air humidity percentage, Total Volatile Organic Compounds, Air particulate matter size
* **Required Business Capacity:** Ability to get data like volatile Organic Compounds to predict smoke from chemicals and reduce fire alarms.


**Solution 3: Smoke detection from surveillance video**

*   A model could be built to distinguish fire smoke and trigger alarms based on live surveillance video.
*   **Required Data:** Many labelled video instances of smoke in closed spaces to train the model.
* **Required Business Capacity:** Deployment of the developed model and training staff on how to use the system.


**Solution 4: False Smoke Detection from dust, home cooked foods**

*   A model could be built to distinguish real smoke from fire and smoke from home cooked foods. In general, if the house hold does not have any mechanism to take out smoke from cooked foods it could trigger false alarms.
*   **Required Data:** Co2 equivalent concentration, hydrogen levels in the air etc.,
* **Required Business Capacity:** Ability to get required data from labarotary setting and implement ways of detecting the data and distinguishing the smoke. 

####**<center>Final Prediction Solution</center>**

We picked solution 1 as our final prediction solution. For this business problem it is important to generalize the smoke detection based on different factors and predict what smoke it is and reduce the fire alarms. Also, the dataset we are using contains all the data to cover different smoke scenarios as it contains data like carbon dioxide levels, particulate matter etc,. By using this dataset we can build and train the machine learning model that could predict whethet the smoke is a leigtimate smoke from a fire or from other different sources. Not only it will predict the smoke but also it can help reduce the fire alarms.





