# DCLP3


import random

def evolve_list(T, k):
    for i in range(10):
        for j in range(10):
            if i + j == T:
                result = [i, j]
                while len(result) < k:
                    result.append(0)
                return result
    return [0] * k
