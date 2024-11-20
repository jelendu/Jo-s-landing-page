# Jo-s-landing-page


Linear Programming Model

Objective Function:

Maximize Z = Σ (P_i * S_i)

Where:
	•	P_i: Profit or sales per unit of shelf space for product type i.
	•	S_i: Allocated shelf space for product i.

Constraints:
	1.	S_i_min <= S_i <= S_i_max (Minimum and maximum shelf space for each product type).
	2.	Σ S_i <= Total Shelf Space Available (Total shelf space constraint).
	3.	Adjacency constraints for complementary products to leverage cross-selling.

Regression Model

Model Equation:

Sales_i = β_0 + β_1 * S_i + β_2 * Adjacency_i + β_3 * ComplementarySales_i + ε

Where:
	•	β_1: Coefficient measuring the impact of shelf space on sales for product i.
	•	β_2: Effect of adjacency of complementary products.
	•	β_3: Cross-selling effect of complementary products.


