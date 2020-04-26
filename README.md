# Investigate-Dataset

## <b> Overview </b>

In this project, the aim was to conduct my own data analysis and then communicate my findings about it.

The project had 3 steps:

### Step One - Choosing my dataset
The dataset chosen was the one with information of 100k medical appointments in Brazil and was focused on the question of whether or not patients showed up for their appointment. 

### Step Two - Analyze my data

I had to brainstorm some questions I could answer using the dataset I chose, then started answering those questions. I had to suggest questions that promote looking at relationships between multiple variables and had to analyze at least one dependent variable and three independent variables in my investigation. 

### Step Four - Share my findings

Once I finished analyzing the data, I had to create a report that shares the findings I found most interesting.

## <b> Tools </b>

Ir order to complete this project, I've used:

1. Python (Numpy, Pandas, Matplotlib, csv)
2. Jupyter Notebook

## <b> Conclusion </b> 

1. The **overwall no show rate** of this dataset is **20.2%**.  
2. Age is a key factor to predict if the patient is going to show up. The **no show rate tends to be lower the older the patient is**.  
3. Patients who **received a remind SMS have a 10% higher no show rate** than people who did not receive it, as counterintuitive as it is. In this case, gender does not matter, since both groups have almost the same no show rate.
4. Patients tend to **show up less for their appointments on Fridays and Saturdays** than the other week days, especially **Saturdays with an about 5% higher no show rate**.
5. The **no show rate tends to go up as patients waiting time till the appointment goes up**. The no show rate is less than 10% for those who schedule the appointment for the same day, it increases to about 25% for those who wait 1-9 days and increses again to about 30% for those who wait 10 days more.
6. Patients who are in the **welfare program** do not have greater responsability with showing up to their appointments, with an almost **5% higher no show rate**
7. Having a disease affects if people are going to show up, as the **no show rate decreases for almost all the groups with diseases, unless for those who are in the welfare program and suffer from alcoholism.**
