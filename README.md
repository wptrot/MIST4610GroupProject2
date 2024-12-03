# MIST4610GroupProject2

## Team Name and Members
**group8**
- Forcucci, Enzo:
- Runckel, David
- Trotman, William:
  
## Dataset Description
Our group chose to visualize the dataset "Health conditions among children under age 18, by selected characteristics: United States" provided by the U.S. Department of Health & Human Services. This is because, in an ideal world, no child should have to battle with health conditions and if we could use this data to formulate possible solutions, then that would help us reach our ultimate goal.

https://catalog.data.gov/dataset/health-conditions-among-children-under-age-18-by-selected-characteristics-united-states-53b56

The dataset recorded the percentage of children with health conditions in the United States between 1997-2018. Some of the health conditions include ADHD, asthma, food allergies, and skin allergies. 2744 rows of data were contained within the dataset with 16 columns/fields providing descriptive information regarding each row. Some key fields our group chose to utilize in our visualizations are listed below.

**Panel Column:** The different health conditions such as ADHD, asthma, food allergies, and skin allergies.

**Stub Label Column:** The various characteristics of the children such as age, gender, and race.

**Year Column:** Each year between 1997-2018 is grouped by a lapse of 3 years. For example, 1997-1999 or 2013-2015.

**Estimate Column:** The percentage of children afflicted by the health condition(s).

## Question 1
**Question:** Does the percentage of children affected by skin allergies differ between races?

**Value:** What environmental factors can we attribute to an increase/decrease in skin allergies, and if one or more races are affected by skin allergies at a higher rate than others, then we can utilize this data to propose possible reasonings, and hopefully solutions from our findings.

**Fields Used:** Used the Year Field to construct a line graph of the percentage of children with skin allergies via the Estimate and Panel Fields. Each line represents a different race from the Stub Label Field.

## Question 2
**Question:** Does the percentage of children affected by various health conditions vary between 1997-1999 and 2016-2018?

**Value:** Understanding how the percentage of children affected by these diseases has changed over time allows us to identify health trends, both positive and negative.

**Fields Used:** A bar chart was created using 3 fields. The Year Field differentiates between the two timespans, 1997-1999 and 2016-2018. The Panel Field represents the distinct health conditions, while the Estimate Field provides the percentage of children affected.

## Dataset Manipulations
![](GP2Q1.png)

**Question 1:** For a line graph to be useful and show trends over a timespan, the Year Field must be on the x-axis of the visualization. In the y-axis is the Estimate Field, which is used to depict the percentage of children with skin allergies. It only depicts skin allergies instead of all health conditions because the visualization is filtered via the Panel Field to do so. Another core filter is the one placed on the Stub Label Field to depict individual lines for each race in the dataset. A filter specifically used to make the visualization easier to understand was the one placed on the Year Field to ensure all the included years on the y-axis were congruent with one another and didn't include any overlap. The Stub Label Field was used for the visual effect of colorized lines.

_____________________________________
![](GP2Q2.png)

**Question 2:** In the y-axis is the Estimate Field, which is used to depict the percentage of children with health conditions. What's different about this usage of the Estimate Field compared to Question 1 is that no filter is needed because of the usage of the Panel Field in the x-axis. This, combined with the Year Field, is what creates the separate bars for each health condition, comparing the two timespans for each. A filter on the Year Field is used to only model these two timespans instead of the multitude that are within the dataset. The Year Field is once again used, this time to color the bars, blue for 1997-1999 and orange for 2016-2018.

## Analysis and Results
**Question 1:** We focused our research on the possible cause behind the disproportionate number of African American children affected by skin allergies. This is because it was far and away the biggest outlier in the visualization. Not only did they see a doubling in the percentage of children affected by skin allergies between 1997-2018, but at its peak, there was a 6.30% difference between African Americans and the second-highest affected race (Asians).

Before going further into the research, we wanted to give a reminder that none of the following conclusions or points of research came from a place of hate or prejudice. We simply wanted to find conclusions that tied to the visualization and the articles we chose supported the outlying trend.

Based on two separate articles published in the National Library of Medicine, operated by the United States Federal Government, we concluded that a mix of socioeconomic and genetic factors played a role in this major discrepancy. The article outlying the socioeconomic factors that could be associated with the data focused on eczema, the most common form of skin allergy. Eczema is mainly caused by an overactive immune system reacting to the surrounding environment via adverse reactions to dust mites and certain chemicals within disinfectants and detergents. We surmised that these catalysts were more prevalent in African American households due to a lower standard of living caused by an economic disparity. Utilizing data acquired from the Bureau of Labor Statistics on annual income for different households based on race from 2014-2016, African Americans on average made $21,577 less than the total average. This directly shows the economic disadvantage that African Americans are faced with and thus puts them at greater risk in an environment that is correlative to eczema. All of these factors collide, leading to an increased rate of eczema in African American children.

In the second article, research indicated that a structural difference in skin also played a part in higher rates of eczema specifically. One point highlighted was the desquamation rate differences between races. Desquamation rate is defined as the shedding of dead skin cells and African Americans had a desquamation rate 2.5x higher than other races. Dead or dry skin is a symptom of eczema and if African Americans have dryer skin than other races, then it could be surmised that this acts as a catalyst of sorts to the development of eczema itself.

