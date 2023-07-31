## Modeling For Home-Credit

### Introduction (Summary of business problem and project objective)

Home Credit is a multinational financial institution that specializes in providing loans to individuals with inadequate credit history. They aim to promote financial inclusion by offering accessible financial services to underprivileged populations. Home Credit develops creative financing solutions by using non-traditional data sources and other alternative techniques to evaluate creditworthiness. Their customer-centric approach and fast, convenient lending process empower individuals to make important purchases and build a positive credit history. Home Credit reduces the risks involved with lending to borrowers with spotty credit histories by using advanced risk management models. Overall, they strive to democratize access to financial services and create a positive social impact.

This notebook will walk you through the data available and how that data is used to train a model which Home Credit will then use to predict if a future applicant will default on their loan or not.


### Installation

###**How did trying different models help?**

Trying many models gave us a thorough understanding of their advantages, disadvantages, and performance on the work at hand. It contributed in selecting the best model, maximising performance, comprehending the significance of features, evaluating robustness, and utilising model diversity to enhance predictions and gather insightful information.

**Selecting the right model for the job:** As this is a classification issue and there are numerous of classification models to choose from, we selected this as our starting point. We tried default decision trees, Random Forest, and a few different varients of Gradient Boosting Machine.

**Performance Comparison:** Comparing performances of various models enables you to choose the one that performs the best. Along with which we also took into consideration the Kaggle score as guided to move forward with the best model based on it's Kaggle score. Random Forest and Gradient Boosting Machine models performed much better than the default decision tree model; however, there were some overfitting issues that we had to correct for. While Random Forest and our Gradient Boosting Machine models were similar, we moved forward with a Gradient Boosting Machine model given its advantage of how quickly it can train the model.

**Questions when testing different models:** We asked ourselves a variety of questions to help use decide which model to use.



*   Different models draw attention to different key characteristics. Does our selected model fail to draw attention to important key characteristics that we need to include?
*   Is our model robust? Could Home Credit train a new model using our work if they had additional new train data?
*   Do other models show patterns or insights that our model doesn't? If yes, is it worth finding a way to include these in our model?
*   Is our selected model a current industry standard? If not, did we review current industry standard models to ensure that we tried various model options?


### My Contribution

We worked as a team on Google Colab and completed the modeling process and compiling different code chunks into one single notebook using python packages.
**Venkatachalam Kapuganti:** Worked on data cleaning, outliers identification and removal, data files merger, encoding and normalisation. By using raw as well as normalised data, created logistic regression model and randomforest model.

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Roadmap

See the [open issues](https://github.com/evanca/quick-portfolio/issues) for a list of proposed features (and known issues).
___

### References

[1] Jekyll theme "Minimal" for GitHub Pages: https://github.com/pages-themes/minimal (CC0 1.0 Universal License)
<br>[2] Dummy photo via: https://pixabay.com/photos/man-male-adult-person-caucasian-1209494/ (Pixabay License)
<br>[3] Dummy thumbnail image created by rawpixel.com: https://www.freepik.com/free-vector/set-elements-infographic_2807573.htm (Standard Freepik License)
