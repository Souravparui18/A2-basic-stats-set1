# A2-basic-stats-set1
## Topics: Descriptive Statistics and Probability
## Question 1
## Look at the data given below. Plot the data, find the outliers and find out μ,σ,σ^2
Name of company Measure X

Allied Signal 24.23%

Bankers Trust 25.53%

General Mills 25.41%

ITT Industries 24.14%

J.P.Morgan & Co. 29.62%

Lehman Brothers 28.25%

Marriott 25.81%

MCI 24.39%

Merrill Lynch 40.26%

Microsoft 32.95%

Morgan Stanley 91.36%

Sun Microsystems 25.99%

Travelers 39.42%

US Airways 26.71%

Warner-Lambert 35.00%

Ans - By using df.describe() we get Mean = 33.271333 , Standard Deviation = 16.945401 and by df.var() we get Variance = 287.146612 By using boxplot and barplot - the outliers in this data is Morgan Stanley 91.36%.

## Question2
Answer the following three questions based on the box-plot above.
What is inter-quartile range of this dataset? (please approximate the numbers) In one line, explain what this value implies.
Ans: Approximately (First Quantile Range) Q1 = 5, (Third Quantile Range) Q3 = 12, (Inter-Quartile Range) IQR = Q3 – Q1 = 12 – 5 = 7 Second Quartile Range is the Median Value

What can we say about the skewness of this dataset?
Ans- The data is Right-Skewed as it median lies towards the left so it is not an normal distribution.

If it was found that the data point with the value 25 is actually 2.5, how would the new box-plot be affected?
Ans - In the above case there would be no outliers on the given dataset , because of outlier the data had positive skewness so it will reduce and the data will be normally distributed.

## Question3
Answer the following three questions based on the histogram above.
Where would the mode of this dataset lie?
Ans - The mode of the dataset will lie between 5 to 10 or approximately between 4 to 8.

Comment on the skewness of the dataset.
Ans: Right-Skewed as Mean>Median>Mode

Suppose that the above histogram and the box-plot in question 2 are plotted for the same dataset. Explain how these graphs complement each other in providing information about any dataset.
Ans- They both are right-skewed and both have outliers, the median can be easily visualized in box plot, where as in histogram mode is more visible.

## Question4
AT&T was running commercials in 1990 aimed at luring back customers who had switched to one of the other long-distance phone service providers. One such commercial shows a businessman trying to reach Phoenix and mistakenly getting Fiji, where a half-naked native on a beach responds incomprehensibly in Polynesian. When asked about this advertisement, AT&T admitted that the portrayed incident did not actually take place but added that this was an enactment of something that “could happen.” Suppose that one in 200 long-distance telephone calls is misdirected. What is the probability that at least one in five attempted telephone calls reaches the wrong number? (Assume independence of attempts.)
Ans- If 1 in 200 long-distance calls are getting misdirected then

Probability of call misdirecting = 1/200

Probability of call not misdirecting = 1 - 1/200 = 199/200

The probability for at least one in five attempted telephone calls reaches the wrong number

Number of calls (n) = 5

p = 1/200

q = 199/200

P(x) = At least one in five attempted telephone calls reaches the wrong number

P(x) = ⁿCₓ pˣ qⁿ⁻ˣ

P(x) = (nCx)(p^x)(q^n-x) ) #(nCr = n!/r!*(n - r)!)

P(1) = (5C1) (1/200)^1 (199/200)^5-1

P(1) = 0.0245037

## Question5
Returns on a certain business venture, to the nearest $1,000, are known to follow the following probability distribution
x = P(x)

-2,000 = 0.1

-1,000 = 0.1

0 = 0.2

1,000 = 0.2

2,000 = 0.3

3,000 = 0.1

E(x) = Sum(x.P(x) | E(x^2) =x^2.P(x)

-200 | 400000

-100 | 100000

0 | 0

200 | 200000

600 | 1200000

300 | 900000

Total: 80 | 2800000

### What is the most likely monetary outcome of the business venture?
Ans- The most likely monetary outcome of the business venture is 2000 dollars

The probability for 2000 dollars is 0.3 which is highest as compared to others

### Is the venture likely to be successful? Explain
Ans- : Yes, since the probability that the venture will make more than 0 or a profit is

p(x>1000)+p(x>2000)+p(x=3000) = 0.2+0.3+0.1 = 0.6 , it states that there's a 60% chance for this venture to make a profit.

### What is the long-term average earning of business ventures of this kind? Explain
Ans- The long term average is Expected Value = Sum(x * P(x))

E(x) = -2000x0.1 + -1000x0.1 + 0*0.2 + 1000x0.2 + 2000x0.3 + 3000x0.1 = 800$, So the long term average of business venture will earn an average of around 800 dollars

### What is the good measure of the risk involved in a venture of this kind? Compute this measure
Ans- : The good measure of the risk involved in a venture of this kind depends on the Variability in the distribution. Higher Variance means more chances of risk

E(x) = Sum(x*P(x))

E(X^2) =x^2*P(x)

Var (x) = E(x^2) –(E(x))^2

Var(x) =2800000 – 800^2

Var(x) =2160000 (Value is quite high)

Std Deviation = √Var ≈ $ 1470 , so there is risk of around 1470 dollars involved in this business venture.
