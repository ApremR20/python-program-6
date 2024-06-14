# python-program-6
#class getitem()
class numbers:
    def __init__(self,mylist):
        self.mylist=mylist
    def __getitem__(self,index):
        return self.mylist[index]
numlist=numbers([1,2,3,4,5,6,7,8,9])
print(numlist[5])
