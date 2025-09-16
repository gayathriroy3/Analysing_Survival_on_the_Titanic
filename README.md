# Analysing_Survival_on_the_Titanic
Analysing Survival on the Titanic

This end-to-end EDA has provided a deep understanding of the Titanic dataset. Our analysis confirms the "women and children first" narrative and highlights the stark social inequalities of the time. Through feature engineering, we've created even more powerful predictors for a potential machine learning model.

Key Findings:

Strongest Predictors of Survival:

Title & Sex: Being female ('Mrs', 'Miss') was the single most significant advantage. Our engineered Title feature captures this nuance better than Sex alone, also showing that young boys ('Master') had a much higher survival rate than adult men ('Mr').
Passenger Class: There was a clear survival hierarchy: 1st > 2nd > 3rd class.
Age: Children and infants had a higher survival rate.
Other Influential Factors:

Family Size: Traveling in a small family (2-4 members) increased survival chances, while traveling alone or in a very large family decreased them.
Fare/Cabin: Having a cabin (and thus paying a higher fare) was strongly correlated with survival, acting as a proxy for wealth and passenger class.
Port of Embarkation: Passengers from Cherbourg ('C') had a higher survival rate, possibly because a higher proportion of them were in 1st class.
