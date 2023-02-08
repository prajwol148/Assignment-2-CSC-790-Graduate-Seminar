# Assignment-2-CSC-790-Graduate-Seminar
This is the second assignment for Dr. Santosh KC's CSC 790: Graduate Seminar course.
<br>
[Click to view Paper 1]()
[Click to view Paper 1]()
<br>

## 1) Discuss the following (paper 1):
#### a. Motivation
#### b. Problem
#### c. Methodology
#### d. Data and results
#### e. Take home message
#### f. Scalability and generalizability of the method
<br>
### Answer: 
Paper 1 is the original scientific research paper. It is trying to implement Inductive Learning Programming (ILP). The study is referred to as a first step in the authors' attempt to employ ILP uniquely to automatically acquire intricate descriptions of symbols. This implies that the writers are engaged in original research and working on the new concept.

### A=> 
The primary motivation of this research, according to the first paragraphs of both the introduction and the abstract sections, is to reduce inefficiency in the pattern or symbol identification. The author's motivation is to improve the process of symbol identification, which is based on symbol appearance. The author wishes to replace the method with a more semantic and meaningful process of symbol comprehension. In the process, the author intends to employ ILP. The author intends to improve the process by using ILP to automatically learn complex descriptions of symbols from a formal description.

### B=> 
According to the study report, the conventional approach of symbol identification does not produce particularly effective results since it is difficult to take into consideration non-trivial symbol descriptions. The issue is that the minute elements and their details in the image are generally disconnected from the main concept of what it represents which can generate wrong results.
This study aims to find a new way to identify symbols by automatically learning their complex descriptions through ILP. The hope is that this new approach will lead to a more accurate and semantically linked recognition process.

### C=> 
This study's methodology is highly fascinating and distinctive. The author has noted that the strategy employed is to extract complicated structures that may be discovered in the image and develop a vocabulary out of them, rather than employing the existing sets of rules to recognize the shapes or symbols. Based on earlier research, the technique already has a set of local structures. They already have tools built to locate forms and symbols, which they use as shape detectors for circles, aligned corners, rectangles, and so on.
Following the extraction process, they look for the location of the shapes and study how the shapes are positioned concerning one another. For example, they can consider whether the square extracted from the symbol is on the right side or the left side of a straight line which is also extracted from the symbol. The way of describing the position of the shapes is very familiar to how we would describe it in our natural language. After this is done, based on first-order logic, the shapes are then described, and their types are distinguished based on the vocabulary they have based on previous research.

### D=> 
Any research project's dataset is essential from every perspective since the outcomes rely on it. Datasets of electrical graphical symbols were employed by the author for this research project. The dataset, which originates from a database of electrical wire components, is then represented using first-order logic language.
ILP tends to give out negative and positive examples based on the set of rules which are created to analyze the dataset. Generally, there ought to be only one rule which accounts for every positive and negative example. However, it can also create multiple rules which are based on the dataset. The author has chosen symbols 255_2 and 226_2 from figure number 1 and the ILP solver is implemented on the dataset. The result is a single rule that gave negative and positive examples.  
Likewise, in the paper, the author first considered images {195_2, 198_2, 199_2, 200_2, 207_2, 208_2} as a positive example. The ILP translated the experiment into natural language and the result is only one rule to classify positive and negative examples. It is so because all positive examples are covered, and no negative examples are covered. In this case, the rule is a perfect match to the dataset taken. The result showed that the chosen image set contains circles, and all circles have a northwest corner element. Thus, all positive examples are distinguished from negative ones with a single rule. 
The author again performed another test on another set of symbols extracted from the images {180_1, 180_3, 184_1, 185_1, 185_3, 186_2} from figure 1. However, the system was not able to complete the experiment with just a single rule as a result. Multiple sub-classes were created for the positive examples that remained from the previous predicates. Each sub-classes also have separate rules. 
Thus, the learning that we can draw from the experiment can also be stated that the ILP can create a single rule if a dataset is easy and simple to work with and if it can be described by a single and clear rule. However, if the dataset is complex then ILP tends to create multiple rules for multiple patterns to describe various aspects of the data. 

