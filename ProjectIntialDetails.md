Team Project (Team 9)


Title: Budget Meal Planner (JustEat)
Topic: Human Services

Purpose: 
To provide an app that can list down all possible food options in accordance to the user’s dietary restrictions, food preference type and budget constraints. Additionally, the app can provide nutritional value and recipes. 

Problem Statement and Target Users 

In the current market of meal planning apps, the vast majority of them only plan out different varieties of food, track nutritional value and give recipes. This can lead to overspending, repetitive meals, or meals that do not meet the user's dietary needs. Our app aims to integrate AI to balance these factors and recommend suitable meals within the user’s budget.

The target users for our app are individuals who want to plan their meals while managing their food expenses and may have dietary requirements. This includes families, students, young adults and working individuals who may have a limited budget but still want meals that fit their dietary needs. By allowing users to personally add their dietary requirements, budget and food preference, the app can generate personalized meal plans that are both affordable and suitable to their needs.
	

User Inputs 
Dietary requirement, food preference, budget, pax per meal

Use of AI 
AI will generate personalised meal recommendations by analysing user dietary needs, budget constraints, and food preferences. For each meal plan request, the AI will return structured data including meal options, estimated costs and nutritional breakdowns. The AI will rank options by combining cost, nutrition, and preferences.

Input: pax per meal, name, dietary restriction, country, food preference, calorie setting, food allergies
Output: 

Business Rules
Dietary Filter: Enforces exclusion rules for dietary restriction
Budget Caps: Total cost cannot exceed user’s budge
Meal Acceptance Rule:
IF (cost_per_serving ≤ user_budget) AND (dietary_flags match restrictions) AND (food_type == user_food_preference) THEN accept as primary recommendation
Budget Alert Rule:
IF (planned_week_cost + new_meal_cost > weekly_budget) THEN flag as "over budget" and offer cheaper alternatives
Nutritional Recommendation Rule:
IF (week_nutrition_summary shows deficiency in protein) THEN recommend high-protein meals
Allergy rule
Meals that contain ingredients identified as allergens by users must be excluded regardless of AI’s recommendation.

Github Link
https://github.com/nrjbms/INF1103-Team-Project 

