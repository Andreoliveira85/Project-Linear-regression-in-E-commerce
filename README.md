# Project-Linear-regression-in-E-commerce

# Project description:

Some Ecommerce company based in New York City sells clothing online but also has in-store style and clothing advice sessions. 
Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app 
or website for the clothes they want. The company is trying to decide whether to focus their efforts on their mobile app experience or their website. We use linear 
regression in order to quantify the linear dependence of the target variable "yearly amount spent" that captures the investment done in terms of the other variables
of the dataset. The score (Adjusted R2) is incredibly high 98% in the train and test set (with 20% size for the validation dataset). We also perform regularization
of the model (that in this case is not highly required since there is no overfitting in the model). Lasso regularization performs for the hyper parameter 1 a slight 
underfitting (Score on the train set : 0.981235530537366 vs Score on the test set : 0.9787641440205315) and the best performance for Ridge regularization on the model
is the vanishing coefficient 0 reducing it to the clasical linear regression model that we built in the first try.

## Code and resources used:
**Python version:** 3.7

**Libraries/packages used:** pandas, numpy, matplotlib, seaborn, scikitlearn.

**Dataset:** available at the repo.

