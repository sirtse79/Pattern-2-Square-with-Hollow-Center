# Pattern-2-Square-with-Hollow-Center
code
size = int(input()) # but it works only whith values over 3 : 4, 5 and ets.

print(size * "*") 
for i in range(1, size):
    print("*", (size - 4) * " ", "*")
print(size * "*")
