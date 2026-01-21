テストケース

def add(a, b, c=0):
try:
return int(a + b) + int(c)
except:
return “error”

正常
a:5 b:10 = 15
a:2 b:3 = 5
a:100 b:234 = 334
a:-1 b:-5 = -6

print(add(5,10))
print(add(2,3))
print(add(100,234))
print(add(-1,-5))

異常
print(add("a","b"))
print(add(true,false))

結果
https://colab.research.google.com/drive/1XMRfgytN1ics4vwNerMmL5Hp4hN1ySYa?usp=sharing


