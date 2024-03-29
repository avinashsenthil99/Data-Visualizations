# Argumentative Visualization

You can view my work at: https://avinash-argumentative-visualization.netlify.app/

In this homework, you will create a pair of data visualizations that argue for opposing viewpoints, using the same base dataset.

Your completed submission should include the following files:
* `index.html`: The webpage with the visualizations.
* `data/`: The folder containing your dataset file(s).
* Any other necessary files like CSS, JS, etc.

(If your dataset is larger than 10 MB, please only extract the portions needed for the visualizations.)

## Design requirements

Using techniques from the Storytelling lecture and the [visualization rhetoric paper](http://users.eecs.northwestern.edu/~jhullman/vis_rhetoric.pdf), you will create two visualizations about a dataset that frame the data with opposite narratives.

First, find a dataset about a "controversial" topic. In other words, you want a topic with strong opinions on both sides of the issue. Here are some examples of topics that could work: a political issue, science, religion, sociocultural, economics, immigration, sports, climate change, geopolitical sovereignty, etc. Topics from other regions or countries are also allowed. Good places to look for this data include Kaggle and news organizations that provide access to their data (538, New York Times, etc.).

> **COVID-19 datasets** are NOT allowed, though, you are free to look at examples of opposing COVID visualizations for inspiration.

Next, create your `index.html` page with two visualizations placed side-by-side (one on the left, one on the right). The two visualizations should use the same base dataset. Not all attributes are required to be the the same, and you are free to preprocess the data differently for each visualization (if desired), including aggregating data, filtering data, etc. but use the same source must be used. (In other words, you cannot go find two datasts and merge them together.) One visualization should be rhetorically framed to argue "in support" of a viewpoint, and the other visualization should be rhetorically framed to argue against the viewpoint. 

> 🔍 A good way to consider this is that these two visualizations are two opposite answers to a question. The left-visualization can support the "Yes" answer, and the right-visualization supports the opposite "No" answer.

Again, the trick is that you will use the _same base dataset_ for both visualizations, and you'll employ rhetorical techniques to help frame the data in opposing ways. Some examples of how you might do this include: filtering some of the data, picking different attributes to show, using diffrent ranges (timescales, etc), using different granularities, clustering or binning the data, using text annotating on the charts, picking colors or channels to emphasize some aspect of the data. You're allowed to pre-process the data or break up the data into multiple files if necessary. 

[This paper on visualization rhetoric](http://users.eecs.northwestern.edu/~jhullman/vis_rhetoric.pdf) describes an extensive collection of framing and styling techniques you can use to help frame a visualization to promote a specific viewpoint, story, or argument. You can also the lecture slides for ideas of specific rhetorical techniques. Your frame of mind if you choose this option should be like a debate: one team argues the affirmative position, while the other argues the negative. For this assigment, you'll argue both sides. You are free to use any visualization techniques and rhetorical framing devices you like, but you should only create ONE main visualization for each side. (In other words, don’t make a collection of several charts to argue Yes or No, just have one for each side. However, it’s okay to inset or annotate a smaller chart within your primary chart.)

Above the charts, add a title (or question) that describes the debate topic, and provide a link to the dataset source. At the bottom of each chart, providing a brief title or caption about each chart. Then, below that, provide the following paragraphs.

* Introduce the topic: Provide a brief (3-4 sentence) description of the chosen topic. In other words, if I'm not familiar with the topic, introduce it here. If you'd like, you may state your personal position on the topic, though that's not required.
* Left chart: Describe the argument of the left chart, and describe the rhetorical techniques you are using in this chart. You should explicitly reference techniques from the lecture/paper.
* Right chart: Provide a similar writeup for the right chart.

## Grading 

This assignment is worth 10 points. Be sure to organize and lay out your page nicely, with nicely styled elements. Up to +2 bonus points will be considered for submissions that go above and beyond (e.g., creating particularly compelling or impressive argumentative visualizations).

> ❗️ In previous years, students have posted this assignment as a part of their portfolio. While we cannot prohibit you from reviewing such charts, you are not allowed to use their code, and we highly recommend not even looking at these until you submitted the assignment. Copying someone else's code/arguments is considered plagiarism.