While finding a reason behind why African Americans are disproportionately affected by skin allergies compared to other races was valuable, coming up with possible solutions holds considerably more significance towards why we wanted to work with this dataset. One solution we proposed was to encourage funding for eczema treatments that are less "one-size-fits-all" and more curated towards African Americans and other disproportionately affected groups. It seems preposterous that we don't work towards solutions for groups more negatively affected than others.

__________________________________________________________
**Question 2:** Our analysis focused on identifying trends in the percentage of children affected by various disease panels between 1997–1999 and 2016–2018, using the oldest and most recent data available. One striking difference highlighted in our visualization pertains to the category of serious emotional or behavioral difficulties. While nearly 6% of children were reported as affected in recent years, this category was absent from the dataset in 1997–1999. This absence does not indicate a lack of mental health issues in the 1990s but rather reflects a significant evolution in the recognition, diagnosis, and treatment of children's mental health and behavioral challenges. Increased awareness and expanded resources have played a pivotal role in this shift. Notably, the dataset began recording emotional difficulties as a category of illness between 2003–2005, marking a key turning point.

Although no substantial change was observed in the overall prevalence of mental disorders between 1990–1992 and 2001–2003, the proportion of children receiving treatment for emotional problems nearly doubled—from 12.2% to 20.1% (National Library of Medicine, 2010). This indicates growing recognition of mental health needs and improved response mechanisms. By 2019, 70.7% of children aged 4 to 17 with mental health problems were receiving treatment, underscoring a significant enhancement in access to mental health services compared to earlier years (OASH, 2024).

Additionally, the data revealed a marked increase in the prevalence of food and skin allergies over the two-decade span. This growth can be attributed to advances in diagnostic testing as well as environmental and dietary changes. Since the 1990s, medical professionals have shifted from RAST allergy tests, which utilized radioactive materials, to modern, safer, and more accurate methods. These advancements have made allergy diagnosis more accessible and affordable, contributing to higher reported rates. Increased urbanization and pollution have also been linked to allergic conditions, as exposure to pollutants like diisocyanates and xylene can disrupt skin microbiota, leading to conditions such as atopic dermatitis (Wikipedia, 2024). Changes in dietary habits, including the delayed introduction of allergenic foods, have similarly been associated with rising food allergy rates. However, recent studies suggest that early introduction of foods such as peanuts can help reduce the risk of developing allergies.

While this analysis highlights just two of the five disease panels in our visualization, it underscores the importance of exploring these shifts in greater detail and expanding investigations beyond the initial and final data points. Doing so will allow medical professionals to better understand these trends, enabling them to improve preventative measures, diagnosis, and treatment for affected populations.



## Tableau Packaged Workbook
**Tableau:** https://github.com/DavidRunckel/MIST4610GroupProject2/blob/main/MIST4610GroupProject2.twbx

**Presentation:** https://docs.google.com/presentation/d/1_spfeNQEnBOtTZ1GlbQeA-eewAAE1KfyYS9dKZrO6pU/edit?usp=sharing

## Works Cited
Croce, Emily, et al. “Reframing Racial and Ethnic Disparities in Atopic Dermatitis in Black and Latinx Populations.” U.S. National Library of Medicine, The Journal of Allergy and Clinical Immunology, 30 Sept. 2021, pmc.ncbi.nlm.nih.gov/articles/PMC8578465/.

Noël, R. A. (2018, May). Race, Economics, and Social Status. U.S. Bureau of Labor Statistics. https://www.bls.gov/spotlight/2018/race-economics-and-social-status/#:~:text=Such%20increases%20in%20income%20inequality,or%20African%20Americans%20with%20%2448%2C871.

Wesley, Naissan O, and Howard I Maibach. “Racial (Ethnic) Differences in Skin Properties: The Objective Data.” U.S. National Library of Medicine, American journal of clinical dermatology, 21 Aug. 2012, pubmed.ncbi.nlm.nih.gov/14640777/.

“What Is Eczema?” National Eczema Association, nationaleczema.org/eczema/#:~:text=Natural%20liquids%20like%20the%20juice,areas%20of%20the%20skin%20differently. Accessed 20 Nov. 2024.

National Library of Medicine, Kessler, R. C., Demler, O., Frank, R. G., Olfson, M., Pincus, H. A., Walters, E. E., Wang, P., Wells, K. B., & Zaslavsky, A. M. (2005, June 16). Prevalence and treatment of mental disorders, 1990 to 2003. The New England journal of medicine. https://pmc.ncbi.nlm.nih.gov/articles/PMC2847367/ 

OSHA. (2024). Increase the proportion of children with mental health problems who get treatment - MHMD‑03 data. Increase the proportion of children with mental health problems who get treatment - Data - Healthy People 2030. https://odphp.health.gov/healthypeople/objectives-and-data/browse-objectives/mental-health-and-mental-disorders/increase-proportion-children-mental-health-problems-who-get-treatment-mhmd-03/data?from=2019&group=Age+group&populations=12-17_years&state=United+States&to=2019 

Wikipedia. (2024, August 14). Hygiene hypothesis. https://en.wikipedia.org/wiki/Hygiene_hypothesis? 
