# Alzheimer’s Disease Analysis 
## AI Bootcamp: Project One

### Group Members:
* Katia Monteros
* Madeline Jankowski
* James Kim

### Dataset Overview
The Alzheimer's dataset contains medical information from 2,149 patients and includes 35 columns. It covers a range of factors that may contribute to Alzheimer's Disease, including demographic details, lifestyle factors, medical history, and reported symptoms.

### Instructions to Run the Code
1. Clone the Repository
* Open terminal on the local machine and run the following command:
  
```git clone https://github.com/maddiejane25/Project-1.git```

2. Set Up Environment
* Make sure Python is installed on the computer
* Open terminal on the local machine and run the following commands:

```cd Project-1```

```pip install pandas numpy matplotlib seaborn```

3. Run the Code
* Open the project folder in an IDE (Jupyter Notebook, Google Colab or VSCode)
* Import necessary files
* Start running the code
  
### Project Overview
This project focuses on the analysis of an Alzheimer's dataset to identify trends in demographics, lifestyle factors, and health-related risks associated with the disease. In the healthcare industry, there is active research studying this disease and a focus on preventative care as an aging population. The cause of Alzheimer’s is still largely unknown, and almost 62% of healthcare practitioners worldwide incorrectly identify dementia as a normal part of aging. This project will aim to identify valuable patterns that can contribute to better detection and understanding of Alzheimer’s disease. 

### What is Alzheimer’s?
Dementia is an umbrella term used to describe different brain disorders that affect memory, thinking, behavior and emotion. Alzheimer’s disease is characterized by the buildup of a protein called ‘beta-amyloid’ outside of brain cells and tangled strands of a protein called ‘tau’ inside these cells. This is often linked to the death of brain cells and harm to brain tissue. In addition, there can be inflammation and shrinkage of the brain tissue. 
* There is a spectrum of Alzheimer’s, ranging from asymptomatic to severe
* In the US alone, there is nearly 7 million people living with Alzheimers
* Although the medical community is starting to understand more about the disease, there is currently no known prevention or cure
* Early detection is key to having the most options and preventing furthering of the disease

### Problem Statement
* The cause of Alzheimer’s is still largely unknown
* There is a growing elderly population - in 2022, almost 58 million people were over 65, and all of the Baby Boomer population will be over 65 by 2030.
* Almost 62% of healthcare practitioners worldwide incorrectly think that dementia is part of normal ageing
* There is no known definitive cause for Alzheimer’s

### Hypothesis
Before analyzing the dataset, we hoped to see patterns to answer:
* Which health conditions are most related to Alzheimer’s?
* What lifestyle factors factors contribute most to Alzheimer’s?
* What can we glean from the numbers of patients with symptoms versus those who are diagnosed?

Our initial thought is, that even though there is no definitive cause for why people get Alzheimer's, many different factors like demographics, lifestyle, medical history, and others, would have an impact in an individual getting Alzheimer's disease. For example, we think people that are diagnosed with Alzheimer's disease would have more unhealthy lifestyle and have worse medical history.  

### Analysis and Findings

1. **General Statistics**
**Dataset includes:** 2149 patients | 35 categories
*Note: Data covers a range of factors that may contribute to Alzhiemers Disease*

