import math

def calculate_combinations(n, k):
    return math.comb(n, k)

n = 22
k = 11
combinations = calculate_combinations(n, k)
print(f"The number of ways to choose {k} players from {n} players is: {combinations}")
