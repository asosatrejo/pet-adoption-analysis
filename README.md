#  Pet Adoption Analysis
## Created by Team 5
We aim to increase the number of dogs & cats being adopted within North Carolina. To accomplish our goal, first, we must recognize what factors affect adoption rates. We will look at the pets, the shelters, and the areas to determine whether any significant data can be determined. After analyzing, we will conclude with our findings whether there are any pets that are being ignored, if a shelter has any shortcomings, or if specific areas, in general, affect the adoption rates. 

Our team will use the following APIs to extract data for our research.
  **API/Resources:**
  - [PetFinder API](https://www.petfinder.com/developers/)
  - [PetPy Python Wrapper](https://petpy.readthedocs.io/en/latest/api.html)

### Main Question:
How can we increase the overall adoption rate of cats & dogs in North Carolina?

### Important notes: 
- Our scope is subject to change to a national level depending on the data found and APIs. For the purposes of avoiding scope creep, we will not go beyond the national level.
- To avoid scope creep in the project we are focusing on how dogs & cats specifically are affected, while we do acknowledge there are more types of pets then one should also acknowledge that covering a large variety of pets will make the project less feasible in the long run. 

### Research Questions:
1. Which adoption organizations are most convenient for a potential customer to browse cats and/or dogs through social media?
2. Is a certain age, size, or sex of a dog/cat more/less likely to be adopted?
3. Does a certain area (location) have higher/lower adoption rates? 

These questions are to help us narrow our research to help find significant data that can provide an answer to our main question.

### Tasks/Team Member responsibilities:
#### Each individual: 
- Will create the slides for their focus question, and aim to answer their focus and main question
- Will clean their data, create graphs, and do the majority of work for their focus question
- Review the overall project including slides, peer work, and ReadMe to make sure rubric requirements are met
- Help out other team members to the best of their ability

#### Individual Tasks/Responsibilities:
- Ariana - Host the Repository, focus on question 3, 
- Dwight - Host the Presentation, focus on question 2
- Ross - Focus on ReadMe, focus on question 1


# Requirements
### Completed Analysis Uploaded to Github
- Final data analysis contains ample and complete information.
- Final repository is acceptable for professional quality presentation.

### Data Visualization
- 6–8 visualizations of data
- Clear and accurate labeling of images
- Visualizations supported with ample and precise explanation

### Analysis and Conclusion
- Write-up summarizes major findings and implications at a professional level
- Each question in the project proposal is answered with precise descriptions and findings
- Findings are strongly supported with numbers and visualizations
- Each question response is supported with a well-discerned statistical analysis (e.g., aggregation, correlation, comparison, summary statistics, sentiment analysis, and time series analysis)

# Analysis and Conclusion

## Data Analysis for Question 1:

To find the most convenient organizations for a potential customer to browse cats and/or dogs through social media, we needed to take the initial DataFrame and sort it to make our assessment. Our focus for this portion of the analysis is North Carolina adoption organizations and adoptable cats and dogs. We needed this information to accurately gather the information for a potential customer and the perfect home for our furry friends. With those specifications met, we looked for organizations with major social media platforms and graphed the results. But to really narrow down our results, we made the analysis more precise by looking for the organizations with all the major social media platforms, eight. From those eight organizations, we went back to our first focus of cats and dogs by customizing the analysis to discover the most convenient organizations for cats and dogs separately by turning the results into csv files. With our new findings captured and posted for visualization, we noticed one organization met all of the qualifications of this portion, Chatham Animal Rescue Education Inc.

One of the key reasons why Chatham Animal Rescue Education Inc. stands out as the most convenient organization for pet adoption through social media is their extensive presence on various platforms. They have a well-maintained Facebook page where they regularly post updates about available animals, adoption events, success stories, and educational content. Through twitter, Chatham Animal Rescue Education Inc. is able to share real-time updates about new arrivals, urgent adoption needs, and upcoming events. YouTube and Instagram are also powerful social media platforms that showcase their animals in a visually appealing manner. On YouTube, they upload videos that provide virtual tours of their facility, introduce individual animals, and share heartwarming adoption stories. Instagram allows them to share captivating photos of their furry residents along with engaging captions that highlight each animal's unique personality. By implementing these four social media platforms together, a potential customer has the appropriate resources provided to appeal to a wider audience.

## Data Analysis for Question 2:

For the first part of this question, we created two pie charts analyzing the adoption percentages of cats and then dogs when compared by age. There is a clear correlation in both pie charts that we can see and it would seem that the younger a dog or cat is the more likely they are to be adopted. The baby animals make up around half of the pie chart in both cats and dogs when it comes to how many of them were adopted. Unfortunately this does mean the older animals are less likely to be adopted as senior animals of both types hardly have any presence on the pie chart. It does seem however that adult dogs are more likely to be adopted than young ones but for the most part, younger animals do seem to do better. 

Next, we focus on size and the data would like us to believe that Medium sized dogs and cats are more liked than the others especially when we are talking about cats. From here however we can see that animals larger than that are not adopted as often, especially with extra large animals that seem to be rarely adopted. This makes a lot of sense as well given that larger animals are harder to take care of. So one takeaway here is that there isn’t necessarily a ‘too small’ since the adoption rates of the smaller animals are still relatively good but there is definitely a ‘too large’ because the demographic of larger animals that have been adopted is very small.

The Final part of this question is perhaps the least telling given the fact that be it dog or cat the rate of adoption between the males vs the females is nearly even. The split isn’t significant enough to tell us that one gender is preferred over another and gives us the insight that the gender of the animal has little to no impact on the choices that potential pet owners make so gender will not be a big factor in predicting the rate of adoption or in any way a part of the plan when it comes to helping pets get adopted. 

To conclude it would seem as though smaller and younger pets are some of the most likely to be adopted. More specifically due to our data it would seem that a baby cat/dog that’s medium-sized has the absolute best chance of being adopted. Now we can reason why this all is, if someone were to adopt an older pet you wouldn’t have them around nearly as long as a younger one and you also have the benefit of training them how you want to train them and getting them used to your family. Small to medium-sized pets are also easier to manage, you can pick them up easier,  have smaller messes if any and I imagine discipline will come easier as well. To help improve the rate of adoption perhaps organizations can attempt to promote animals that are younger to be adopted and try to get them adopted as young as possible all the while managing their weight to attempt to keep them within the small-medium range. Naturally, there are breeds of animals that are larger by nature but even managing a diet for potential pets would likely do wonders.

## Data Analysis for Question 3:

To answer this question, there could be a couple of different sets of data that could be analyzed. To begin with, Petfinder organizes the type of pets by species, status, and date. Already as a team, we agreed to focus on cats and dogs. We also agreed to look between the dates starting on January 1st, 2018, to January 1st, 2023. Status was the last factor and there were three possibilities: adopted, adoptable, and found. In just one year, over 10,000 dogs were adopted, so looking over the last 5 years would give us quite a bit of data. Unfortunately, the runtime was minutes long, sometimes exceeding 10, so a different approach was taken with the appropriate observations. Instead of focusing on pets that have been adopted, we could shift our focus to pets that were available for adoption within the last 5 years. The shift allowed the data to be processed quicker and provided a different perspective to answer the question.

After gathering, cleaning, and organizing the data, it was time to create charts. The data retrieved focused on the species but kept cats and dogs separated. Organizations were kept, and the state was narrowed down to just North Carolina. Other information was necessarily needed, so it was removed, except for cities. Cities were the focus and what was needed to see if there were areas that stood out in North Carolina as hubs where more pets could be adopted. To view the cities where cats and dogs were listed as adoptable, < .value_counts() > was used to return a sorted list. To begin with, not much data was given, from between 200 to 400 results were given. After the sorted list was printed, a couple of cities had very little and similar numbers. To gain a better understanding and clearer perspective, there was another shift to answer the main question. The top 10 cities were separated to create a scatter plot with the latitudes and longitudes. 

On the scatter plots, the cities were labeled. The sizes and colors of the dots are based on the number of adoptable pets. From these plots, we can arrive at several conclusions. First, the most adoptable dogs are found in Raleigh, North Carolina. Second, the most adoptable cats are found in Pittsboro, North Carolina. Third, both maps featured cities in the western region of North Carolina. However, before we can generalize our conclusions, we must address some potential factors that may affect the data provided. First, not every shelter in North Carolina may be providing up-to-date information on their pets. The pets may also be listed as "found" and not "adoptable". Perhaps shelters use a different database in general. In any way, we must be aware that this may be missing information. Secondly, these scatter plots only display the top 10 cities that came with the highest number of adoptable dogs and cats. This could be due to more animals in the area, or perhaps more animals are taken to organizations where they can be adopted. But we can't read more into the data and assume that these locations have the most adopted cats or dogs. That would be a completely different set of data. That conclusion leads us to the final factor, which is that we may not have completely answered our original question. However, the main goal was to increase adoption. In the end, we can see what cities have more pets up for adoption and can use this data to encourage pet-seeking people to visit a nearby city for adoption options. 

Although the focus was shifted in the process of answering the initial question, it did serve as a great starting point. We can conclude that western North Carolina generally has the most adoptable pets, and can view images "top-10-dogs-scatter.png" and "top-10-cats-scatter.png" to see the general area in which the cities are located. With more experience, and perhaps a better laptop, a bigger dataset could be analyzed to take a different approach to answering the initial question. "Does a certain area have higher/lower adoption rates?" Perhaps, but we can answer "Does a certain area have higher/lower available adoptable pets?" Yes, look to Western North Carolina!

# Resources

# Files included
## Location Analysis
- Location-Analysis.ipynb
- top-10-cats-scatter.png
- top-10-dogs-scatter.png

# Pet Attributes Analysis
- Per-Adoption-Analysis.ipynb

## Location Analysis - Portion completed by Ariana
- [Navigating Petfinder’s API using Petpy Wrapper](https://medium.com/analytics-vidhya/navigating-petfinders-api-using-petpy-wrapper-2cf085c33d75)
- [Pythonic Data Cleaning With pandas and NumPy](https://realpython.com/python-data-cleaning-numpy-pandas/)
- [Pandas Drop Last Column from DataFrame](https://sparkbyexamples.com/pandas/pandas-drop-last-column-from-dataframe-2/#:~:text=using%20iloc%5B%5D-,Using%20DataFrame.,the%20last%20column%20from%20DataFrame.)
- [Matplotlib Cheatsheets and Handouts](https://matplotlib.org/cheatsheets/)
- [List of Named Colors](https://matplotlib.org/stable/gallery/color/named_colors.html)
