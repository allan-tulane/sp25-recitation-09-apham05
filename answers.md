# CMPS 2200 Recitation 09

## Answers

**Name:**_____Anh Pham____________________
**Name:**_________________________


Place all written answers from `recitation-09.md` here for easier grading.



- **2)**
- If the graph has k connected components, the modified Prim’s algorithm runs once for each component. Even though we do this multiple times, each edge and vertex is still only processed once overall. So, the worst-case work is the same as the regular prim’s algorithm: O(ElogV).

- **4)**
- The total work of the algorithm has two parts. The algorithm builds a fully connected graph by computing the distance between every pair of cities, which takes O(n^2) work since there are about n^2 pairs. Then, it runs prim’s algorithm on that graph, which takes O(n^2 logn) work because of the large number of edges. The MST step dominates the overall runtime so the work of the full algorithm is O(n^2 logn).
