# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Logistic Regressions with Misclassification Correction Use logistic4p With (In) R Software
install.packages("logistic4p")
library("logistic4p")
# Estimate Logistic Regressions with Misclassification Correction Use logistic4p With (In) R Software
logistic4p = read.csv("https://raw.githubusercontent.com/timbulwidodostp/logistic4p/main/logistic4p/logistic4p.csv",sep = ";")
y = logistic4p[, 1]
x = logistic4p[, -1]
y_ = logistic4p[, 2]
x_ = logistic4p[, -2]
logistic4p = logistic4p(x, y)
logistic4p_ = logistic4p(x_, y_)
logistic4p
logistic4p_
# Logistic Regressions with Misclassification Correction Use logistic4p With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished