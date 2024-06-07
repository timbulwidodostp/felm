# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit (Fitting) a linear model with multiple group fixed effects Use felm With (In) R Software
install.packages("lfe")
library("lfe")
felm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/felm/main/felm/felm.csv",sep = ";")
# Estimate Fit (Fitting) a linear model with multiple group fixed effects Use felm With (In) R Software
felm <- felm(Dependen ~ Indenpenden_1 + Indenpenden_2 | Id + Firm, data = felm)
summary(felm)
# Fit (Fitting) a linear model with multiple group fixed effects Use felm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished