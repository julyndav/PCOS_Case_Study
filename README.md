# PCOS: A Case Study Analysis
Polycystic Ovary Syndrome (PCOS) is a hormonal disorder and a leading cause of infertility, affecting millions worldwide and characterized by a diverse range of symptoms, both physical and mental.

This case study, conducted in 2023, uses data collected through a Google survey by a team of final-year engineering students. The survey's goal was to gather detailed information on various factors related to PCOS, to aid in the development of a machine learning-based PCOS risk prediction system.

The interactive PowerBI dashboard developed for this project serves as an informative and visually engaging infographic. It not only presents the findings from the data analysis but also aims to educate viewers a little about PCOS and its main symptoms. 
 <br></br>

### Table of Contents:
[Data Source](https://www.kaggle.com/datasets/sahilkoli04/pcos2023)
<br></br>

### Skills Demostrated
<ul>
<li>Data extraction and loading</li>
<li>Data cleaning (Power Query)</li>
<li>Creating calculated columns</li>
<li>Data Analysis Expression (DAX) Functions</li>
<li>Dashboard design</li>
<li>Data Visualisation</li>
</ul>
<br></br>

# My Analysis Process:

### Reviewing the Data:
<ul>
<li>Reviewed the provided data consisting of one csv file on the Kaggle platform.</li> 
<li>Loaded the working data into a Jupyter notebook for initial cleaning and data preparation.</li>
<li>Power BI for initial data cleaning, formatting, and manipulation which was minimal.</li>
</ul>  
<p>
  
### Processing Data:
<ul>
<li>Reviewed dataset structure and information.</li>
<li>Revised column headings to something shorter.</li>
<li>Changed weight from kilograms to pounds and height from centimeters to inches.</li>
 <li>Dataset was checked for duplicates and null values.</li>
</ul>
<p></p>

#### Revising Column Lables:
| Revised | Original Column Lable |
| --- | --- |
| Age | No Change |
| Weight (in Kg)| No Change |
| Height (in Cm) | No Change |
| Blood Group | Can you tell us your blood group? |
| Weight Gain | Have you gained weight recently? |
| Body_Facial Hair Growth | Do you have excessive body/facial hair growth? |
| Skin Darkening | Are you noticing skin darkening recently? |
| Hair Loss | Do have hair loss/hair thinning/baldness? |
| Acne | Do you have pimples/acne on your face/jawline? |
| Regular Fast Food | Do you eat fast food regularly? |
| Regular Excercise | Do you exercise on a regular basis? |
| Diagnosed PCOS/PCOD? | Have you been diagnosed with PCOS/PCOD? |
| Mood Swings | Do you experience mood swings ?  |
| Periods Regular? | Are your periods regular? |
| Period Frequency | After how many months do you get your periods?(select 1- if every month/regular)  |
| Duration | How long does your period last ? (in Days) |
| Age_Range_Groups |<i> *Calculated Column</i> |
| PCOS |<i> *Calculated Column </i> |

  
### Dashboard Concept:
<ul>
<li>Outlined key metrics and potential visual ideas.
<li>Designed the overall aesthetic and layout to ensure an informative user-friendly interface.</li> 
<li>The background and icons were designed and exported from PowerPoint.</li>
</ul>
<br></br>


# Dashboard & Analysis Overview:
### Section 1: Introduction
![sect1](https://github.com/julyndav/PCOS_Case_Study/blob/main/Images/DashBrd1.png)

<ul>
<li>Gives a brief synopsis of PCOS</li>
<li>22% of the participants have been diagnosed with PCOS.</li>
<li>78% of the participants stated that they have not been diagnosed with PCOS.</li> 
</ul>
<br></br>

### Section 2: Age Analysis
![sect2](https://github.com/julyndav/PCOS_Case_Study/blob/main/Images/Images/DashBrd2.png)

<ul>
 <li>Even though there were only 465 participants, the data still provided an valueable insight into the symptoms of PCOS.</li>
 <li>Out of 465 participants, Age groups outside of the 20-35 range are very limited. This limited representation restricts the findings across different age groups, particularly for those over 50. Insights from this study may not capture a true spectrum of the population, this will limit any analysis of age-related conclusions.</li>
</ul>
<br></br>

### Section 3: Effects 

![Sect3](https://github.com/julyndav/PCOS_Case_Study/blob/main/Images/Images/DashBrd3.png)

<ul>
 <li>Majority of participants experience "regular" menstural cycles. One occurs every month and lasts 4-6 days.</li>
 <li>Results for those over 50 are not shown as the data was negligible.</li>
     - Menstrural Fregquency: (4) Participants have periods everyone with (1) having periods every 3 months.<p>
     - Periods lasts approximately 4 days.
</ul>

### Symptoms
![Sect4](https://github.com/julyndav/PCOS_Case_Study/blob/main/Images/Images/DashBrd4.png)<p>
###### <i>If you find yourself having these symptoms and are concerned about them, please see your health care provider.</i><p>

<ul>
 <li>The interactive dashboard can be filtered by age group and diagnosis. </li>
 <li>Hormonal changes can affect a variety of things both physical and mental. The symptoms shown here are what were part of the case study.</li>
 
<br></br>

