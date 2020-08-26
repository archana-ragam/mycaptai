#function program
string=input("enter string:")
print(string)
def most_frequent():
 count={"i":0,
        "s":0,
         "p":0,
         "m":0}
 for x in string:
   if x in count.keys():
    count[x]+=1
   else:
    count[x]=1
 print("i:0",count["i"])
 print("s:0",count["s"])
 print("p:0",count["p"])
 print("m:0",count["m"])
most_frequent()
