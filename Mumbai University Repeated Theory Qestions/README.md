# Repeated University Questions

## Describe types of attributes in Data mining.

1. Nominal Attributes: 

	a. The values of a nominal attribute are symbols or names of things.

	b. Each value represents some kind of category, code, or state, and so nominal attributes are also referred to as categorical. 

	c. In computer science, the values are also known as enumerations.

	d. That is, mathematical operations on values of nominal attributes are not meaningful

	e. Example: Hair color and Marital Status 

2. Binary Attributes

	a. only two categories or states: 0 or 1, where 0 typically means that the attribute is absent, and 1 means that it is present.

	b. The attribute medical test is binary, where a value of 1 means the result of the test for the patient is positive, while 0 means the result is negative.

3. Ordinal Attributes

	a. Values that have a meaningful order or ranking among them, but the magnitude between successive values is not known

	b. Ordinal attributes are useful for registering subjective assessments of qualities that cannot be measured objectively; thus ordinal attributes are often used in surveys for ratings

	c. Customer satisfaction had the following ordinal categories: 
		0: very dissatisfied, 1: somewhat dissatisfied, 2: neutral, 3: satisfied, and 4: very satisfied

	d. The central tendency of an ordinal attribute can be represented by its mode and its median (the middle value in an ordered sequence), but the mean cannot be defined

4. Numeric Attributes

	a. A numeric attribute is quantitative; that is, it is a measurable quantity, represented in
	integer or real values.

	b. Numeric attributes can be interval-scaled or ratio-scaled.

	c. Interval-scaled attributes are measured on a scale of equal-size units. The values of interval-scaled attributes have order and can be positive, 0, or negative.

	d. A temperature attribute is interval-scaled

	e. A ratio-scaled attribute is a numeric attribute with an inherent zero-point. That is, if a measurement is ratio-scaled, we can speak of a value as being a multiple (or ratio) of another value

	f. count attributes such as years of experience (e.g., the objects are employees) and number of words (e.g., the objects are documents).


## Different distance measures to compute distance between clusters.

1. The choice of distance measures is a critical step in clustering. It defines how the similarity of two elements (x, y) is calculated and it will influence the shape of the clusters.

2. Euclidean distance: It is just a distance measure between a pair of samples p and q in an n-dimensional feature space. 

3. Euclidean distance: d(i, j) = sqrt((xi1 − xj1 )^2 + (xi2 − xj2 )^2)

4. Manhattan (or city block) distance, named so because it is the distance in blocks between any two points in a city (such as 2 blocks down and 3 blocks over for a total of 5 blocks). 
5. It is defined as d(i, j) = |xi1 − xj1 | + |xi2 − xj2 |

6. Other dissimilarity measures exist such as correlation-based distances, which is widely used for gene expression data analyses. Correlation-based distance is defined by subtracting the correlation coefficient from 1. 

7.  Different types of correlation methods can be used such as:
	
	a. Pearson correlation distance: Pearson correlation measures the degree of a linear relationship between two profiles.

	b. Eisen cosine correlation distance: It’s a special case of Pearson’s correlation with x¯ and y¯ both replaced by zero:

	c. Spearman correlation distance: The spearman correlation method computes the correlation between the rank of x and the rank of y variables.

	d. Kendall correlation distance: The spearman correlation method computes the correlation between the rank of x and the rank of y variables.







