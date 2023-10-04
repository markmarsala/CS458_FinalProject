# CS458_FinalProject

Problem
The problem that we are trying to solve is to identify “highly influential” videos on a set of Youtube data. Influence is determined by the PageRank score of the video. Create an algorithm that can take YouTube datasets and find the K (determined by user) most influential videos in the dataset.

Tasks

Data Collection
Extract the relevant YouTube data from the provided URL: http://netsg.cs.sfu.ca/youtubedata/.

Data Preprocessing
Handle missing values, remove duplicates, and address inconsistencies.
Transform data into a suitable format, handling timestamps, text data, or categorical variables.
Feature Selection: Choose relevant attributes for PageRank-based influence analysis.

PageRank Algorithm
Implement a PageRank algorithm to compute the influence scores for each video.
A high PageRank score means the video has a high influence.

Data Modeling
Create a model of the YouTube network
Nodes represent videos
Edges represent connections between videos

Identify Top K Most Influential Videos
Rank the K most influential videos based on their PageRank scores in descending order.

Data Analysis
Analyze the selected K influential videos to understand their characteristics 
Number of views, number of edges, category, and other attributes.

Discussion & Conclusion
Create visualizations to present the results effectively using graphs, charts, or plots to illustrate the relationships and trends discovered during analysis.

Report & Presentation
Create a PowerPoint presentation to communicate with the class the key findings and insights.
Construct a report / repository on GitHub to document the entire data mining process, including data collection, preprocessing, modeling, analysis, and conclusions.


Tech/Tools/Systems

The primary tool that we will need is Jupyter Notebook to keep track and build our code so that we do not have to manually replicate the data analysis and algorithm-building steps. Some libraries in Python that we will need are sknetwork, which will provide us the page rank algorithm we likely need. In addition, data analysis tools like Hadoop and Spark are likely needed to look at the data.


Implementation/Evaluation Plan

Learning How the Tools Work: Some of the tools are rather new to us and may take some time to figure out what they do and how they do it. For example, Hadoop and
Spark are new tools that we have not used and will require time to see how they work. This is in addition to the mathematics and theory behind the PageRank algorithm.

Data Summary: Look over the data and understand what each attribute of the data represents, the range of values, the meaning or encoding of the data, and the types of the data. We must also visualize the data and find potential outliers and consider why they are outliers.

Data Preprocessing: From the data, decisions need to be made in order to make the most of the data. Choosing useful attributes to analyze and performing dimensional reduction where necessary. All of these in preparation for the true analysis.

Data Analysis: We will use the tools in order to score each and every video inside our datasets for the PageRank algorithm. From these, we will sort the scores and videos associated with them and find which videos are incredibly influential. 

Data Conclusions: We will then look at how these videos compare to “non-influential” videos in order to find out why the algorithm selected them as “influential” (consider their attributes) and build a theory on how a video is more influential than another video. Once we make these conclusions, they become hypotheses. Testing Hypothesis: We can recreate these properties through manual test samples and figure out if what we have concluded are true or false.


Timeline and Milestones

Week 1-2 (By 10/15)
Learning how the tools work
Create GitHub Repository
Data Collection

Week 3-4 (By 10/29)
Data Preprocessing

Week 5-6 (By 11/12)
Data Modeling & Visualization
PageRank Algorithm
Identify K most influential videos

Week 7-8 (By 11/26)
Data Analysis & Conclusions
PowerPoint Presentation complete

Week 9 (Presentation Date: 11/30)
Practice Presentation
Present findings to the class
