# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Inferring causal impact using structural time-series models Use CausalImpact With (In) R Software
install.packages("CausalImpact")
library("CausalImpact")
CausalImpact = read.csv("https://raw.githubusercontent.com/timbulwidodostp/CausalImpact/main/CausalImpact/CausalImpact.csv",sep = ";")
# Estimation Inferring causal impact using structural time-series models Use CausalImpact With (In) R Software
pre.period <- c(1, 40)
post.period <- c(41, 52)
CausalImpact <- CausalImpact(CausalImpact, pre.period, post.period)
summary(CausalImpact)
plot(CausalImpact)
# Inferring causal impact using structural time-series models Use CausalImpact With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished