Okay, let's start with supervised learning.
And I suppose I have some historic data about some health
trials participants, and I have got the exercise they have
taken and the number of calories they have spent and so on.
And I might want to explore how I would use machine learning to
predict how many calories a new participants
might be expected to burn while engaging in some exercises.
When we need to predict a numeric value, like an amount
of money or a temperature or the number of calories, then what we
use is a supervised learning technique called regression.
For example,
let's suppose Rosy here is a participant in our health study.
Here she is taking some exercise.
Now we gathered some data about Rosy when
she first signed up for the study.
And while she's exercising,
we'll capture more data using a fitness monitor.
Now what we wanna do is model the calories burned
using the features we have for Rosy's exercise.
Her age, weight, heart rate, duration, and so on.
And in this case, we know all of the features and
we know the label value of 231 calories.
So we need our algorithm to learn the function that operates
of all of Rosy's exercise features to give us a result of
231.
Now of course a sample of only one person isn't likely to give
us a function that generalizes well.
So what we do, is gather the same sort of data
from lots of diverse participants and
train our model based on this larger set of data.
After we've trained the model and
we have a generalized function that can be used to calculate
our label Y, we can then plot the values of Y, calculated for
specific features of X values on a chart like this.
And of course, we can interpolate any new values of
X to predict and unknown Y.
Now because we started with data that includes the label we
are trying to predict,
we can train the model using only some of the data.
And withhold the rest of the data for
evaluating model performance.
Then we can use the model to predict f of x for
evaluation data.
And compare the predictions or
scored labels to the actual labels that we know to be true.
The difference between the predicted and
actual levels are what we call the residuals.
And they can tell us something about the level of
error in the model.
Now there are a few ways we can measure the error in the model,
and these include root-mean-square error, or RMSE,
and mean absolute error.
Now both of these are absolute measures of error in the model.
For example, an RMSE value of 5 would mean that the standard
deviation of error from our test error is 5 calories.
Of course absolute values can vary wildly depending on what
your predicting.
It's an error of 5
calories would seem to indicate a reasonably good model.
But if we were predicting how long an exercise session takes
an error of 5 hours would indicate a very bad model.
So you might want to evaluate the model using relative metrics
to indicate a more general level of error as a relative value
between 0 and 1.
Relative absolute error and relative squared error produce
a metric where the closer to 0 the error, the better the model.
And the coefficient of determination, which we
sometimes call R squared, is another relative metric, but
this time a value closer to 1 indicates a good fit for
the model.
