Algorithm: One-pass Hash Map.
Logic: As we iterate through the nums vector, we calculate the complement (target - current number). If the complement exists in our map, we've found the pair. Otherwise, we store the current number and its index.
Efficiency:

    Time Complexity:
    — We traverse the list only once.
    Space Complexity:
    — In the worst case, we store every element in the map.
