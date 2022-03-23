# CMPS 2200 Assignment 3
## Answers

**Name:** Ruoqin Ji


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**
**Answer:** We can tell that `parens_match_iterative` iterate the whole list one by one and perform a if-else statement fo each interation. Thus, its work is $W(n)= O(n)$. Since the whole process is sequential, leaving no space for parallelism, then its span is $S(n) = O(n)$.




- **d.**
**Answer:** Program `parens_match_scan` firstly calls `map` to perform function `parens_map` on each element in the list. Then, by implemnting the efficient scan (with method of contraction), the total work is $W(n) = W(\frac{n}{2})+n \in O(n)$. Its span is $S(n) = S(\frac{n}{2})+O(1) \in O(\lg n)$. 




- **f.**
**Answer:** Since the merging step takes constant work, then the total work is $W(n)=2W(\frac{n}{2})+1 \in O(n)$ and its span is $S(n) = S(\frac{n}{2})+O(1) \in O(\log n)$.