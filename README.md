import pandas as pd 
df= pd.read_cvs("employeedata.cvs")
df=pd.read_excel("employeedata.xls")
df.loc[0,'Email Address']='asinabdou@helpinghamds.cm'
df.loc[1,'Email Address']='larbaavaika@helpinghamds.cm'
df.loc[2,'Email Address']='tchabatidriss@helpinghamds.cm'
df.loc[3,'Email Address']='anababoris@helpinghamds.cm'
df.loc[4,'Email Address']='mengueblaise@helpinghamds.cm'
df.loc[5,'Email Address']='temgouarucel@helpinghamds.cm'
df.loc[6,'Email Address']='mekuloedimo@helpinghamds.cm'
df.loc[7,'Email Address']='essoloserena@helpinghamds.cm'
df.loc[8,'Email Address']='djoueric@helpinghamds.cm'
df.loc[9,'Email Address']='fankamfrancesca@helpinghamds.cm'
df.loc[10,'Email Address']='bilonfrankbell@helpinghamds.cm'
df.loc[11,'Email Address']='kadjiflorian@helpinghamds.cm'
df.loc[12,'Email Address']='mayaghislaine@helpinghamds.cm'
df.loc[13,'Email Address']='onanahonore@helpinghamds.cm'
df.loc[14,'Email Address']='kissokjeff@helpinghamds.cm'
df.loc[15,'Email Address']='emakojenifer@helpinghamds.cm'
df.loc[16,'Email Address']='zolekojenny@helpinghamds.cm'
df.loc[17,'Email Address']='abessolostephan@helpinghamds.cm'
df.loc[18,'Email Address']='sackjordan@helpinghamds.cm'
df.loc[19,'Email Address']='atanganajosepha@helpinghamds.cm'
df.loc[20,'Email Address']='merrickjoy@helpinghamds.cm'
df.loc[21,'Email Address']='tatchijunior@helpinghamds.cm'
df.loc[22,'Email Address']='michellekitou@helpinghamds.cm'
df.loc[23,'Email Address']='laurentatangana@helpinghamds.cm'
df.loc[24,'Email Address']='amewouegoumichelle@helpinghamds.cm'
df.loc[25,'Email Address']='yumbinaomie@helpinghamds.cm'
df.loc[26,'Email Address']='meugangtania@helpinghamds.cm'
df.loc[27,'Email Address']='fongangrosane@helpinghamds.cm'
df.loc[28,'Email Address']='mefoesandra@helpinghamds.cm'
df.loc[29,'Email Address']='noraophelie@helpinghamds.cm'
df.to_csv("newcsv.csv",index=False)
df.to_excel("newxls.xls",index=False)
print(df)