### E=> 
This research paper is an original scientific research paper and the author has tried using a new approach for the recognition of symbols discarding the traditional method in which established sets of rules were used to detect the shapes or symbols. The method that the author has approached and has used extract complex structures that can be found in the image and build a vocabulary out of it. The method already has a set of local structures based on previous research. The approach can recognize the shapes in a more meaningful way. 
The advantage of this method that the author has suggested is that the machine can be more intelligent because the algorithm can pick up on visual concepts without human guidance. It will allow the system to not just consider the shapes and symbols from the dataset, but the system can also extract the information such as text, and build its result upon it. However, the author acknowledges that the method is still far from perfect because of the limited sets of the content of the vocabulary. However, the author seems determined to keep on improving the methodology by improving the vocabulary by expanding the language and adding additional numerical descriptions.

### F=> 
The author says that the method they're using to recognize symbols and represent them has a limit. It can only work with a limited number of symbols in its vocabulary. To make the method work better and be able to recognize more symbols, the vocabulary needs to be expanded.
The algorithm that creates the rules for recognizing symbols needs to be improved so that it can accurately tell the difference or classify the good examples and bad examples. The author thinks that this can be done easily because there are already resources available for analyzing images.
Additionally, the author wants to include more information about the symbols' shapes by using numbers and statistics. This will require more work, but it will make the method even better at recognizing symbols.
<br>
<br>
## 2) Write abstracts from both papers (paper 1 and paper 2).
### Abstract for Paper 1:
	Machine learning has significantly improved in recognizing symbols, because of the current research works that are happening in the fields of Artificial Intelligence. Machine learning methods are often employed for symbol recognition tasks, including musical symbol recognition, pattern matching, and handwritten character recognition. But there are several issues with the approach that is currently being employed. This paper proposes the use of an approach known as Inductive Logic Programming (ILP), which uses first-order logic to represent hypotheses and data, to automatically learn nontrivial descriptions of symbols, based on a formal description, and be used for symbol recognition. This approach is motivated by the fact that unsupervised learning can be more effective than supervised learning methods. To validate our concept, we employ datasets of electrical graphical symbols represented using our first-order logic vocabulary. The suggested model is a first step in that direction and more of a proof-of-concept than a completely functional framework. To the best of our knowledge, the results obtained thus far are extremely efficient, but the efficiency and accuracy of the model may still be improvised by improving the vocabulary by expanding the language and adding additional numerical descriptions. This proves the viability of using ILP for symbol recognition.
<br>
### Abstract for Paper 2:
	Computer vision's topic of object recognition is exciting since it pushes the limits of what is conceivable through image analysis. To fully realize the potential of appearance-based object identification, feature/descriptor extraction, and matching are essential. However, the problem of recognizing objects in cluttered or textured environments has proven to be a bit difficult. Current methods struggle to extract stable and distinguishable features, leading to less accurate feature matching for line-rich color scenes/objects such as cars, buildings, and faces and ultimately underperforming object recognition algorithms. This research suggests using a novel descriptor, RSILC (Rotation- and Scale-Invariant, Line-based Color-aware descriptor), for object identification tasks to address these problems. To extract robust features, RSILC makes use of a special mix of line-based features and color information, even in congested or textured settings. It is particularly well suited for face-matching applications, where standard descriptors often struggle with changes in pose and size, thanks to its rotation and scale invariance. Our tests show that RSILC is more effective than currently used generic descriptions. The findings demonstrate that, especially in congested or textured surroundings, RSILC surpasses these descriptors in terms of accuracy and efficiency. The outstanding performance of RSILC demonstrates its potential as a formidable tool for object recognition.



.

