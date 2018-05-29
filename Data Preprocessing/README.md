# Data Preprocessing

# Find examples in the Notebook

## Data Quality

1. Accuracy: The data collection instruments used may be faulty. There may have been human or computer errors occurring at data entry. Users may purposely submit incorrect data values for mandatory fields when they do not wish to submit personal information. Errors in data transmission can also occur. There may be technology limitations such as limited buffer size for coordinating synchronized data transfer and consumption.

2. Completeness: Attributes of interest may not always be available, furthermore, the recording of the data history or modifications may have been overlooked.

3. Consistency

4. Timeliness

5. Believability: Believability reflects how much the data are trusted by users

6. interpretability: How easy the data are understood.
 


## Tasks in Data Preprocessing

1. Data cleaning: Filling in missing values, smoothing noisy data, identifying or removing outliers, and resolving inconsistencies.

2. Data integration: Include data from multiple sources. 

3. Data reduction: Reduced representation of the data set that is much smaller in volume, yet produces the same (or almost the same) analytical results. Data reduction strategies include dimensionality reduction and numerosity reduction. In dimensionality reduction, data encoding schemes are applied so as to obtain a reduced or “compressed” representation of the original data. In numerosity reduction, the data are replaced by alternative, smaller representations using parametric models (e.g., regression or log-linear models) or nonparametric models (e.g., histograms, clusters, sampling, or data aggregation).

4. Data transformation: Normalization, data discretization, and concept hierarchy generation are forms of data transformation.



## Missing Values?

1. Fill in the missing value manually

2. Use a global constant to fill in the missing value

3. Use a measure of central tendency for the attribute (e.g., the mean or median) to fill in the missing value

4. Use the most probable value to fill in the missing value: This may be determined with regression, inference-based tools using a Bayesian formalism, or decision tree induction.


## Noisy Data?

1. Binning: Binning methods smooth a sorted data value by consulting its “neighborhood,” that is, the values around it. Because binning methods consult the neighborhood of values, they perform local smoothing. Similarly, smoothing by bin medians can be employed, in which each bin value is replaced by the bin median. In smoothing by bin boundaries, the minimum and maximum values in a given bin are identified as the bin boundaries.

2. Regression

3. Outlier analysis

## Wavelet Transforms

1. The discrete wavelet transform (DWT) is a linear signal processing technique that,
when applied to a data vector X, transforms it to a numerically different vector, X 0 , of
wavelet coefficients.

2. The usefulness lies in the fact that the wavelet transformed data can be truncated.

3. A compressed approximation of the data can be retained by storing only a small fraction of the strongest of the wavelet coefficients.

4. Given a set of coefficients, an approximation of the original data can be constructed by applying the inverse of the DWT used.

## Principal Components Analysis (PCA)

1. Suppose that the data to be reduced consist of tuples or data vectors described by n attributes or dimensions. 

2. Principal components analysis (PCA; also called the Karhunen-Loeve, or K-L, method) searches for k n-dimensional orthogonal vectors that can best be used to represent the data, where k ≤ n.

3. The original data are thus projected onto a much smaller space, resulting in dimensionality reduction.

4. PCA often reveals relationships that were not previously suspected and thereby allows interpretations that would not ordinarily result.

5. PCA can be applied to ordered and unordered attributes, and can handle sparse data and skewed data

## Attribute Subset Selection

1. Data sets for analysis may contain hundreds of attributes, many of which may be irrelevant to the mining task or redundant

2. Attribute subset selection 4 reduces the data set size by removing irrelevant or redundant attributes

3. The goal of attribute subset selection is to find a minimum set of attributes such that the resulting probability distribution of the data classes is as close as possible to the original distribution obtained using all attributes.

4. Stepwise forward selection: The procedure starts with an empty set of attributes as
the reduced set. The best of the original attributes is determined and added to the reduced set. At each subsequent iteration or step, the best of the remaining original attributes is added to the set.

5. Stepwise backward elimination: The procedure starts with the full set of attributes. At each step, it removes the worst attribute remaining in the set.

6. Combination of forward selection and backward elimination: The stepwise forward selection and backward elimination methods can be combined so that, at each step, the procedure selects the best attribute and removes the worst from among the remaining attributes.

7. Decision tree induction: Decision tree induction constructs a flowchart like structure where each internal (nonleaf) node denotes a test on an attribute, each branch corresponds to an outcome of the test, and each external (leaf) node denotes a class prediction. At each node, the algorithm chooses the “best” attribute to partition the data into individual classe. 

## Sampling

1. Sampling can be used as a data reduction technique because it allows a large data set to be represented by a much smaller random data sample

2. Simple random sample without replacement (SRSWOR) of size s: This is created by drawing s of the N tuples from D (s < N ), where the probability of drawing any tuple in D is 1/N , that is, all tuples are equally likely to be sampled.

3. Simple random sample with replacement (SRSWR) of size s: This is similar to SRSWOR, except that each time a tuple is drawn from D, it is recorded and then replaced. That is, after a tuple is drawn, it is placed back in D so that it may be drawn again.

4. Cluster sample: If the tuples in D are grouped into M mutually disjoint “clusters,” then an SRS of s clusters can be obtained, where s < M

5. Stratified sample: If D is divided into mutually disjoint parts called strata, a stratified sample of D is generated by obtaining an SRS at each stratum.


## Data Transformation by Normalization

To help avoid dependence on the choice of measurement units, the data should be normalized or standardized. This involves transforming the data to fall within a smaller or common range such as [−1, 1] or [0.0, 1.0]. 

### Normalizing the data attempts to give all attributes an equal weight. 

	1. 