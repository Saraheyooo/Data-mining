# Data mining_Exam 1
20211209


Question 1

Train a topic model on the description column in framing.p. Describe and explain your pre-processing steps and parameters.
Choose two news media from the column netloc (e.g. vox.com and breit- bart.com) that are relevant to compare and explain your choice. Compare the topic proportions between those two news media. Try to explain your results, also given what you know about how the data set is constructed.


======================================================================================

Question 2

Choose two shows from discussions.p and compare the gender bias in the discussions on both shows. Explain why the two shows you choose are relevant to compare in this context and formulate a hypothesis.
Train two word embeddings models (one for each show). Compile a list of male and female related words that you deem relevant for your corpus and compare the gender biases between the discussions on the two shows you choose, using the method of the paper by Wevers. Interpret the results, relate them to your hypothesis, and discuss whether your results say something about the shows themselves or about the discussions on these shows.
For your reference, the columns in word_cats.p represent the following cate- gories:
• affect: Affect
• posemo: Positive emotions
• negemo: Negative emotions
• social: Social
• family: Family
• cogproc: Cognitive Processes • percept: Perceptual Processes • body: Body
• work: Word
• leisure: Leisure
• money: Money
• relig: Religion
• occupation: Occupation

======================================================================================



Question 3

A record producer has approached you with the question of whether there are any distinguishable features of a pop song. In other words: what sets a pop song (lyrically) apart from other genres?
Try to formulate a good operationalization of this question (how are you going to quantify this, what method do you use, what steps do you need to take, what time period are you focusing on) using the methods we discussed in the last three weeks (you are free to choose one!), and argue why this operational- ization would be suitable to formulate an answer to the question of the record producer.
Implement your operationalization using the dataset from exercise 3.1 and formulate an answer to the question of the record producer.
After that, consider the following new lyrics provided by our hypothetical producer:

*The sky breaks open and the rain falls down
Oh, and the pain is blinding
But we carry on...
Seems like the end of everything
When the one you love
Turns their back on you
And the whole world falls down on you...
It's the end of the world
It's the end of the world
Well, I'm holding on...
But the world keeps dragging me down...
It's the end of the world
It's the end of the world
Well, I'm holding on...
But the world keeps dragging me down...
I got my heart on lockdown
And my eyes on the lookout
But I just know that I'm
Never gonna win this
They can keep the lights on
They can keep the music loud
I don't need anything
When I got my music
And I'm holding on...
The sky breaks open and the rain falls down
And the pain is blinding
But we carry on
(They tell you lies)
I'm holding on...
(They tell you lies)*


Based on (the results) of your method, to what extent could you say whether this is a ”classic” pop song or not? Explain your answer (in a data-driven way) and try to refer both to your results and to the lyrics itself.
