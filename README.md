# The "Childhood Allergies: Prevalence, Demographics"
# Big-Data-Group-16
This project is a part of the ITCS 6100 - Big Data Analytics for competitive Advantage course from the University of North Carolina at Charlotte
# Deliverable – 1


## 	Team

### a)	Members
•	Bhavya Sri Killi

•	Rithika Bejjanki

•	Maneesh Reddy Kapireddy

•	Rahul Reddy Gangula

•	Nagarjuna Challa


### b)	Communication plan to include project artifact repository

1.	Zoom meetings.
2.	Atkins Library

## 	Communication plan

Communication channels: Discord for daily team conversation and syncing. We will be using email as a formal way of communication.

Communication frequency: 40 mins long stand-up call on Zoom every alternate day to check the progress of the project.

Work division: Tasks are divided among team members efficiently any work overload can be brought to the team's notice and discussed to resolve them.

Meeting agendas: Update on tasks assigned to everyone, assign new tasks, and plan future developments, discussing issues faced and collectively working to fix them.

## Project artifact repository:

Git Link: https://github.com/challanagarjuna99/Bigadata-project/blob/main/README.md

Dataset
Kaggle: [https://www.kaggle.com/datasets/thedevastator/childhood-allergies-prevalence- diagnosis-and-tre](https://www.kaggle.com/datasets/thedevastator/childhood-allergies- prevalence-diagnosis-and-tre)


## 	Selection of data to analyze

The "Childhood Allergies: Prevalence, Demographics" dataset on Kaggle is an excellent choice for analysis. This dataset contains information on childhood allergies, including the prevalence rates and demographics of children with allergies. The dataset includes 6 columns and over 100,000 rows of data, including information on allergies such as asthma, eczema, hay fever, and food allergies.

To analyze this dataset, you could start by exploring the prevalence rates of different types of allergies among children in different age groups, genders, and regions. You could also investigate the relationship between allergies and other demographic factors such as ethnicity, socio-economic status, and geographic location. Additionally, you could examine the trends in allergy prevalence rates over time and compare them to changes in environmental factors such as pollution levels and climate patterns.

##  Business Problem or Opportunity

The chosen dataset can be used to address various business problems and opportunities such as:
Improving allergy diagnosis and treatment: The dataset reveals that millions of children suffer from allergies, and many cases go undiagnosed or untreated. A business opportunity could be to develop better diagnostic tools and treatment options for childhood allergies. This could include investing in research and development of new medications, therapies, or diagnostic tests.

Expanding access to allergy care: The dataset also shows that certain demographic groups are more susceptible to allergies, including children from low-income families or certain ethnic groups. A business opportunity could be to expand access to allergy care for these underserved populations. This could include opening new clinics or telemedicine services in areas with high allergy prevalence rates or providing financial assistance to families who cannot afford treatment.

Marketing and product development: For companies that already sell allergy-related products, the dataset offers valuable insights into the demographics and prevalence rates of different types of allergies. This information could be used to develop targeted marketing campaigns or new products that cater to specific allergy types or age groups. For example, a company that sells asthma medications could develop an advertising campaign targeting parents of boys, who are more likely to have asthma than girls.

Overall, the "Childhood Allergies: Prevalence, Demographics" dataset presents several business problems and opportunities related to the prevention, diagnosis, and treatment of childhood allergies. By analyzing this data, companies can gain insights into the factors that contribute to allergy susceptibility and develop strategies to address these issues.

## Domain Knowledge

The "Childhood Allergies: Prevalence, Demographics" dataset on Kaggle is related to the domain of healthcare and medicine. More specifically, it is related to the field of pediatric allergy and immunology, which focuses on the diagnosis, treatment, and prevention of allergies and immune system disorders in children.
To analyze this dataset effectively, some domain knowledge in the following areas may be helpful:
1. Allergy types: A basic understanding of the different types of allergies, such as food allergies, hay fever, eczema, and asthma, and their symptoms is essential. Knowledge of the physiological mechanisms of allergic reactions can also be helpful.
2. Epidemiology: An understanding of the epidemiology of allergies is important to analyze the prevalence of allergies in different demographic groups and regions. It can involve understanding risk factors, environmental exposures, and other factors that contribute to the development of allergies.
3. Medical terminology: A basic understanding of medical terminology and concepts such as diagnoses, treatments, and medication classes can be helpful when analyzing the dataset. This can help in interpreting columns such as "diagnosis_method" and "treatment".
4. Statistical analysis: Knowledge of basic statistical techniques such as descriptive statistics, correlation analysis, and regression analysis can be useful in exploring the relationships between variables in the dataset. It can also help identify trends over time and compare prevalence rates across different demographic groups.
Overall, a basic understanding of pediatric allergy and immunology, epidemiology, medical terminology, and statistical analysis can be helpful in analyzing the "Childhood Allergies: Prevalence, Demographics" dataset effectively.

## Research Objectives and Question(s) (what you are trying to describe or predict with the data)

The "Childhood Allergies: Prevalence, Demographics" dataset on Kaggle can be analyzed to achieve several research objectives and answer various research questions related to childhood allergies. Here are some potential research objectives and questions that can be addressed using this dataset:

1. What are the differences in the prevalence of allergies among different racial groups, and how have these patterns changed over time according to the NHIS data?
2. What are the trends in the prevalence of childhood allergies by gender over time, and how do these patterns compare between boys and girls?
3. What are the counts and percentages of 'Non-Medicaid' and 'Medicaid'?
4. Are there any significant differences in the distribution of allergies between males and females?
5. What is the distribution of birth years among patients with different allergies?
##
# Deliverable – 2
## Data Understanding
a) Exploratory Data Analysis

