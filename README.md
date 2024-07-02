# Classification models and cluster analyzes for the purchase intention of users of e-commerce platforms

Understanding how users' online activities influence their purchase likelihood is crucial for gaining insights into their motivations. Numerous studies in the academic space highlight the global expansion of the Internet contributing to the rise of e-commerce. Online stores are preferred over traditional brick-and-mortar establishments due to their enhanced accessibility, convenience, privacy, and extensive product variety (Schaupp and Belanger, 2005; Vijayasarathy, 2004; Jain et al., 2021; Rahayu et al., 2017)

__The main objectives of this project are:__

1.Explore novel classification models to predict purchase intentions.

2.Identify key factors within the best-performing model that significantly influence purchase intentions.

3.Group users into distinct categories based on their time spent on specific pages and exit rates.

The dataset used for this analysis is sourced from the Online Shoppers Purchasing Intention dataset provided by UC Irvine’s Machine Learning Repository. Each session in the dataset corresponds to a different user within a one-year period, ensuring diversity and avoiding bias towards specific campaigns, special days, user profiles, or seasons. The dataset comprises 18 features: 7 numerical and 11 categorical, and it includes a total of 12,330 entries.

The data set along with the introductory paper can be found here: https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset


**Column Descriptions:**

Administrative: This is the number of pages of this type (administrative) that the user visited.

Administrative_Duration: This is the amount of time spent in this category of pages.

Informational: This is the number of pages of this type (informational) that the user visited.

Informational_Duration: This is the amount of time spent in this category of pages.

ProductRelated: This is the number of pages of this type (product related) that the user visited.

ProductRelated_Duration: This is the amount of time spent in this category of pages.

BounceRates: The percentage of visitors who enter the website through that page and exit without triggering any additional tasks.

ExitRates: The percentage of pageviews on the website that end at that specific page.

PageValues: The average value of the page averaged over the value of the target page and/or the completion of an eCommerce transaction.

SpecialDay: This value represents the closeness of the browsing date to special days or holidays (eg Mother's Day or Valentine's day) in which the transaction is more likely to be finalized. 

Month: Contains the month the pageview occurred, in string form.

OperatingSystems: This variable represents the operating system that the user was on when viewing the page.

Browser: This variable represents the browser that the user was using to view the page.

Region: This variable represents which region the user is located in.

TrafficType: This variable represents what type of traffic the user is categorized into.

VisitorType: A string representing whether a visitor is New Visitor, Returning Visitor, or Other.

Weekend: A boolean representing whether the session is on a weekend.

Revenue: A boolean representing whether or not the user completed the purchase.


**References:**
1.Jain, Vipin, B. I. N. D. O. O. Malviya, and S. A. T. Y. E. N. D. R. A. Arya. "An overview of electronic commerce (e-Commerce)." Journal of Contemporary Issues in Business and Government 27, no. 3 (2021): 665-670.

2.Rahayu, Rita, and John Day. "E-commerce adoption by SMEs in developing countries: evidence from Indonesia." Eurasian Business Review 7 (2017): 25-41.

3.Schaupp, L. Christian, and France Bélanger. "A conjoint analysis of online consumer satisfaction1." Journal of electronic commerce research 6, no. 2 (2005): 95.

4.Vijayasarathy, Leo R. "Predicting consumer intentions to use on-line shopping: the case for an augmented technology acceptance model." Information & management 41, no. 6 (2004): 747-762.
