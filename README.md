# Becroud1072
Inteval 2
N = int(input())
in_count = 0
out_count = 0
for i in range(N):
    x = int(input())
    if 20 >= x >= 10:
        in_count += 1
    else:
        out_count += 1
print(f"{in_count} in\n{out_count} out")
