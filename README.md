# python-marketing-conversion-analysis-95
import pandas as pd,matplotlib.pyplot as plt d={"Channel":["Email","Social","Ads"],"Leads":[500,800,600],"Sales":[50,120,90]} df=pd.DataFrame(d) df["CR"]=(df.Sales/df.Leads)*100 print(df) plt.bar(df.Channel,df.CR) plt.show()
