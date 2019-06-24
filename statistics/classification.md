
So we've seen how to train
a regression model to predict a numeric value.
Now it's time to look at another kind of supervised learning,
classification.
Classification is a technique that we can use to predict which
class, or category, something belongs to.
The simplest variant of this is binary classification where we
predict whether an entity belongs to one of two classes.
It's often used to determine if something is true or
false about the entity.
For example,
suppose we take a number of patients in our health clinic,
and we gather some personal details, and run some tests, and
we can identify which patients are diabetic and which are not.
We can learn a function that can be applied to these patient
features and give the result 1 for
patients that are diabetic, and 0 for patients that aren't.
More generally, a binary classifier is a function that
can be applied to features X to produce a Y value of 1 or 0.
Now, the function won't actually calculate an absolute value
of 1 or 0, it will calculate a value between 1 and 0,
and we'll use a threshold value
to decide whether the result should be counted as a 1 or a 0.
When you use the model to predict values,
the resulting value is classed as a 1 or
a 0 depending on which side of the threshold line it falls.
Because classification is a supervised learning technique,
we withhold some of the test data to validate the model
using known labels.
Cases where the model predicts a 1 for a test observation that
actually has a value, a label value of 1, are considered true
positives, and similarly cases where the model predicts 0, and
the actual label is 0, are true negatives.
If the model predicts 1, but the actual label is 0,
well that's a false positive, and if the model predicts 0,
but the actual value is 1, well that's a false negative.
Now the choice of threshold determines how predictions
are assigned to classes.
In some cases, a predicted value might be very close to
the threshold, but is still misclassified.
You can move the threshold to control how the predicted values
are classified.
In the case of the diabetes model,
it might be better to have more false positives, but
reduce the number of false negatives, so
that more people who are at risk of diabetes get identified, and
the number of true positives, false positives, true negatives,
and false negative, produced by your model,
is crucial in evaluating its effectiveness.
The kinds of these are often shown in what's
called a confusion matrix, and this provides the basis for
calculating performance metrics for the classifier.
The simplest metric is accuracy,
which is just the number of correctly classified cases
divided by the total number of cases.
In this case there are five true positives and
four true negatives, and there are also two false positives and
no false negatives.
That gives us nine correct predictions out of a total of
11, which is an accuracy of 0.82, or 82%.
Now that might seem like a really good result, but
perhaps surprisingly, accuracy actually isn't all that
useful as a measure of a model's performance.
Suppose that only 3% of the population is diabetic.
I can create a model that simply always predicts zero and
it would be 97% accurate, but it's completely useless for
identifying potential diabetics.
A more useful metric might be the fraction of cases classified
as positive that are actually positive.
This metric's known as precision.
In other words, out of all the cases classified as positives,
which ones are true and not false alarms?
In this case, there are five true positives, and
two false positives.
So our precision is 5 / (7), which is 0.71 or
71% of our cases identified as positive really are diabetic,
and 29% are false alarms.
In some situations we might want a metric that's sensitive to
the fraction of positive cases we correctly identify, and
we call this recall.
It's calculated as the number of true positives divided by
the combined true positives and false negatives.
In other words,
what fraction of positive cases are correctly identified?
In this case, there are five true positives and
no false negatives.
So our recall is five out of five, which is of course one,
or 100%.
So in this case we're correctly identifying all patients
with diabetes.
Now recall actually has another name, sometimes it's known as
the True Positive Rate, and there's an equivalent rate for
false positives, compared to the actual number of negatives.
In this case, we have 2 false positives and 4 true negatives.
So our false positive rate is 2/(6), which is 0.33.
Now you may remember that the metrics we got were based on
a threshold of around 0.3, and we can plot the true positive
rate against the false positive rate for
that threshold like this.
If we were to move the threshold back to 0.5,
our true positive rate becomes 4 out of 5, or 0.8 and our false
positive rate is 1 out of 6, or 0.16, which we can plot here.
Moving the threshold further to say 0.7,
gives us a true positive rate of 2 out of 5,
or a 0.4, and a false positive rate of 0 out of 6 or 0,
and if we plotted this for every possible threshold rate,
we would end up with a curved line that looks like this.
Now this is known as a receiver operator characteristic,
a ROC chart.
Now the area under the curve, or AUC,
as we call it, is an indication of how well the model predicts.
Generally, you wanna see a large AUC with a curve staying as
close as possible to the top left corner of the chart.
A perfect classifier would go straight up the left and
then along the top, giving an AUC of one.
Now, you can always compare with a diagonal line, and
that represents how well the model would perform if you
simply made a 50-50 guess.
It's an AUC of 0.5.
So you're just simply random guessing 50% of the time true,
50% false.
In this case, our model has an AUC of 0.9.
So, it's definitely outperforming guessing.

