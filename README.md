# hello-world
Memo of my python practices

Hi Humans!
Xudong-yali is here. 

The first programming I did is as below:

a=input('甲筐苹果的数量是乙筐苹果的几倍')  ##甲筐的苹果数是乙筐的几倍量，也就是可以把乙筐当做一倍量看待
b=input('从甲筐取出多少个苹果放入乙筐，那么两筐苹果就一样多')
print('甲筐苹果+乙筐苹果='+a+'+1'+'倍量')
print('甲筐苹果-乙筐苹果='+'2*'+b)
c=input('你打算求甲筐苹果，还是乙筐苹果呢')
if c=='甲筐苹果':
    d=2*int(b)/(int(a)-1)*int(a)
    print('甲筐苹果数是'+str(d))
elif c=='乙筐苹果':
    e=2*int(b)/(int(a)-1)
    print('乙筐苹果数是'+str(e))
else:
    print('你既不是求甲筐苹果，也不是求乙筐苹果')
