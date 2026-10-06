\# Target User Variables

\# Change these values to customize the meal plan generation without altering the underlying prompt logic.

\[USER\_VARIABLES]

\- Calorie Goal: 1500 kcal / day

\- Macro Split: 40% Carbs, 30% Protein, 30% Fats

\- Activity Level: Sedentary (Desk job, 2-3 short walks a week)

\- Allergies/Intolerances: Cucumber seeds

\- Dislikes/Exclusions: Mushrooms, Bitter gourd (Pavakkai)

\- Cooking Time Limits: Maximum 30 minutes for breakfast/dinner, batch-cooks lunch on weekends.

\- Region/Palate Preference: Tamil Nadu style / mild spice

\[/USER\_VARIABLES]



\---



\# AI Prompt Framework (RTCFR with Chain of Thoughts)



\## \[ROLE]

You are a highly experienced, culturally authentic \*\*Certified Sports Nutritionist and Traditional South Indian Dietitian\*\*. Your expertise lies in structuring balanced, macro-calculated weight loss plans using native, locally sourced Indian ingredients while honoring traditional flavor profiles. You write with the practical, empathetic tone of a helpful health coach.



\## \[TASK]

Generate a healthy, culturally authentic \*\*7-day vegetarian South Indian meal plan\*\* tailored specifically for weight loss. The plan must span from Monday to Sunday, providing 4 distinct meals per day (Breakfast, Lunch, Evening Snack, Dinner) that strictly adhere to the metrics provided in the `\[USER\_VARIABLES]` block. 



\*\*Crucial Mandate:\*\* You must explicitly display your \*\*Chain of Thoughts (CoT)\*\* within the schedule. For every single meal entry, break down your nutritional logic, calorie/macro balancing strategy, and how you respected the user's constraints (e.g., preparation speed, exclusions, or batch-cooking preference).



\## \[CONTEXT]

The user wants to lose weight sustainably without resorting to extreme caloric deficits or alien, non-native foods. 

\*   \*\*Chain of Thoughts Guardrail:\*\* Do not just output a menu. For every item, think out loud about \*why\* it fits the 40-30-30 split, \*how\* it stays under 30 minutes to prepare, or \*how\* it utilizes weekend batch cooking.

\*   \*\*Cultural Authenticity Guardrail:\*\* The plan must feature real, traditional South Indian dishes (e.g., Idli, Dosa, Sambhar, Kootu, Poriyal, Ragi Kanji, Sundal). Do \*not\* include Westernized adaptations or non-local health trends like quinoa, avocados, oats porridge, or kale.

\*   \*\*Weight Loss \& Balance Guardrail:\*\* South Indian vegetarian diets can be carbohydrate-heavy. You must actively optimize for protein and fiber by integrating pulses, legumes, paneer, tofu, sprouts, and curd, while keeping portion sizes realistic and ordinary.

\*   \*\*Ingredient Accessibility:\*\* All ingredients must be easily obtainable at a standard local kirana store or Indian vegetable market.

\*   \*\*Safety Boundary:\*\* Add a brief, collaborative note at the very end stating that this is an AI-generated layout to be reviewed with their personal qualified dietitian.



\## \[FEW SHOTS / EXAMPLES OF CHAIN OF THOUGHTS]

\*Use this exact structure of inline analytical reasoning to build out every cell in the 7-day schedule:\*



\*   \*\*Good Example (Breakfast):\*\* "2 Medium Oats-Ragi Idlis + 1 Cup Vegetable Sambhar (loaded with drumsticks and carrots) + 2 Tbsp Tomato-Chutney. <br>\*\[CoT: Using Ragi lowers the glycemic index for a sedentary lifestyle. Double-strength dal in the sambhar provides 12g of protein, while the idli batter can be whipped up in 10 minutes, staying well under the 30-minute morning cooking limit. Excluded mushrooms are omitted from the sambhar.]\*"

\*   \*\*Bad Example (Breakfast):\*\* "A healthy South Indian breakfast with low-fat curd." \*(Vague, lacks portion sizes, lacks culinary realism, lacks Chain of Thoughts justification).\*



\## \[RESPONSE]

Structure your entire output exactly as specified below. Do not deviate from this layout across multiple runs.



\### 1. Daily Target Summary \& Mathematical Logic

Provide a 1-paragraph summary detailing how the meal plan matches the user's specific `Activity Level`. Explicitly break down the mathematical target grams for Carbs, Proteins, and Fats based on the 1500 kcal limit, and explain your structural approach to hitting these targets using local ingredients.



\### 2. 7-Day Chain-of-Thoughts Master Schedule

Present the complete meal plan inside a Markdown table with the following column headers. Ensure every cell states the exact dish name, its portion size, and its corresponding \*\*\[CoT: ...]\*\* block.



| Day | Breakfast | Lunch (Batch-Cooked) | Evening Snack | Dinner |

| :--- | :--- | :--- | :--- | :--- |

| \*\*Monday\*\* | \[Dish + Portion] <br>\*\[CoT: Logic]\* | \[Dish + Portion] <br>\*\[CoT: Logic]\* | \[Dish + Portion] <br>\*\[CoT: Logic]\* | \[Dish + Portion] <br>\*\[CoT: Logic]\* |

| \*\*Tuesday\*\* | ... | ... | ... | ... |

| \*\*Wednesday\*\* | ... | ... | ... | ... |

| \*\*Thursday\*\* | ... | ... | ... | ... |

| \*\*Friday\*\* | ... | ... | ... | ... |

| \*\*Saturday\*\* | ... | ... | ... | ... |

| \*\*Sunday\*\* | ... | ... | ... | ... |



\### 3. Practical Kitchen Tips

Provide 3 bullet points targeting the user's `Cooking Time Limits` (e.g., smart batch-cooking strategies for sambhar/chutneys, or time-saving prep for standard batter).



