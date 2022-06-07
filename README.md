# Multi-Output-Neural-Network-on-Large-Data
Estimating a multi-output feed-forward neural network on data that is larger than what can be held in a typical computer ’s RAM


Goal
The data comes from Amazon, and the category is specified by the seller of the product. The seller selects categories from a list, but there is also an ‘other’ category. When the ‘other’ category is selected the seller has tocreate the category. This makes it a challenging task to detect incorrect categories. The goal in this assignment is to predict which categories a product belongs to based on its title. To clean up the categories assigned to a product we will then retain the top five categories (i.e., the five categories with the highest probability). If the model is accurate, the result will be that categories will be correct (in case a wrong category was selected from the list), and that the categories that were created but not useful (e.g., those that have typographical errors, or are
inappropriate) will be filtered out.
