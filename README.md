# woman
 beautiful people

mylist = list('abcedfghijklmnopqrstuvwxyz')
myarr = np.arange(26)
mydict = dict(zip(mylist, myarr))
ser = pd.Series(mydict)


df = ser.to_frame()
print(df.tail())
