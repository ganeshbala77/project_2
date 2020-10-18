X] README.md included
[X] Slides included
[X] Code included

## Clean Code:

- Code follows PEP-8
- Very readable and easy to follow
- Create a separate notebook or file for scraping and another for cleaning your data. For future projects try creating functions. These functions can then be 
  placed in py files. Then you can call the function from your jupyter notebook. 


## Good Documentation:

- In your README.md, provide a clear scope and analysis, methodology, data science methods used, and summary of your findings. 
- Use markdown cell at beginning of .ipynb explains scope and analyis
- Use Inline code comments more. Your workflow is clear but it is best practice to comment so you and the reader/audience understands the code. 
- Could use more markdown cells throughout as section headings and explaining decisions made

## Proper Data Science:

- Clarity on Train, validate, test (I remember from lecture you interchanging validate and test). Below is the clear documentation for the split
 X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=1)
 X_train, X_val, y_train, y_val = train_test_split(X_train, y_train, test_size=0.25, random_state=1)
- Nice visualizations but speak more about them in your code
- Post bootcamp, try working through other models (Lasso & Ridge) and tuning hyperparameter. This is great for practice.
- Reminder-if features are on different scales, you must scale in order to be able to interpret coefficients. 



## Comments:

- Good job, simple and clear project 2 :)
- Be sure to comment more on your code. Commenting gives the reader the sense that you did not simply copy and paste your code.
