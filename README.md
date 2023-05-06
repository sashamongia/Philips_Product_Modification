# Philips_Product_Modification

The dataset for this project was obtained from a commercial conjoint analysis study on coffee makers for the electronics manufacturer Philips (www.Philips.com). The purpose of the study was to identify the importance of product attributes to consumers and to design a new coffee maker for Philips. The five product attributes used in the study and their levels are listed in the table below. These attributes were selected on the basis of extensive discussions with Philips product managers, pretests, and in-depth interviews with consumers. 

There were five major products in the coffee maker market currently. For the sake of this project, we assume that they are the only existing products in the marketplace.

1.	Krups, 5 cups, $59, without a water filter, without an auto-grinder; 
2.	Krups, 10 cups, $79, without a water filter, without an auto-grinder;
3.	Cuisinart, 10 cups, $99, without a water filter, with an auto-grinder; 
4.	Cuisinart, 15 cups, $79, without a water filter, without an auto-grinder;
5.	Philips, 10 cups, $79, without a water filter, without an auto-grinder.

Philips was interested in finding out whether adding a water filter and/or an auto-grinder would increase its market share.

Study Design

Using the five product attributes and their levels as listed in Table 1, 16 product profiles were constructed based on a fractional factorial design. These profiles were divided into eight blocks, each of which consisted of three alternatives (an alternative is a unique product profile). Respondents were divided into two groups, and each group received different choice sets based on the same 16 product profiles. Each respondent had to choose an alternative from a choice set of three product profiles, and to repeat the same choice task in a total of eight choice sets. A common product profile (“Philips, 5 cups, $79, with a water filter, without an auto-grinder”) was included as alternative #3 in all choice sets. This was to ensure that the choice probabilities from each choice set are compared, as they were all anchored against a common benchmark. There are 185 respondents in the data, and each of them made choice decisions in eight choice sets, resulting in a total of 1480 observations in the data. Effect coding method was used for the product attribute level dummy variables. Details of the data are provided in the next section.

Table 2. Variable Definitions
Column	Variable Name	Variable Definition
1	Respondent	ID number for the respondent (1 – 185)
2	Choice_Set	ID number for the choice set (1 – 8)
3	Choice	The chosen alternative in a choice set (1, 2, or 3)
4	Philips-1	The “Philips” dummy variable for alternative 1 
(1 = Philips; -1 = Cuisinart; 0 = Krups)  
5	Krups-1	The “Krups” dummy variable for alternative 1
(1 = Krups; -1 = Cuisinart; 0 = Philips)  
6	Capacity5-1	The “Capacity5” dummy variable for alternative 1
(1 = 5 cups; -1 = 15 cups; 0 = 10 cups)
7	Capacity10-1	The “Capacity10” dummy variable for alternative 1
(1 = 10 cups; -1 = 15 cups; 0 = 5 cups)
8	Price59-1	The “Price59” dummy variable for alternative 1
(1 = $59; -1 = $99; 0 = $79)
9	Price79-1	The “Price79” dummy variable for alternative 1
(1 = $79; -1 = $99; 0 = $59)
10	Filter-1	The “Filter” dummy variable for alternative 1
(1 = with a water filter; -1 = without a water filter)
11	Grinder-1	The “Grinder” dummy variable for alternative 1
(1 = with an auto-grinder; -1 = without an auto-grinder)
12	Philips-2	The “Philips” dummy variable for alternative 2 
(1 = Philips; -1 = Cuisinart; 0 = Krups)  
13	Krups-2	The “Krups” dummy variable for alternative 2
(1 = Krups; -1 = Cuisinart; 0 = Philips)  
14	Capacity5-2	The “Capacity5” dummy variable for alternative 2
(1 = 5 cups; -1 = 15 cups; 0 = 10 cups)
15	Capacity10-2	The “Capacity10” dummy variable for alternative 2
(1 = 10 cups; -1 = 15 cups; 0 = 5 cups)
16	Price59-2	The “Price59” dummy variable for alternative 2
(1 = $59; -1 = $99; 0 = $79)
17	Price79-2	The “Price79” dummy variable for alternative 2
(1 = $79; -1 = $99; 0 = $59)
18	Filter-2	The “Filter” dummy variable for alternative 2
(1 = with a water filter; -1 = without a water filter)
19	Grinder-2	The “Grinder” dummy variable for alternative 2
(1 = with an auto-grinder; -1 = without an auto-grinder)
20	Philips-3	The “Philips” dummy variable for alternative 3 
(1 = Philips; -1 = Cuisinart; 0 = Krups)  
21	Krups-3	The “Krups” dummy variable for alternative 3
(1 = Krups; -1 = Cuisinart; 0 = Philips)  
22	Capacity5-3	The “Capacity5” dummy variable for alternative 3
(1 = 5 cups; -1 = 15 cups; 0 = 10 cups)
23	Capacity10-3	The “Capacity10” dummy variable for alternative 3
(1 = 10 cups; -1 = 15 cups; 0 = 5 cups)
24	Price59-3	The “Price59” dummy variable for alternative 3
(1 = $59; -1 = $99; 0 = $79)
25	Price79-3	The “Price79” dummy variable for alternative 3
(1 = $79; -1 = $99; 0 = $59)
26	Filter-3	The “Filter” dummy variable for alternative 3
(1 = with a water filter; -1 = without a water filter)
27	Grinder-3	The “Grinder” dummy variable for alternative 3
(1 = with an auto-grinder; -1 = without an auto-grinder)

