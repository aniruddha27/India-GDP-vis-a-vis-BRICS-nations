# India-GDP-vis-a-vis-BRICS-nations
Built this as project for the course-Applied Plotting, Charting & Data Representation in Python by University of Michigan on Coursera.
Certificate can be found here-https://www.coursera.org/account/accomplishments/verify/QBKCHRF2ZM35

Question?

How does India's standard of living compare to that of other nations in the BRICS group based on their GDP values?

About the dataset?

The four datasets were taken from World Bank database. The column names were replaced with the 4th row which contains the years. Then the first four columns were dropped to start the columns from the year 1980. There were a lot of null values between 1980-1990 for most of the BRICS nations, therefore the data for years 1980-1990 was dropped as it would be very difficult to predict almost all those values.

Conclusion?

India has an year-on-year increasing GDP nominal and became the second fastest growing BRICS nation around 2014. Its GDP nominal is pegged at more than $2 trillion in 2017. This, however, does not take into account inflation, that affects exchange rate, and population which, if not accounted for, give a false impression of standard of living in a country.

GDP ppp gives us a picture of what a person in a country can actually buy, or what is actually produced. PPP measures currencies on the basis of their ability to buy goods or servies within the local economy. It gives the relative purchasing power of the local currency. The GDP PPP of India is higher than its GDP nominal indicating that it is a developing economy. The reason that India's GDP ppp is higher than GDP nominal is because the cost of non-tradeable goods in India is lower compared to Brazil, Russia and South Africa. This indicates that the standard of living in India is lower compard to all other nations in the group except China.

China and India that are highly populated nations with a combined population of close to 3 billion people, therefore, it would be wrong to judge the standard of living of BRICS nations without taking into account their population.

GDP per capita takes into account the population of a country. In the graphs we can see that, although nominal GDP of India was the significantly higher compared to other nations, its GDP per capita is actually the lowest indicating lowest standard of living amongst the member nations. This is because of its high population which was not evident is the top two plots.

The last plot, which sums up the entire deduction, shows that all members are developing nations because of higher GDP per capita(ppp) value than the respective GDP per capita with Russia having the higest and India having the lowest standard of living amongst the BRICS nations as of 2017.

Were Alberto Cairo's principles followed?

Truthful: I have removed 1980-1990 data because there were a lot of null values which could be predicted. It would be difficult to predict these values just going by their sheer number.

Functionality: Line chart is the best choice for plotting the GDP values because it shows the fluctuations in the values. The border of the plots was removed to avoid user distraction from actual data visualisation.

Beauty: The colours indicating the different nations in the plots are taken from their repective national flags so that it makes the lines not only distinct, but also relatable:India-orange,China-red,Russia-blue,South Africa-black,Brazil-green.

Insightfulness: Although India has a higher GDP nominal and GDP ppp, when taking into account its population, it actually has the lowest standard of living amongst the memeber nations.


