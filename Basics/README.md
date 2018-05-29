# Basic Knowledge About Data Mining Is Important

## What is Data Mining? (Explained Like I'm 5)
Looking for patterns in large amounts of data. The process of extracting information and knowledge from data is what data mining is. Data mining is digging though tons of random looking data looking for the pieces of information that is worth anything. Essentially, going through raw data and finding trends within.

## What is Knowledge Discovery from Data? (KDD)
Process of discovering useful knowledge from a collection of data. The knowledge discovery process is as an iterative sequence of the following steps:

	1. Data cleaning: Remove noise and inconsistent data

	2. Data integration: Multiple data sources may be combined
	
	3. Data selection: Data relevant to the analysis are retrieved from the database
	
	4. Data transformation: Data are transformed and consolidated into forms appropriate
	by performing summary or aggregation operations
	
	5. Data mining: Intelligent methods are applied to extract data patterns
	
	6. Pattern evaluation: Identify the truly interesting patterns representing knowledge based interestingness measures
	
	7. Knowledge presentation: Visualization and knowledge representation techniques are used to resent mined knowledge to users

## What Kinds of Data Can Be Mined?
	
	1. Database data: tables and stuffs

	2. Data Warehouse

	3. Transactional Data: such as a customer’s purchase, a flight booking, or a user’s clicks on web page


## What is Machine Learning?
Machine Learning is a form of Artificial Intelligence in which the program is designed to learn on its own. Machine Learning is a way of programming a computer to learn to do a task on its own, rather than you having to implicitly tell it how to accomplish the task. Machine learning investigates how computers can learn (or improve their performance) based on data. 

## Major Issues in Data Mining
### Mining Methodology
	1. Mining various and new kinds of knowledge: Due to the diversity of applications, new mining tasks continue to emerge, making data mining a dynamic and fast-growing field

	2. Mining knowledge in multidimensional space: n many cases, data can be aggregated or viewed as a multidimensional data cube. Mining knowledge in cube space can substantially enhance the power and flexibility of data mining. 

	3. Data mining

	4. Handling uncertainty, noise, or incompleteness of data

### User Interaction
	
	1. Interactive mining: Build flexible user interfaces and an exploratory mining environment, facilitating the user’s interaction with the system

	2. Incorporation of background knowledge

	3. Ad hoc data mining and data mining query languages

	4. Presentation and visualization of data mining results

### Efficiency and Scalability

	1. Efficiency and scalability of data mining algorithms

	2. Parallel, distributed, and incremental mining algorithms

### Diversity of Database Types

	1. Handling complex types of data

	2. Mining dynamic, networked, and global data repositories

### Data Mining and Society
	
	1. Social impacts of data mining: The improper disclosure or use of data and the potential violation of individual privacy and data protection rights are areas of concern that need to be addressed.

	2. Privacy-preserving data mining: The philosophy is to observe data sensitivity and preserve people’s privacy while performing successful data mining.

	3. Invisible data mining: For example, when purchasing items online, users may be unaware that the store is likely collecting data on the buying patterns of its customers, which may be used to recommend other items for purchase in the future.

## Type of Data Attributes

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

## Mean

	1. The most common and effective numeric measure of the “center” of a set of data

	2. A major problem with the mean is its sensitivity to extreme (e.g., outlier) values

	3. To offset the effect caused by a small number of extreme values, we can instead use the trimmed mean, which is the mean obtained after chopping off values at the high and low extremes.

## Median 

	1. Middle value in a set of ordered data values

	2. The median is expensive to compute when we have a large number of observations.

## Mode

	1. The mode for a set of data is the value that occurs most frequently in the set

	2. Data sets with one, two, or three modes are respectively called unimodal, bimodal, and trimodal.

## Range, Quartiles, and Interquartile Range

	1. The range of the set is the difference between the largest (max()) and smallest (min()) values.

	2. Quantiles are points taken at regular intervals of a data distribution, dividing it into essentially equal size consecutive sets.

	3. The 4-quantiles are the three data points that split the data distribution into four equal parts; each part represents one-fourth of the data distribution. They are more commonly referred to as quartiles.

	4. The quartiles give an indication of a distribution’s center, spread, and shape. 

	5. The first quartile, denoted by Q1, is the 25th percentile. It cuts off the lowest 25% of the data. The third quartile, denoted by Q3, is the 75th percentile. It cuts off the lowest 75% (or highest 25%) of the data. The second quartile is the 50th percentile. As the median, it gives the center of the data distribution.

	6. The distance between the first and third quartiles is a simple measure of spread that gives the range covered by the middle half of the data. This distance is called the interquartile range (IQR)

## Five-Number Summary, Boxplots, and Outliers
	
	1. The five-number summary of a distribution consists of the median (Q 2 ), the quartiles Q 1 and Q 3 , and the smallest and largest individual observations, written in the order of Minimum, Q 1 , Median, Q 3 , Maximum.

	2. Boxplots are a popular way of visualizing a distribution. 

	3. A boxplot incorporates the five-number summary as follows:

		a. The ends of the box are at the quartiles so that the box length is the interquartile range.

		b. The median is marked by a line within the box

		c. Two lines (called whiskers) outside the box extend to the smallest (Minimum) and largest (Maximum) observations.

	4. Variance and standard deviation are measures of data dispersion.

	5. A low standard deviation means that the data observations tend to be very close to the mean, while a high standard deviation indicates that the data are spread out over a large range of values.

	6. The standard deviation, σ , of the observations is the square root of the variance



