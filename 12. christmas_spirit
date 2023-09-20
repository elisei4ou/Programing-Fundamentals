quantity = int(input())
days_left = int(input())
final_price = 0
point = 0

for i in range(1, days_left + 1):
    if i % 11 == 0:
        quantity += 2
    if i % 2 == 0:
        final_price += quantity * 2
        point += 5
    if i % 3 == 0:
        final_price += quantity * 8
        point += 13
    if i % 5 == 0:
        final_price += quantity * 15
        point += 17
    if i % 15 == 0:
        point += 30
    if i % 10 == 0:
        final_price += 23
        point -= 20

if days_left % 10 == 0:
    point -= 30

print(f"Total cost: {final_price}")
print(f"Total spirit: {point}")
