# TH-Segment

How to use/Install program
1. Extract file in drive C:

2. Access the extracted folder and Click the file SETUP to set up the program.
2.1 You can change the dictionary if you have the better one (must be .txt file and each word be in each line). To change dictionary, drag your dictionary file and drop in the folder. Rename your dictionary to 'Thaidictionary.txt'.

3. Get into the file name's 'word segmentation' to access the program.

4. Type your sentence in the input section.

5. Click 'Generate'.

6. The output will appear on the right side. In case that some word of your sentence doesn't have in the dictionary or typing a typo, the output will appear as 'ERROR SENTENCE(#&#;#:#€#*#;#^)'.


The things that be improved
1. Inputting Number
	We fixed the problem from the last time that it will be error when input the number. Right now we can input the number normally.
2. Spacing
	From the last time, it was error when we put in the space. But now we can input it as much as want.
3. Multiple-line inputting
	From the last time, our code can be able to input only one line at a time. Now we can input more than 1 line at a time.
4. Catching the error in sentence.
	If in the sentence that we input has any word that didn’t be in the dictionary, it will show up the error message.
	In case that we input more than 1 sentence and each sentence were separated to each other. Although there was 1 sentence that has an unknown word, another sentence will still be able to show normally.



The things that will be improved for the next update
1. Interface
	We will try to design better interface.
2. Adding “browse” button
	To insert the input in file .txt
3. Algorithm
	As usual, we separate the word by using longest matching. For the next time, we will use maximum matching and n-gram / vector matching.
4. Update Dictionary
	Our dictionary still has a number of word that is not much. So we will add more to have a variety of word.
5. Special word
	We will try to catch up for the special word such as number symbol (-, +, etc.), acronym.
6. Timer
	We will add a timer to check the time that is used for each algorithm in case that there are more than 1 algorithm.
