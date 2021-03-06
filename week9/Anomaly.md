##1.For which of the following problems would anomaly detection be a suitable algorithm?

From a large set of primary care patient records, identify individuals who might have unusual health conditions.(O)

Given a dataset of credit card transactions, identify unusual transactions to flag them as possibly fraudulent.(O)


##2.Suppose you have trained an anomaly detection system that flags anomalies when p(x) is less than ε, and you find on the cross-validation set that it has too many false positives (flagging too many things as anomalies). What should you do?

Decrease ε

##3.Suppose you are developing an anomaly detection system to catch manufacturing defects in airplane engines. You model uses
p(x)=∏nj=1p(xj;μj,σ2j).
You have two features x1 = vibration intensity, and x2 = heat generated. Both x1 and x2 take on values between 0 and 1 (and are strictly greater than 0), and for most "normal" engines you expect that x1≈x2. One of the suspected anomalies is that a flawed engine may vibrate very intensely even without generating much heat (large x1, small x2), even though the particular values of x1 and x2 may not fall outside their typical ranges of values. What additional feature x3 should you create to capture these types of anomalies:

x3=x1/x2

##4.Which of the following are true? Check all that apply.

When choosing features for an anomaly detection system, it is a good idea to look for features that take on unusually large or small values for (mainly the) anomalous examples.

If you do not have any labeled data (or if all your data has label y=0), then is is still possible to learn p(x), but it may be harder to evaluate the system or choose a good value of ϵ.



##5.You have a 1-D dataset {x(1),…,x(m)} and you want to detect outliers in the dataset. You first plot the dataset and it looks like this:

μ1=−3,σ21=4


