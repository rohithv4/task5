# task5
: Exploratory Data Analysis (EDA)
Here's a detailed plan and a basic template to Exploratory Data Analysis (EDA) using Python with Pandas, Matplotlib, and Seaborn.
![task5 1](https://github.com/user-attachments/assets/2ec97665-36d8-4cab-8f7a-72b0c1be3da0)
![task5 2](https://github.com/user-attachments/assets/f4c87477-2f13-4fc1-a24b-72baef15695c)
![task5 3](https://github.com/user-attachments/assets/eaee6d32-c3e3-41d2-89f2-6200c2955fbc)
![task5 4](https://github.com/user-attachments/assets/50ed43ac-deda-4989-a20d-8acbb516b461)
![task5 5](https://github.com/user-attachments/assets/fff82a19-245f-4b91-89ab-d04857c354bc)
![task5 6](https://github.com/user-attachments/assets/2bb3a79d-069d-4a07-b16b-23c560bf44fd)
![task5 7](https://github.com/user-attachments/assets/b4065bda-ad9b-4592-ae18-64a0876128ed)
![task5 8](https://github.com/user-attachments/assets/dd3703e6-f6b4-4eb4-a934-33b63254fbf9)
![task5 9](https://github.com/user-attachments/assets/48e140a1-0e33-4cd7-a635-3d7b013d33e6)
![task5 10](https://github.com/user-attachments/assets/1110aed4-8dec-4beb-aa75-e16c94a80ab4)
![task5 11](https://github.com/user-attachments/assets/667ffe0a-b679-402e-8829-e1ad14e29f13)
![task5 12](https://github.com/user-attachments/assets/f0547b3b-831b-4dcf-af59-e410b6c79aab)
![task5 13](https://github.com/user-attachments/assets/446beefb-6fb0-46c0-be7c-dd103f736d51)
✅ Key Trends Observed:
- Females survived at much higher rates than males.
- 1st class passengers had highest survival rates.
- Higher fares correlated with higher survival.
- Children had a slightly better chance of survival.
- Passengers from Cherbourg (Embarked='C') had better survival.
- Small family sizes had a slight advantage.


 Here are observations for each plot from the previous histograms, boxplots, and scatterplots — plus a clear summary of findings you can add to your report.
 ![task5 14](https://github.com/user-attachments/assets/1b3b9052-5eab-42f0-94f7-827b1146b6a5)
 ![task5 15](https://github.com/user-attachments/assets/df3f715d-b1fd-46ee-94c0-b066dd9f6d9c)
 ![task5 16](https://github.com/user-attachments/assets/fd80f820-b84e-43d7-8968-e867d4b41a05)
![task5 17](https://github.com/user-attachments/assets/a44e7644-caba-4a0b-afd9-5c44eae369ad)
![task5 18](https://github.com/user-attachments/assets/7771cff0-3647-43e6-b191-8f82d544a725)
 ![task5 19](https://github.com/user-attachments/assets/ce780a2a-758d-480d-9c22-029b7f55bd96)


  Observations for Each Plot
1. Histogram of Passenger Ages
The age distribution is roughly right-skewed with most passengers between 20 and 40 years.

There is a noticeable peak in the child age group (0-10 years).

Missing age values were filled with median, so distribution is reasonably smooth.

2. Histogram of Fare Paid
Fare distribution is heavily right-skewed with many paying low fares.

A few passengers paid very high fares (outliers).

Higher fares are associated with wealthier passengers, mainly in 1st class.

3. Boxplot of Fare by Passenger Class
Median fare decreases from 1st class (highest) to 3rd class (lowest).

Fare ranges and variability are highest in 1st class.

3rd class fares are concentrated at lower values with fewer outliers.

4. Boxplot of Age by Survival
Survivors tend to be younger on average than non-survivors.

Children and younger adults had better survival chances.

Some older passengers survived, but median age for non-survivors is higher.

5. Scatterplot of Age vs Fare (colored by Survival)
Survivors (usually in blue/red depending on palette) cluster at higher fare and younger ages.

Many non-survivors paid lower fares and are spread across ages.

Shows how socioeconomic status (fare) and age both influenced survival.

6. Scatterplot of SibSp vs Parch (colored by Survival)
Family members aboard (siblings/spouses vs parents/children) vary widely.

Survivors are scattered across small family sizes; large families had mixed outcomes.

Suggests small to medium family groups had some survival advantage.

📝 Summary of Findings
Age and Survival: Younger passengers, especially children, had higher survival rates.

Fare and Survival: Higher fare passengers (likely 1st and 2nd class) had better chances to survive.

Passenger Class: 1st class passengers paid more and survived more often than 3rd class.

Family Size: Small families or traveling alone showed mixed survival, with slight advantage to smaller groups.

Gender (from earlier analyses): Females survived significantly more than males.

Overall: Survival was influenced by a combination of age, socioeconomic status (fare and class), family size, and gender.


