Since the same baseline alternative was used in each choice set, alternative 3 is the always the same in the data: “Philips, 5 cups, $79, with a water filter, without an auto-grinder”. This is reflected in the values of dummy variables #20-27.  

The effect coding method can be illustrated using the brand name dummy variables as an example. There are three brands in the study: Philips, Krups, and Cuisinart. Two dummy variables are used to indicate the brands, “Philips” and “Krups”. With effect coding:

Brand Name	“Philips” Dummy	“Krups” Dummy
Philips	1	0
Krups	0	1
Cuisinart	-1	-1

You can look at the first observation in the data to get a more concrete idea of the meaning of the variables. This observation shows that:
•	Respondent 1 chose alternative 3 in choice set 1. 
•	Alternative 1 was: Philips, 10 cups, $79, with a water filter, without an auto-grinder
•	Alternative 2 was: Krups, 15 cups, $79, with a water filter, with an auto-grinder
•	Alternative 3 was: Philips, 5 cups, $79, with a water filter, without an auto-grinder 


Assignment
Your task is to help Philips analyze consumer preference structures in the coffee maker market, design a new product, and evaluate its market potential and impact on other existing products in the marketplace. Philips is particularly interested in finding out whether adding a water filter and/or an auto-grinder would increase its market share.

You are expected to conduct a market segmentation analysis based on the conjoint study data. In other words, you should estimate mixture multinomial logit models to determine the number of segments, as well as the characteristics of each segment. Note that the segments will differ in terms of the coefficients of the product attribute variables (i.e., part-worths in the terminology of conjoint analysis).    

Your decision recommendations should include but not limited to:
•	Find out whether it is worthwhile for Philips to introduce a coffee maker with water filter and auto-grinder;
•	Determine what is the best new product introduction strategy for Philips;
•	Evaluate the market potential of your recommended new Philips product(s) and the impact on existing products.

Your data analysis and model estimation should address, but may not be limited to, the following issues:

1.	Estimate mixture multinomial logit models of different segment sizes and determine the number of segments in the data.
2.	Based on your analysis, are there different segments of consumers with respect to the importance of the various product attributes? If so, how would you describe the characteristics of each segment? Please pay attention to how important the brand name, carafe capacity, price, water filter, and auto-grinder are to each segment. 
3.	Identify the “optimal” product design for each segment.
4.	Determine the best new product design strategy for Philips and describe your recommended product(s) in terms of the product attribute level dummy variables (i.e., specify the X-values for the new design). 
5.	Predict the market share(s) of your recommended new Philips product(s) as well as those of existing products.
