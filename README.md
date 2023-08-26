# calculatoer
first = int(input("enter numbe first:"))
operation =input("enter operation(+,-,*,/,**,//,%):")
second = int(input("enter number second:"))
if operation =="+":
  print(first+second)
elif operation =="-":
  print(first-second)
elif operation =="*":
  print(first*second)
elif operation =="/":
  print(first/second)
elif operation =="**":
  print(first**second)
elif operation =="//":
  print(first//second)
elif operation =="%":
  print(first%second)
else:
  print("inveled input")
