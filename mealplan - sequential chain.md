\# SEQUENTIAL CHAIN PROMPT

\## 7-Day South Indian Vegetarian Weight-Loss Meal Plan



\---



\# CHAIN 0 — USER VARIABLES



Read and lock the following variables before generating anything.



\[USER\_VARIABLES]



\- Calorie Goal: 1500 kcal / day

\- Macro Split: 40% Carbs, 30% Protein, 30% Fats

\- Activity Level: Sedentary (Desk job, 2-3 short walks a week)

\- Allergies/Intolerances: Cucumber seeds

\- Dislikes/Exclusions: Mushrooms, Bitter gourd (Pavakkai)

\- Cooking Time Limits: Maximum 30 minutes for breakfast/dinner, batch-cooks lunch on weekends

\- Region/Palate Preference: Tamil Nadu style / mild spice



\[/USER\_VARIABLES]



\### Instruction



Treat these variables as hard constraints.



Do not modify, reinterpret, or silently ignore them.



If any later chain step conflicts with these variables, return to this section and correct the conflict before proceeding.



\---



\# CHAIN 1 — CALCULATE DAILY NUTRITION TARGETS



Calculate the approximate daily nutritional targets from the supplied calorie goal and macro split.



For a 1500 kcal target:



\- Carbohydrates = 40%

\- Protein = 30%

\- Fat = 30%



Convert the percentages into approximate grams per day using:



\- Carbohydrates = 4 kcal/g

\- Protein = 4 kcal/g

\- Fat = 9 kcal/g



Calculate:



1\. Daily calories

2\. Daily carbohydrate grams

3\. Daily protein grams

4\. Daily fat grams



Then establish reasonable approximate targets for:



\- Breakfast

\- Lunch

\- Evening snack

\- Dinner



Do not force every individual meal to match an exact macro target.



The DAILY TOTAL is the primary target.



\---



\# CHAIN 2 — BUILD THE FOOD CONSTRAINT MATRIX



Before designing meals, create an internal constraint matrix.



\## Mandatory Food Characteristics



Prioritize:



\- Traditional Tamil Nadu / South Indian dishes

\- Locally available ingredients

\- Vegetarian foods

\- Pulses

\- Lentils

\- Legumes

\- Paneer

\- Tofu

\- Sprouts

\- Curd

\- Vegetables

\- Traditional chutneys

\- Sambar

\- Kootu

\- Poriyal

\- Sundal

\- Idli

\- Dosa

\- Adai

\- Ragi-based dishes



\## Avoid



\- Mushrooms

\- Bitter gourd / Pavakkai

\- Cucumber seeds

\- Quinoa

\- Avocado

\- Kale

\- Westernized diet foods

\- Unnecessary imported ingredients

\- Extreme low-carbohydrate approaches



Unless specifically requested by the user, do not introduce foods outside the intended cultural framework.



\---



\# CHAIN 3 — CREATE THE MEAL ARCHITECTURE



Before creating the 7-day table, define the structure of each day.



Each day must contain exactly:



1\. Breakfast

2\. Lunch

3\. Evening Snack

4\. Dinner



Every meal must contain:



\- Exact dish name

\- Practical portion size

\- Appropriate protein source where required

\- Appropriate vegetable/fiber source where practical



Avoid repeating the exact same complete meal unnecessarily.



Some ingredients may repeat intentionally for practicality and batch cooking.



\---



\# CHAIN 4 — DESIGN BREAKFASTS



Generate 7 breakfasts.



Requirements:



\- Tamil Nadu / South Indian style

\- Mild spice

\- Practical preparation

\- Maximum 30 minutes

\- Appropriate portion control

\- Include protein wherever practical

\- Avoid excessive dependence on rice-based foods



Examples may include:



\- Idli

\- Ragi idli

\- Dosa

\- Ragi dosa

\- Adai

\- Pesarattu

\- Vegetable uthappam

\- Ragi vegetable upma



Do not use vague descriptions.



Bad:



"Healthy South Indian breakfast"



Good:



"2 medium ragi dosas + 1 cup vegetable sambar + 100 g curd"



\---



\# CHAIN 5 — DESIGN LUNCHES



Generate 7 lunches.



Lunch should be suitable for weekend batch cooking.



Each lunch should generally contain:



\- Controlled rice portion

\- Dal / sambar / kootu

\- Vegetable poriyal or equivalent

\- Protein-rich vegetarian component

\- Curd where appropriate



Prioritize dishes that can be prepared in batches.



Avoid creating lunches that require several separate fresh preparations every day.



\---



\# CHAIN 6 — DESIGN EVENING SNACKS



Generate 7 evening snacks.



Prioritize:



\- Sundal

\- Sprouts

\- Curd

\- Buttermilk

\- Fruit

\- Small quantities of nuts



Avoid:



\- Deep-fried snacks

\- Sugary beverages

\- Bakery snacks

\- Highly processed foods



Snack portions must support the 1500 kcal daily target.



\---



\# CHAIN 7 — DESIGN DINNERS



Generate 7 dinners.



Requirements:



\- Maximum 30-minute preparation

\- Moderate carbohydrate portions

\- Good protein contribution

\- Vegetables where practical

\- Traditional South Indian profile

\- Mild spice



Dinner should not simply duplicate lunch.



\---



\# CHAIN 8 — PRELIMINARY MACRO CHECK



