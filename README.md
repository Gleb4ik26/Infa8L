ДЗ №1
n = int(input("Введите число:"))
tot = 0
while(n > 0):
    dig = n % 10
    tot = tot + dig
    n = n//10
print("Сумма цифр равна:", tot)
ДЗ №2
num = int(input("Введите натуральное число: ")) 
i = 1 
print("Делители числа", num, ":") 
while i <= num: 
    if num % i == 0: 
        print(i) 
    i += 1
