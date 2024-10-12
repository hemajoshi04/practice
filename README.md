# practice
import pylab as plb

def Calc_interest(p,r):
    i=p*r*1/122
    return i

p=10000
my=2
r=6
months=list(range(0,my*12+1))
bal=[p]
for i in range(1,len(months)):
    p=p+Calc_interest(p,r)
    bal.append(p)
    plb.plot(months.bal.marker='0',styleline='*',color='b');
    plb.title("errowth of fixecl Deposit with monthly compounting")
    plb.xlabel("Time(months)")
    plb.grid()
    plb.show()
    
