# commrate
A project written using Python, which evaluates the positiveness or negativity of the written comment on a scale from 1 to 5.


# Commrate with Jamshid Ahmadov
**A project written using Python, which evaluates the positiveness or negativity of the written comment on a scale from 1 to 5.**
<br>
<br>
Why exactly is the project:
This project can be added to the comment section of any online store. The program can automatically evaluate the comment. 5-most positive, 1-most negative. The correct model is working with some errors. Our future plans: Taking our idea public and customizing this model for any language. Currently, the model works only in Russian.
<br>
<br>

1. Imports necessary libraries for data manipulation, feature extraction, model training, and evaluation.
<br>
2. Reads a CSV file named "train.csv" and selects two columns: 'comment' and 'reting'.
<br>
3. Renames the 'reting' column to 'rating'.
<br>
4. Converts the 'rating' column to numeric values and filters the DataFrame to only include rows with ratings between 1.0 and 5.0.
<br>
5. Groups the DataFrame by 'rating' and randomly samples an equal number of rows from each group to ensure balanced classes.
<br>
6. Preprocesses the 'comment' column by converting it to lowercase and removing punctuation and non-alphabetic characters.
<br>
7. Splits the preprocessed data into training and testing sets using a 90/10 split.
<br>
8. Trains a LightGBM classifier model on the training data.
<br>
9. Evaluates the model's accuracy on the testing data.
<br>
10. Creates and displays a confusion matrix to visualize the model's performance on each class.

<br>
<br>
<br>

![image](https://github.com/jamshid-ds/Commrate/assets/117648241/d5d20318-b7d4-466c-8ab6-7419054d80ce)

<br>
<br>
Technologies which used:
<br>
<br>
-Python
<br>
-LightGBM
<br>
-Matplotlib and Seaborn (for visualisation)
<br>
-Pandas and Numpy
