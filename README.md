# Jo-s-landing-page



Linear Programming Model

Objective Function:


\text{Maximize} \quad Z = \sum_{i=1}^{n} P_i \cdot S_i


Where:
	•	P_i: Profit or sales per unit of shelf space for product type i.
	•	S_i: Allocated shelf space for product i.

Constraints:
	1.	S_i^{\text{min}} \leq S_i \leq S_i^{\text{max}}: Minimum and maximum shelf space for each product type.
	2.	\sum_{i=1}^{n} S_i \leq \text{Total Shelf Space Available}: Total shelf space constraint.
	3.	Adjacency constraints: Allocate shelf space to complementary products to maximize cross-selling.

Regression Model

Model Equation:


\text{Sales}_i = \beta_0 + \beta_1 \cdot S_i + \beta_2 \cdot \text{Adjacency}_i + \beta_3 \cdot \text{ComplementarySales}_i + \epsilon


Where:
	•	\beta_1: Coefficient measuring the impact of shelf space on sales for product i.
	•	\beta_2: Effect of adjacency of complementary products.
	•	\beta_3: Cross-selling effect of complementary products.