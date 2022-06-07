# Multi-Output-Neural-Network-on-Large-Data
Estimating a multi-output feed-forward neural network on data that is larger than what can be held in a typical computer ’s RAM


## Project Goal
The data comes from Amazon, and the category is specified by the seller of the product. The seller selects categories from a list, but there is also an ‘other’ category. When the ‘other’ category is selected the seller has tocreate the category. This makes it a challenging task to detect incorrect categories. The goal in this assignment is to predict which categories a product belongs to based on its title. To clean up the categories assigned to a product we will then retain the top five categories (i.e., the five categories with the highest probability). If the model is accurate, the result will be that categories will be correct (in case a wrong category was selected from the list), and that the categories that were created but not useful (e.g., those that have typographical errors, or are
inappropriate) will be filtered out.

# Process
## 1: PREPARE DUMMY VECTOR STRUCTURE
        
Cycle through all the data once to get all the unique words and count how many times they occur.
We will later remove words that appear few times. What is the cut off to remove items? However many items your RAM can handle.
If there are categories present in all items, I removed them to help the model learn more accurately.

## 2: Train Model

## 3: Track Performance
How many categories within the top 5 highest probabilities are seen in the testing observation?

## 4: Follow-up:
###### Variable Importance
###### Partial Dependency Plot
