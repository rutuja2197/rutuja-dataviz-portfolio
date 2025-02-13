| [Home page](https://rutuja2197.github.io/rutuja-dataviz-portfolio/) | [data viz examples](dataviz-examples.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# Critique by Design: MakeoverMonday  
This is a critique of the Animal Rights Index 2023 visualization from MakeoverMonday, evaluating its effectiveness in presenting global variations in animal welfare.

## Step one: the visualization

<b>Visualization Title:</b> Animal Rights Index 2023

<b>Source:</b> The Swiftest

<b>URL:</b> [https://theswiftest.com/animal-rights-index/#:~:text=Animal%20rights%20laws%20vary%20greatly,cruelty%20any%20way%20they%20can](https://theswiftest.com/animal-rights-index/#:~:text=Animal%20rights%20laws%20vary%20greatly,cruelty%20any%20way%20they%20can) 

<b>Summary:</b><br>
This visualization presents the Animal Rights Index 2023, ranking countries based on their animal welfare rights. The index considers factors such as the recognition of animal sentience, recognition of animal suffering, laws against animal cruelty, national fur-farming ban, support for the universal declaration of animal welfare, meat consumption per capita, percentage of protected areas, pesticide usage per hectare of cropland, and environmental performance index score. The data is displayed in a ranked table and is both color-coded as well as icon-based, highlighting variations in multiple attributes contributing to animal rights across different countries.

<b>Why I Chose This Visualization:</b><br>
I am an animal lover, and as I was going through different visualizations, this one instantly caught my eye. Since I have a pet dog, I was curious to check which country would be the best for my dog and which one would be the worst. Additionally, the visualization had a lot going on—multiple elements, colors, and rankings—which made it interesting to critique. I wanted to analyze whether all the information was presented effectively or if the complexity affected its clarity.

## Step two: the critique
The Animal Rights Index visualization on <i>The Swiftest</i> presents several challenges that affect its effectiveness.  The design is cluttered with inconsistent icon usage and a lengthy table format, making it difficult for users to quickly find the top and bottom countries, which would be most relevant to the primary audience — pet owners or individuals seeking pet insurance, since <i>The Swiftest</i> is a pet insurance website. While factors and weights are provided at the end of the table, it’s hard to correlate them with the scores just by looking at the table, making it confusing. The lack of explanation for the grading system and the use of solid circles for some metrics and icons for others creates confusion.

The visualization offers moderate usefulness but falls short due to the difficulty in quickly extracting actionable insights from the long table format. In terms of completeness, while it covers a broad range of countries, the lack of detailed information on the scoring methodology and country-specific laws weakens its overall effectiveness. Perceptibility is hindered by the inconsistent use of icons and varying color schemes, which complicate the task of quickly understanding the data. The truthfulness of the data appears solid, and provides a reference of multiple sources. Intuitiveness suffers because of the overwhelming table format and unclear layout, making it hard for users to navigate. The aesthetics are inconsistent, with varying icon styles and color schemes detracting from a cohesive design. Lastly, the engagement level is moderate, as users may find the information relevant but not interactive enough to keep them engaged for long periods.

For improvement, I recommended using a bar graph to display the top 20 and bottom 20 countries in a more digestible format, allowing users to instantly grasp the key information. Further, I recommended including a more detailed table could be included for users looking for deeper insights. I also suggested utilizing a uniform color gradient for all metrics, whether numerical or categorical, to improve the overall visual consistency and make the data easier to interpret. Finally, clarifying the scoring methodology and incorporating a clear explanation of the score calculation would enhance the transparency and usefulness of the visualization.

## Step three: Sketch a solution

<div align="center">
  <img src="Top 10 & Bottom Charts.png" width="500">
  <img src="HeatMap (2).png" width="900">
</div>

## Step four: Test the solution

The focus was to understand how the visual works for different viewers and what changes could be made to improve clarity, usefulness, and engagement. I asked the participants in to evaluate both the charts separately and together to see if any patterns or insights emerged.<br>

### Questions to ask:

- Can you describe to me what this is telling you?
- Who do you think this is intended for?
- Is there anything you find surprising or confusing?
- Is there anything you would change or do differently?
- Overall, do you find this easy to read?

These were the main questions I aimed to target, and I asked them for both the charts separately and together.

### Results:
- <b>Can you describe to me what this is telling you?:</b> Everyone found the visualization easy to understand for both charts. One suggestion was to group certain factors together to avoid making the table too large.
- <b>Who do you think this is intended for?:</b> While splitting the chart into two made it clearer, everyone still felt the visualization was more suited for animal activists. A suggestion was made to adjust the title of the first graph to better target pet owners or insurance seekers.
- <b>Is there anything you find surprising or confusing?:</b> The factors listed in the table were found confusing and there was a general sense of uncertainty about the metrics used for ranking countries.
- <b>Is there anything you would change or do differently?:</b> There was a suggestion to show the top 10 countries instead of 20 to make the chart more concise. Another recommendation was to use color highlighting to differentiate countries based on their assigned grade for better clarity.
- <b>Overall, do you find this easy to read?:</b>  Everyone agreed that the revised version was easier to read compared to the original visualization. They appreciated the use of the chart, which showed the topmost and bottom-most countries, and the division into two parts, which helped with readability and targeting the suited audience. The original version had a lot of unnecessary icons that didn’t make sense and only added confusion. One person even mentioned they would skip reading after the first country because of the overwhelming amount of data. This redesigned version is much easier to read and more focused.

### What I learned:
The feedback highlighted key areas for improvement in my redesign. Grouping related factors together or displaying only pet-relevant ones could help reduce the table's size, making it easier to interpret. Additionally, adjusting the title to better target pet owners or insurance seekers—rather than animal activists—could increase engagement. While the revised table was a visual improvement over the original, it still felt more relevant to activists than to pet owners. The grading system created confusion in the reader's mind due to lack of explanation.

## Step five: build the solution

For my final redesign of the Animal Rights Index visualization, I focused on simplifying the layout to enhance readability and clarity while keeping only the most relevant data. Based on user feedback, I made the following changes:

- <b>Kept only the top 10 and bottom 10 countries:</b> Instead of displaying a long table with all countries, I split the rankings into two sections—one for the top 10 and another for the bottom 10 countries based on the Animal Rights Index. This change made the data easier to digest and helped viewers focus on the most relevant rankings without feeling overwhelmed. I also refined the chart titles to better suit the target audience.
- <b>Removed the heatmap:</b> Feedback indicated that the visualization still felt geared toward animal activists and had too much information. To shift the focus, I replaced the heatmap with a simpler text display, showing only the relevant factors for pet parents alongside the selected country's rank and index score. I also added a filter, allowing users to select any country and view its key metrics in a straightforward format. This approach eliminated the need for a complex table, making it easier to interpret the data at a glance.
- <b>Removed the grades:</b> Since there was no clear explanation of how the grades were calculated, they contributed more to confusion than clarity. Removing them streamlined the visualization and kept the focus on meaningful insights.
- <b>Simplified titles:</b> Based on feedback, I revised the titles — not just for the charts but for the entire dashboard—to better align with the intended audience. This ensured the visualization was more relevant to pet owners and others seeking practical insights rather than animal rights activism.

### Process Summary: 
Overall, this redesign process reinforced the importance of clarity, simplicity, and ensuring the visualization speaks directly to the needs of its intended audience.

### Final Redesign: 
Below is the final redesigned version of the Animal Rights Index visualization:

<div align="center">
  <img src="Final Redesign.png" width="700">
</div>

### Original Design:

<div align="center">
  <img src="Original Design.png" width="700" alt="Courtesy: The Swiftest">
  <p>Courtesy: <i>The Swiftest</i></p>
</div>

## References
- [https://theswiftest.com/animal-rights-index/#:~:text=Animal%20rights%20laws%20vary%20greatly,cruelty%20any%20way%20they%20can](https://theswiftest.com/animal-rights-index/#:~:text=Animal%20rights%20laws%20vary%20greatly,cruelty%20any%20way%20they%20can)
- 

## AI acknowledgements



