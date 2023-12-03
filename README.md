# Fibonacci-Series
n = int(input("n: "))
a=0
b=1
print(a)
if b <= n:
  print(b)
while b <= n:
  c = a+b
  if c > n:
    break
  print(c)
  a, b=b, c
