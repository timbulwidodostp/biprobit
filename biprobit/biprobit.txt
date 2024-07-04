# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Bivariate Probit Regression model (models) Use biprobit With (In) R Software
install.packages("mets")
library("mets")
biprobit = read.csv("https://raw.githubusercontent.com/timbulwidodostp/biprobit/main/biprobit/biprobit.csv",sep = ";")
# Estimation Bivariate Probit Regression model (models) Use biprobit With (In) R Software
biprobit <- biprobit(cancer~1+zyg, ~1+zyg, data=biprobit, id="id")
summary(biprobit)
# Bivariate Probit Regression model (models) Use biprobit With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished