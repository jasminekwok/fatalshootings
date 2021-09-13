# Racial Disparities in Fatal Police Shootings

## Abstract
Unjust police shootings have sparked national outrage in the United States and have started international social movements, such as Black Lives Matter that protest against incidents of racially motivated police violence. The media spotlight has been shined on numerous infamous cases of potentially prejudiced police shooting victims, like the shooting of Breonna Taylor. Our project aims to explore whether police shootings are racially biased and if certain racial groups are targeted more. We also aim to look specifically at California which is the State that has the most police shootings and to see if there are any racial disparities in its victims. We find that there is a difference between the racial distribution of police shooting victims and the racial distribution of the population and that African Americans are overly represented in the population of police shooting victims. We determine that our county demographic data on education and income have no correlated variables with black shooting victim population and that California reflects our previous findings and also that Hispanics are overly represented in the State’s population of police shooting victims as well.

## Background
The frequent and lawful police killings in just the last year have contributed to some of the hardest months of the pandemic. With the media coverage of the Black Lives Matter Movements, it seems that so many Police Shooting Victims are African American. However, we noticed that in total there are more White victims than Black in police killings. The connection between police killings and race, especially, has become an even larger issue and has led to mass protesting and looting all over the country. In light of these events circling the wrongful police killings, we intend to create an educational, meaningful, and informative project that is relevant to the current society and helpful for further research in updating future police funding and practices.

Our goal is to perform an in-depth analysis on factors, like race, that were accounted for in thousands of fatal police shootings in recent years. With this research, we hope to learn the specific variables that contribute to racially biased fatalities and explore potential solutions to prevent them from occurring.

## Aims
The first direction we would like to go in for this project is to detect any notable differences between the distributions of races in the regional population and those who were victims of police shootings. After seeing that the proportion of Black Victims is higher than the proportion of the Blacks in our population, we decided to investigate the demographics of a particular region where a police killed a Black victim. We want to see if there is any indication in geography or demographics that may contribute to high Black fatalities in police shootings. Finally, we decided to look specifically at California, the state with the highest number of police killings, to see if its racial distribution can be related to geography. Since California has one of the highest relative Hispanic populations in the country, it would be interesting to see how the distribution of the minority population differs with the number of victims by race.

## Data
Our data is an up to date log of police killings in the United States from the Washington Post for the past five years. It contains general notes about the event and even information about the victim, police and station. The information comes from several different news sources, social media posts and police reports. The data started being logged after the incident in 2014 where Michael Brown, an unarmed black man was killed by the police. A post investigation of this incident showed that the FBI severely undercounted the number of police-caused fatalities and the reason being many departments failed to require reports of this kind. The Washington Post’s database is kept up-to-date as fatal shootings and facts emerge from the Post's collective methods.

The data is publicly available:

Tate, Julie, et al. “Fatal Force: Police Shootings Database.” The Washington Post, WP Company, 22 Jan. 2020, www.washingtonpost.com/graphics/investigations/police-shootings-database/.

For this study, the observational units are incidents of a fatal shooting in the United States by a police officer in the line of duty. An observation was made at each shooting in which a police officer on duty shoots and kills a civilian since January 1st, 2015 to May 9th, 2021 which is the date we downloaded our dataset. The particular details about each killing are are indicated using the variable descriptions in Table 1. In preprocessing, the initial dataset did not include details on budget per capita, age, education, racial, and income demographics of the population for each county. Since, these additional information would help with our subsequent analysis, we added the additional information by merging the 2014 county census data. The variables included in the final dataset are displayed in Table 1 while the first few rows of the final dataset are shown in Table 2.

## Results Highlights 

### Map
The following map was generated by importing the vega dataset and mark_geoshape() to make the map and mark_circle() to plot the coordinates. It displays the locations of every single reported fatal Police Shooting from 2015 and depicts the race of the victim by color. The bar plot on the side reflects the aggregated fatal shootings by race. 

![Image of US Map](https://github.com/jasminekwok/fatalshootings/blob/main/Images/map.png)

### Racial representations in the population and victims of police shootings
![Image of Racial representations in the population and victims of police shootings](https://github.com/jasminekwok/fatalshootings/blob/main/Images/props_chart.svg)

Exploratory analysis focused on the difference between the racial distribution of police shootings victims and the county average proportions of police shooting victims by race. Figure 2 shows the county and state proportion distributions of racial representations in the population and victims of police shootings.

### Exploring the linear correlation values of the racial counts and proportions of police shooting victims
![Image of Heatmap](https://github.com/jasminekwok/fatalshootings/blob/main/Images/heatmap.svg)

Linear correlation values of all racial counts and proportions against various economic and demographic variables was calculated. We found no significant linear correlation between the black population and the other demographic data by county.

### California Proportions 
![Image of California proportions](https://github.com/jasminekwok/fatalshootings/blob/main/Images/CA_proportions.svg)

The proportion of Hispanic and Black victims of the fatal shooting in California were much higher, around 6 percent and 13 percent, than the actual racial proportion in California. In contrast, the proportions of White, Asian, Native, and Other victims were lower in the fatal shootings data than the actual racial proportion in California by around 5 percent, 10 percent, 3 percent, and 1 percent. Ideally, we would hope for the proportion of racial demographics in the fatal shootings data equal the proportion from the census. However, our findings suggest that Hispanic and Black victims are overrepresented in fatal shootings while the other racial groups are underrepresented.


