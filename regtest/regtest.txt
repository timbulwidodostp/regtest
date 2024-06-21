# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Regression Test for Funnel Plot Asymmetry Use regtest With (In) R Software
install.packages("metafor")
library("metafor")
regtest = read.csv("https://raw.githubusercontent.com/timbulwidodostp/regtest/main/regtest/regtest.csv",sep = ";")
# Estimation Regression Test for Funnel Plot Asymmetry Use regtest With (In) R Software
regtest_rma <- rma(yi, vi, data=regtest)
summary(regtest_rma)
regtest_ml <- regtest(regtest_rma, model="lm")
regtest_ml
result_regtest <- regtest(regtest_rma)
result_regtest
# Regression Test for Funnel Plot Asymmetry Use regtest With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished