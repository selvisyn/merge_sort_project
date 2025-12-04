# merge_sort_project
Merge Sort algorithm implementation with analysis.

# Given Array
`[16, 21, 11, 8, 12, 22]`

# Merge Sort Steps

# Divide Phase
The array is recursively divided into smaller subarrays:

- `[16, 21, 11]` and `[8, 12, 22]`

Further splitting:

Left side:
- `[16]` and `[21, 11]`
- `[21]` and `[11]`

Right side:
- `[8]` and `[12, 22]`
- `[12]` and `[22]`

# Merge Phase

Merging the smallest parts first:

Left side merges:
- `[21] + [11]` → `[11, 21]`
- `[16] + [11, 21]` → `[11, 16, 21]`

Right side merges:
- `[12] + [22]` → `[12, 22]`
- `[8] + [12, 22]` → `[8, 12, 22]`

# Final Merge
Merging the two sorted halves:

Left: `[11, 16, 21]`  
Right: `[8, 12, 22]`

Final result:

`[8, 11, 12, 16, 21, 22]`

# Big-O Notation

Merge Sort always divides the array into halves (`log n`)  
and merges all elements in each level (`n`).

Therefore:

- Best Case: O(n log n)  
- Average Case: O(n log n)  
- Worst Case: O(n log n)

# Overall Time Complexity:  
`O(n log n)`

- Final sorted output  
- Big-O complexity analysis