After generating all 28 meals, estimate:



\- Calories

\- Carbohydrates

\- Protein

\- Fat



for each day.



Create an internal validation table:



| Day | Calories | Carbs | Protein | Fat | Status |

|---|---:|---:|---:|---:|---|

| Monday | \~ | \~ | \~ | \~ | PASS/ADJUST |

| Tuesday | \~ | \~ | \~ | \~ | PASS/ADJUST |

| Wednesday | \~ | \~ | \~ | \~ | PASS/ADJUST |

| Thursday | \~ | \~ | \~ | \~ | PASS/ADJUST |

| Friday | \~ | \~ | \~ | \~ | PASS/ADJUST |

| Saturday | \~ | \~ | \~ | \~ | PASS/ADJUST |

| Sunday | \~ | \~ | \~ | \~ | PASS/ADJUST |



\### Validation Rules



Target:



\- Calories ≈ 1500 kcal/day

\- Carbohydrates ≈ 40%

\- Protein ≈ 30%

\- Fat ≈ 30%



Use reasonable tolerance rather than pretending that household Indian-food portions have laboratory-level precision.



If a day is significantly outside the target:



1\. Identify the meal causing the imbalance.

2\. Adjust the portion or food.

3\. Recalculate.

4\. Repeat until the day is reasonably aligned.



Do not show the uncorrected version.



\---



\# CHAIN 9 — CONSTRAINT VALIDATION



Perform a final automated-style check.



Check every day for:



\### Nutrition

\- \[ ] Approximately 1500 kcal

\- \[ ] Reasonable macro balance

\- \[ ] Adequate vegetarian protein sources

\- \[ ] Adequate vegetables/fiber



\### Cultural

\- \[ ] Tamil Nadu / South Indian style

\- \[ ] Mild spice

\- \[ ] Locally available ingredients



\### Exclusions

\- \[ ] No mushrooms

\- \[ ] No bitter gourd / Pavakkai

\- \[ ] No cucumber seeds



\### Practicality

\- \[ ] Breakfast ≤30 minutes

\- \[ ] Dinner ≤30 minutes

\- \[ ] Lunch suitable for weekend batch cooking

\- \[ ] Ingredients realistically available from a normal Indian market/kirana



If any condition fails, revise the affected meal before continuing.



\---



\# CHAIN 10 — VARIETY CHECK



Check the 7-day plan for excessive repetition.



Do not eliminate useful ingredient repetition solely for the sake of variety.



Prefer:



\- Different preparations of similar ingredients

\- Different pulses

\- Different vegetables

\- Different breakfast formats

\- Different protein sources



Maintain practical shopping and cooking requirements.



\---



\# CHAIN 11 — PRACTICAL KITCHEN OPTIMIZATION



Create exactly 3 practical kitchen tips.



Focus specifically on:



1\. Weekend batch cooking

2\. Batter / chutney / dal preparation

3\. Lunch portioning and storage



Tips should reduce weekday preparation time without compromising the meal structure.



\---



\# CHAIN 12 — FINAL OUTPUT GENERATION



Only after completing all previous chains, produce the final answer.



Do NOT expose the chain-of-thought or internal calculations.



Output exactly the following sections:



\## 1. Daily Target Summary



Provide one concise paragraph explaining:



\- 1500 kcal target

\- Sedentary activity level

\- Macro strategy

\- How vegetarian protein is being increased

\- How the plan supports sustainable weight management



\## 2. 7-Day Master Schedule



Use exactly this table structure:



| Day | Breakfast | Lunch | Evening Snack | Dinner |

|---|---|---|---|---|

| Monday | Dish + Portion | Dish + Portion | Dish + Portion | Dish + Portion |

| Tuesday | Dish + Portion | Dish + Portion | Dish + Portion | Dish + Portion |

| Wednesday | Dish + Portion | Dish + Portion | Dish + Portion | Dish + Portion |

| Thursday | Dish + Portion | Dish + Portion | Dish + Portion | Dish + Portion |

| Friday | Dish + Portion | Dish + Portion | Dish + Portion | Dish + Portion |

| Saturday | Dish + Portion | Dish + Portion | Dish + Portion | Dish + Portion |

| Sunday | Dish + Portion | Dish + Portion | Dish + Portion | Dish + Portion |



Every cell MUST contain:



\*\*Specific dish + measurable portion\*\*



Never use vague descriptions.



\## 3. Practical Kitchen Tips



Provide exactly 3 bullet points.



\## 4. Safety Note



End with:



"This is an AI-generated meal-plan layout intended for planning purposes. Please review the portions, nutritional suitability, and any individual dietary considerations with your qualified dietitian or healthcare professional."



\---



\# FINAL EXECUTION RULE



The model must follow the chains sequentially:



USER VARIABLES

↓

NUTRITION TARGETS

↓

FOOD CONSTRAINTS

↓

MEAL ARCHITECTURE

↓

BREAKFAST

↓

LUNCH

↓

SNACK

↓

DINNER

↓

MACRO CHECK

↓

CONSTRAINT CHECK

↓

VARIETY CHECK

↓

KITCHEN OPTIMIZATION

↓

FINAL OUTPUT



Do not skip validation.



Do not generate the final 7-day table before completing the internal validation steps.



Do not expose internal chain-of-thought.



The final answer must contain only the requested output sections and the final safety note.

