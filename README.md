# PororoQA

##### Authors: Kyung-Min Kim, Min-Oh Heo, Seong-Ho Choi, and Byoung-Tak Zhang (Seoul National University & Surromind Robotics)
##### Paper1: DeepStory: Video Story QA by Deep Embedded Memory Networks (https://arxiv.org/abs/1707.00836) (IJCAI 2017)
##### Paper2: PororoQA: A Cartoon Video Series Dataset for Story Understanding (NIPS 2016 Workshop on Large Scale Computer Vision System, 2016)

You can download the whole video clips with the fowlloing url.
http://147.46.215.100:5000/sharing/MrDZ9H6ro

## Why cartoon video seires?
Characteristic of “Pororo”, children's cartoon video series
* Easy sentence
* A simple story structure
  * One episode: Avg. 7.2 min. 
  * Similar events are repeated
* Small environments
  * The size of dictionary: 3,729
  * The number of characters: 13
* It may be **appropriate as a test bed for video story QA problem**

## Data Statistics - QAs
* 8,834  QA pairs
* Remove 'ambiguous', 'unrelated' questions that do not follow guidelines
* Average QA count per episode : 51.66
* Examples and statistics by type of question
![Alt text](/images/PororoQA_stat_qtype.png)
* Statistics about questions based on answer types
![Alt text](/images/q_types.png)
* Average number of words in our dataset depend on the first word in the question
![Alt text](/images/Average_QA_words.png)
* Comparison of various public datasets in terms of video story analysis
![Alt text](/images/PororoQA_stat_comparison.png)

## Data Statistics – Scene Descriptions
* 27,328 scene descriptions
  * Average sentence / word count per scene description : 1.7 / 13.6
