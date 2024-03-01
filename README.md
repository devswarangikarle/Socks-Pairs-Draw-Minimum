# Socks-Pairs-Draw-Minimum
In a box, there are N pairs of socks. Adrish decided to wear 1 matching pair of socks but he cannot see inside the box. So he wanted your help to determine what's the minimum number of socks that he needs to draw so that he can get a matching pair certainly.

def min_socks_to_draw(N):
    return N + 1

try:
    N = int(input())

    if N <= 0:
        print(result)
    else:
        result = min_socks_to_draw(N)
        print(result)
except ValueError:
    print(result)
