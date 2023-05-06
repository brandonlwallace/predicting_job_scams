# **Identifying Fraudulent Job Postings**
by  
## Candice Chiang and Brandon Wallace
## wantienc & blwallac [@] andrew.cmu.edu
## Carnegie Mellon University

### **Sections:** 
  
#### 1. Data Cleaning  
#### 2. Exploratory Data Analysis  
#### 3. Sampling  
#### 4. Splitting
#### 5. Feature Engineering  
#### 6. Machine Learning 

### **Overview**  

Using publicly available information on a standard job-board website, we developed an approach to successfully identify fraudulent job postings 95% of the time with 63% percent recall. Our objective was to identify the rare cases of scams on job boards to flag them in the future for content moderators.  
    
Graduate students in professional programs are actively seeking post-graudate opportunities. For most students, this is a stressful process that requires sifting through dozens of online job boards and websites containing thousands of postings relevant to their feild of study. [The Federal Trade Commission estaimted](https://www.cnbc.com/2022/06/10/americans-lost-68-million-to-job-scams-this-year-here-are-the-most-common-ones.html) that Americans lost $68 million in scams due to fake business and job opportunities in 2022. These scams can be even more pronounced for international students who are unfamiliar with domestic job boards and face incredible pressure to secure a job which can sponosor their continued stay in country. This solution helps job board websites understand how compromised their content is which ultimately protects job seekers from criminals.   
  
Fraudulent jobs expose individuals to scams. This can result in monetary damages but also important unseen costs in lost personally identifying information. Fraudulent jobs also negatively impact the reputation of job boards designed by companies who are trying to provide a valuable product. Lastly, fraudulent jobs present challenges for governments as well who support job-seekers and unemployed individuals with costly benefits programs.

  
This notebook contains the full process. We discover abstract topics from job descriptions using Latent Dirichlet Allocation(LDA) and then utilize supervised learning with a lableled dataset to predict whether a job is fraudulent or legitimate with a random forest algorithm also employing Synthetic Minority Oversampling Technique (SMOTE) for unbalanced classes. 