Through [AWS Sagemaker](https://github.com/challanagarjuna99/Bigadata-project/blob/main/Amazon%20SageMaker/Amazon%20Sagemaker.pdf), exploratory data analysis was carried out. The related file is uploaded here : [Exploratory Data Analysis](https://github.com/challanagarjuna99/Bigadata-project/blob/main/Exploratory%20Data%20Analysis/EDA.ipynb)



b) Dashboard


AWS Quicksight was used to construct dashboard instances. These dashboards are also examined in the Results section as a tool for addressing the goals and issues of the research. 
[Click here to view Dasboards](https://github.com/challanagarjuna99/Bigadata-project/blob/main/Amazon%20Quicksight/Dashboards.pdf)


## Data preparation

At every stage of the project, data preparation was done, including an initial study of the dataset structures listed in the Open Dataset Registry. Data preparation tasks include reading column data correctly based on the tool being used, considering anomalous data, erroneous values, manipulating the data, and more.
First, we removed the category tags that aren't needed for
similarly structured columns. For good measure we inspected our values for each column and
ensured that we didn't alter them in unwanted or unexpected ways.
##
# Deliverable - 3
## Analytics, Machine Learning

Using Amazon SageMaker, we performed Machine learning and analytics for predicting the results. We used different types of bar charts, pie plots, line graphs and heat maps to view the results. The dataset was train and tested with random forest and CatBoost algorithms. At first, we calculated the study duration for each patient, converted allergy data type to floats and calculated deltas for treatment data per allergy. These gave the best results to get final prediction.

(click Here to view the results){Project/childhood-allergy-prevalence-and-treatment-deltas .ipynb}


## Evaluation and Optimization

Performing machine learning on AWS will boosts the running computations. The machine learning model like Random forest which helps to find the predicted median value in the data, along with random forest we used Cat boost which adds best solutions with out parameter tuning that reduces time spent on parameter tuning because CatBoost provides effective results with default parameters. Using Scatter plot for visualizing the predicted values, based on the positive correlations of the plot helps the data scientist to analyse the stats for better understanding. By optimizing the models for the best fit, a scatter chat can help in setting up models.

## Results

### 1.What are the differences in the prevalence of allergies among different racial groups, and how have these patterns changed over time according to the NHIS data?

The chart reveals some interesting patterns in allergy prevalence by race over time. The prevalence of allergies is highest among non-Hispanic white children, with rates hovering around 10-12% over the years. Non-Hispanic black children have slightly lower rates of allergies, but still higher than Hispanic and other/mixed race children.
The chart also shows that allergy rates have remained relatively stable over time for all racial groups, with only minor fluctuations from year to year.

![1](https://user-images.githubusercontent.com/114270702/236357908-f1d0cc31-6d5e-4be1-a94d-58b34061d20e.jpeg)

### 2.What are the trends in the prevalence of childhood allergies by gender over time, and how do these patterns compare between boys and girls?

The chart reveals some interesting patterns in allergy prevalence by gender over time. For example, the prevalence of allergies is slightly higher among boys than girls, with rates hovering around 9-10% for boys and 8-9% for girls over the years. The chart also shows that allergy rates have remained relatively stable over time for both genders, with only minor fluctuations from year to year.

![2](https://user-images.githubusercontent.com/114270702/236304727-bad4b89b-a1c6-44c2-aaf1-97719075ed7d.jpeg)

### 3.What are the counts and percentages of 'Non-Medicaid' and 'Medicaid'?

The percentages of 'Non-Medicaid' and 'Medicaid' are represented in the pie chart subplot of the graph. By seeing the results we got to know that the percentage of non-medicaide is 73.93 and the percentage of medicaid is 26.07.The percentage value shown for each category represents the proportion of the total number of entries in the 'PAYER_FACTOR' column that belong to that category.

![3](https://user-images.githubusercontent.com/114270702/236306279-322905e9-76fe-4c7e-988e-b4ac57bf119e.jpeg)

### 4.Are there any significant differences in the distribution of allergies between males and females?

We can observe an increase in the allergies for 'male', but not significant. The pie chart slices are labeled with the categories 'Male' and 'Female', and the percentage of each category is displayed in each slice using the 'autopct' parameter. The male percentage of atopic derm is 51.90 and the female percentage of atopic derm is 48.10. 

![4](https://user-images.githubusercontent.com/114270702/236307129-5275f888-c983-48e4-a28d-6382309b3e2f.jpeg)

### 5.What is the distribution of birth years among patients with different allergies?

This is useful for visualizing the distribution of birth years for patients with different allergies, and may help identify any potential relationships between age and allergy prevalence.

![5](https://user-images.githubusercontent.com/114270702/236352658-c139d593-4f76-43f1-b50e-03cc9a8ee2f9.jpeg)

## Future Work,Comments

### What was unique about the data? Did you have to deal with imbalance? What data cleaning did you do? Outlier treatment? Imputation?

There are so many property values in the dataset like Gender_factor, Race_factor, Ethnicity_factor. There are so many unnecessary columns where we tried to remove them.Here we are using str.replace function to remove the unecessary or not required columns from the dataset. If the column name matches with hyphen or space or digit or blank as a word in the column names, then those column names are removed.

### Did you create any new additional features / variables?

We tried to implement many questions as we can analyze the whole dataset with different kinds of graphs like scatter plot, bar graph, piechart, Heat map, line graph etc., with these charts we implemented the indepth analysis of food allergies.

### What was the process you used for evaluation? What was the best result?

Finding the best solutions for the unknown data is challenging, for evaluation of the model comes under the accuracy provided by the model. The results that evaluated helps to find the most allergic food to the people.

### Is there Bias in your work? What were the problems you faced? How did you solve them?

No, We didn’t find any bias among ourselves. We helped each other while doing this project. The main problem is working with AWS for developing machine learning with tools its challenging to work but it helps us a lot by providing all required tools at one place and provides good performance. 

### What future work would you like to do?

Increasing public knowledge of children allergies, including their signs, causes, and treatment options, might help in increasing the accuracy of diagnoses and the effectiveness of treatments. Research in the future may concentrate on creating efficient awareness-raising and education programs for parents, caregivers, and medical professionals.

## Presentation Video









