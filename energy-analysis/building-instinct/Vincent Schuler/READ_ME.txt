Hi, here are some guidelines to run my solution.

Below is a brief description of the 3 notebooks provided.

To run inference, you just need to run the 3rd one (if you decide to use the test.csv file that I provided).
This test.csv file can also be generated by notebook n°1. This takes ~2h30.

# -----------------------------------------------------------
# Notebook n°1 : 1_Feature_extraction.ipynb
- Generates a df_train.csv and df_test.csv files.
- Only test.csv is mandatory to run inference.
- Note that you need to put the individual building test files in the "Files/building-instinct-test-data/" folder prior to execute the notebook (the same goes for the train files).


# -----------------------------------------------------------
# Notebook n°2 : 2_Training.ipynb
- Trains and saves models.
- Does not need to be run for inference.

# -----------------------------------------------------------
# Notebook n°3 : 3_Inference.ipynb
- Generates a submission.parquet files.
