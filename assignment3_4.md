# Step 1. Find a data visualization
![If the image is broken, please try this link to view https://github.com/xuan827/Roxanne-portfolio/blob/main/fig2.png](https://github.com/xuan827/Roxanne-portfolio/blob/main/fig2.png?raw=true)

Source: [https://equitablegrowth.org/how-workplace-segregation-fosters-wage-discrimination-for-african-american-women/](https://equitablegrowth.org/how-workplace-segregation-fosters-wage-discrimination-for-african-american-women/)

DataSet: [https://equitablegrowth.org/working-papers/intersectionality-labor-market/](https://equitablegrowth.org/working-papers/intersectionality-labor-market/)

This visualization is from an article "How workplace segregation fosters wage discrimination for African American women". The visualization is generated from the analysis result of the Mark Paul's paper. The visualization aims to reflect that discrimination and segregation are the main reasons of wage gap for black women by dismantling the impact proportion of different factors on the wage gap. But it is hard to get the relationship of the theme and the graph directly without referring article and original paper. From Paul's paper, we could know that unexplained factor are likely due to discrimination, and occupation and industry factors in explained factors are belongs to workplace segregation which is also because of discrimination, but the visualization doesn't present these information clearly. Therefore, in this assignment, I will try to redesign the visualization so that it can convey the theme more clearly.

# Step 2. Critique the data visualization
The full critique are in the Google form, and here I only summarize the key points.

The arrow from left graph to right graph is clear, which helps audience to quickly get the relationship of these two graph. The subtitle is clearly explained, assisting the understanding. But it also has some problems.
- It is hard to understand the relationship between the title and graph. The designer use different color to differentiate different factors, but these factors seem to have no relationship with discrimination and segregation. So I felt confused how to get the conclusion that discrimination and segregation are the largest causes of black women’s wage gap. 
- These color patches are arranged disorderly, and it is difficult to quickly perceive the size of each color patch through the percentages at below. At the same time, there are negative percentages. It is difficult for me to understand what this means without looking carefully at the original paper.

Therefore, I would change the color and use the color to represent the relationship with discrimination and segregation, making the graph can tell the story corresponding to the title. And I will also change the order and direction of the patches placed and make them much easier to be observed.

# Step 3. Wireframe a solution
![If the image is broken, please try this link to view https://github.com/xuan827/Roxanne-portfolio/blob/main/wireframe.png](https://github.com/xuan827/Roxanne-portfolio/blob/main/wireframe.png?raw=true)

- In order to make audiences much easier to understand 36 cents wage gap, I used a coin picture as the background of pie chart.
- Change the color, and use the darkness degree of red as the degree of factors related to discrimination and segregation, corresponding to the title I want to express.
- Merge “Metro and Region” and “Public Sector” to eliminate the confusion to audience because of the negative percentage.
- Reorganize the order and direction of color blocks. I put blocks related to workplace segregation together and others arranged using size from large to small, which is much easier to observe the proportion of factors related to segregation and better present the theme.
- Add grid lines of the percentage and the percentage of each factor in the total wage gap to further help the audience intuitively percieve the size of differnt blocks.



# Step 4. Test the solution
I selected two friends with different backgroud, one is interested in politics and sociology, and the other one only has some basic understanding. I want to test whether my visualization is easy to be understood by professionals and general audiences that only want to learn more about a new topic.

Friend 1:

He can correctly tell me what the visualization presents. And he thought the intended audience will be dome politician, researchers and those who are interested in equality. There are some confusion and suggestion he pointed:
- the numbers "18.1%, 9.6..." are difficult to make him understand at once. And the percentage from 0% to 100% are also a little bit confusing. Why 45.5% becomes 0% to 100%? Is it much better to move the percentage from left side to right side?
- The black line between the two subgraphs was intended to explain 45.5%, but it may be misunderstood that it is the interpretation of the whole 36 cents。
- Is the gradient of red related to both discrimination and segregation? why all of them use red？ Are they the same meaning?
- Different factors on the right are placed on the grid line, which is easy to misunderstand. You can remove the grid line on the right.

Friend2:

She can tell me what the visualization wants to express but also has doubts about some details. And she thought the intended audience will be some reseachers, experts but also can be general audience. There are some confusion and suggestion she pointed:
- The rightmost text is placed on the grid line. She is a little confused about the correspondence between the text and each stacked block.
- Why there is a 36c wage gap
- What is the difference of discrimination and segregation?
- why only 18.1% has percent sign, and she cannot quickly get the meaning of these numbers.

Feedback summary and my reflection:

Based on the interview, I found there are mainly 3 problems of my visualization.

- The label in the right figure does not correspond well to the figure
  - Place the label on the corresponding color block.

- For the further disassembly and interpretation of 44.5% explained gap, it is difficult for the audience to understand further disassembly analysis and the meaning of the percentages of the two different scales(0%-100% and 18.1%, 9.6%...) at once.
  - Make a hierarchy graph instead of two subgraphs. 
  - Use color blocks to intuitively show the proportion to people instead of numbers that may be confusing.

- The professional concepts proposed in the paper, discrimination and segregation are not well explained by visualization through title, subtitle and graph.
  - Optimize the interpretation of titles and subtitles, and redesign the color and meaning of color to better highlight the theme in the figure

- There is some information that is not very relevant to the theme that will make the audience confused, such as 36 cents.
  - Remove information that is not very relevant to the theme

# Step 5. Build your solution
<div class="flourish-embed flourish-hierarchy" data-src="visualisation/8611985"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Based on the feedback of my wireframe, I try to refine it and build my final solution.

- I choose hierarchy graph because there is a disassembly of factors, the hierarchy diagram can better show the corresponding relationship than using two subgraphs with pointer. And audience can click the explained area to observe the further disassembly of explained factors.
- Redesign title. Audiences may be confused about the difference or relationship of discrimination and segregation. I found segregation is a form of discrimination after I read the article and original paper. Therefore, I redesign the title showing the inclusive relationship between discrimination and segregation as well as emphasizing the significant impact of segregation on wage gap.
- Color. I use the darkness degree of red as the degree of factors related to discrimination instead of discrimination and segregation since segregation is a form of discrimination. Therefore, in order not to confuse readers, I make red simply indicate discrimination, add a "discrimination type" attribute for different color blocks in the pop-up window, a filter to select differet discrimination type and explained it in the subtitle to help readers realize that segregation is an explained discrimination causing wage gap.