![download (1)](https://github.com/user-attachments/assets/2f8fd53a-6eb2-4d2a-9cf5-7bf4ead8c00f)

2. **What factors most significantly affect the risk of Alzheimer's disease?**
We broke down the data a few different ways. Mostly we compared and analyzed the data around patients that were diagnosed with Alzheimer's Disease. After looking at the different results, there were not any factors that stood out to be the most significant factor that affects the risk Alzheimer's disease. One that we could possibly point out is when you compare the age of patients there is a significant spike when the patients hit around the age of 90.

![age](https://github.com/user-attachments/assets/f1002916-c279-4cdb-91d8-78b3f72e5a3c)

3. **What were the most surprising answers/stats from the research?**
I think the lack of impact that the 35 categories had on affecting the risk of the patient getting Alzheimer's Disease was surprising to all of us. We are considering that the categories within the data are were not the best ones to identify what affects the risks of getting Alzhiemer's. However, even when you take a look at lifestyle section you can see that average scores and levels between each category (alc consumption lvl, sleep & diet quality score, physical activity score, bmi levels, etc) were pretty much the same. If anything, the scores and levels were slightly leaning towards the opposite of what we would have guessed. 

![download (2)](https://github.com/user-attachments/assets/b3e84aec-3a0f-4ddd-b8f7-c897af8a95a9)

4. **Were there any answers/stats that supported our initial hypothesis?** 
No. Maybe beside the patients reaching the age of 90 being much higher than any other age of patients diagnosed with Alzheimers there were not any other answers or stats within the data that supported or was consistent with our initial thoughts/hypothesis.

![heatmap](https://github.com/user-attachments/assets/b45675ec-aa52-4026-9cf0-b4297cd088e8)

5. **Is the data consistent to what the general belief is on what causes Alzheimer's diesease?** 
No it is not consistent to what the general belief and what other studies show about what can increase or decrease the risk of getting Alzheimer's Disease. For example: A population-based study of 1,500 people on aging and dementia in Finland found that those who engaged in leisure-time physical activity at least twice a week through middle age, carried half the risk of developing dementia and a 60 percent lower risk of developing Alzheimer’s than did those who remained sedentary in their midlife.

![PA](https://github.com/user-attachments/assets/9eedf494-fbb1-4857-a6f9-416a31aaedb2)


### Conclusion
Our investigation into the Alzheimer’s dataset aimed to uncover trends and factors influencing the onset of Alzheimer’s disease. Our analysis spanned across various demographics, lifestyle choices, and medical histories of 2,149 patients. Despite the comprehensive data, our findings did not significantly align with the established assumptions or our initial hypothesis regarding the key factors that contribute to the risk of developing Alzheimer’s disease.

Interestingly, no single factor from the 35 categories analyzed stood out as a significant contributor to Alzheimer’s risk. Even lifestyle factors, which we hypothesized would show clear correlations, such as alcohol consumption levels, diet quality, physical activity, and BMI, did not differ markedly between patients diagnosed with Alzheimer’s and those not diagnosed. This suggests that the complexity of Alzheimer’s etiology might require a broader or different set of data to uncover meaningful insights.

Our research highlighted an age-related increase in Alzheimer’s incidence around the age of 90, which was one of the few findings that aligned with general expectations about the disease’s demographics. However, the overall lack of supporting data for other hypothesized risk factors points to the possibility that either additional variables not included in the dataset are at play or that the interconnections between the studied factors and Alzheimer’s are more intricate than straightforward causative relationships.

Contrasting our dataset with other studies, such as the Finnish study on physical activity and dementia, suggests that our dataset may not have captured all relevant variables or that our analytical methods need to be adjusted to capture subtler relationships within the data.

In conclusion, while our project did not confirm many of the anticipated relationships between lifestyle factors and Alzheimer’s risk, it has underscored the complexity of the disease and the challenges inherent in identifying its causes through epidemiological data. Future research should consider incorporating a wider range of variables, including genetic data and longer longitudinal studies, to better understand the multifactorial pathways leading to Alzheimer’s disease. This could potentially refine the models used to predict the risk and offer more targeted avenues for prevention and treatment.

### Link to presentation 
https://docs.google.com/presentation/d/1Jso8WWEu9hQWXNIS7uPPgmhKFAz1belmoBMniuzeSSU/edit?usp=sharing

### Citations
@misc{rabie_el_kharoua_2024,
title={Alzheimer's Disease Dataset},
url={https://www.kaggle.com/dsv/8668279},
DOI={10.34740/KAGGLE/DSV/8668279},
publisher={Kaggle},
author={Rabie El Kharoua},
year={2024}
}
https://www.alz.org/media/Documents/alzheimers-facts-and-figures.pdf

2022 Alzheimer’s Disease Facts and Figures, www.alz.org/media/Documents/alzheimers-facts-and-figures.pdf. Accessed 23 Oct. 2024.

“Adi - Dementia Facts & Figures.” Alzheimer’s Disease International (ADI), www.alzint.org/about/dementia-facts-figures/. Accessed 23 Oct. 2024.

“Adi - Dementia Statistics.” Alzheimer’s Disease International (ADI), www.alzint.org/about/dementia-facts-figures/dementia-statistics/#:~:text=Diagnosis,treatment%20gap%20can%20be%20closed. Accessed 23 Oct. 2024.

Alzheimer’s Disease Fact Sheet | National Institute on Aging, www.nia.nih.gov/health/alzheimers-and-dementia/alzheimers-disease-fact-sheet. Accessed 23 Oct. 2024.

“Alzheimer’s Disease.” Mayo Clinic, Mayo Foundation for Medical Education and Research, 10 July 2024, www.mayoclinic.org/diseases-conditions/alzheimers-disease/symptoms-causes/syc-20350447.

Arab, Lana, and Marwan N Sabbagh. “Are Certain Lifestyle Habits Associated with Lower Alzheimer’s Disease Risk?” Journal of Alzheimer’s Disease : JAD, U.S. National Library of Medicine, 2010, pmc.ncbi.nlm.nih.gov/articles/PMC3207358/#:~:text=A%20population%2Dbased%20study%20of,those%20who%20remained%20sedentary%20in.

Understanding Alzheimer’s and Dementia, www.alz.org/media/Documents/alzheimers-dementia-understanding-alzheimers-and-dementia_ts.pdf. Accessed 23 Oct. 2024.

What Are the Signs of Alzheimer’s Disease? | National Institute on Aging, www.nia.nih.gov/health/alzheimers-symptoms-and-diagnosis/what-are-signs-alzheimers-disease. Accessed 23 Oct. 2024. 
