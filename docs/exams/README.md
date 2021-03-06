# Written examinations (with keys)

In this page it is possible to find the link to the various written examination of the course Computational Thinking and Programming, academic year 2018/2019.

## 15 March 2019 written examination

**Text of the exam:** [PDF](https://comp-think.github.io/2018-2019/exams/written-examination-2019-03-15.pdf)

**Solutions:**
* Section 1 (theory):
  1. True or False
  
     not False and (True or False)
     
     True and not (True and False)
     
     not (False and not True) or False
     
  2. The return value is `"bro"`.
  3. Function defined as follows: 
     ```
     def f(s1, s2):
         if len(s1) > len(s2):
             return -1
         elif len(s1) < len(s2):
             return 1
         else:
             return 0
     ```
  4. The problem of the seven bridges of the city of Königsberg can be stated as follows: is it possible to walk around the city and to cross each of the bridges once and only once? Resolution: each land in Königsberg, excepting the starting land and the final land, should have an even number of bridges in order to be sure one can enter and then go out from it. However, all the lands have an odd number of bridges, thus it is not possible to solve the problem satisfactorily.

* Section 2 (understanding): [Python script](https://comp-think.github.io/2018-2019/python/f_written_examination_2019-03-15_ex2.py) to calculate the output of `f(my_fn, my_mn)` - run with `python f_written_examination_2019-03-15_ex2.py` and follow the instructions.

* Section 3 (development): [implementation](https://comp-think.github.io/2018-2019/python/rabin_karp_written_examination_2019-03-15_ex3.py) of the function `rabin_karp`.

## 4 February 2019 written examination

**Text of the exam:** [PDF](https://comp-think.github.io/2018-2019/exams/written-examination-2019-02-04.pdf)

**Solutions:**
* Section 1 (theory):
  1. flowline widget
  
     decision widget
     
     process widget
     
  2. The line `mid = partition(input_list, 0, input_list_len, 0)` must be replaced with `input_list_len // 2`.
  3. Function defined as follows: 
     ```
     def f(i1, i2):
         return (i1 % 2) + (i2 % 2) == 0
     ```
  4. A recursive function must have at least one **basic case**, which describe the terminating scenario that does not use any recursion to product the answer to a specific (sub-)problem, and the **recursion step**, which is where the same algorithm is executed again with a different (and, usually, reduced) input.

* Section 2 (understanding): [Python script](https://comp-think.github.io/2018-2019/python/r_written_examination_2019-02-04_ex2.py) to calculate the output of `r(my_gn, my_fn)` - run with `python r_written_examination_2019-02-04_ex2.py` and follow the instructions.

* Section 3 (development): [implementation](https://comp-think.github.io/2018-2019/python/bigrams_jaccard_written_examination_2019-02-04_ex3.py) of the function `bigrams_jaccard`.


## 25 January 2019 written examination

**Text of the exam:** [PDF](https://comp-think.github.io/2018-2019/exams/written-examination-2019-01-25.pdf)

**Solutions:**
* Section 1 (theory):
  1. an infinite memory tape
     
     an head
     
     a way to record the current state of the machine, an initial state and zero or more final states
     
     a table of instructions
  2. 8
  3. Function defined as follows: 
     ```
     def f(c, k):
         return c * k
     ```
  4. [leaf-win] if current node is a leaf and it is a solution then return it, otherwise; 
  
     [leaf-lose] if current node is a leaf but it is not a solution, then return no solution back the parent node, otherwise; 
     
     [recursive-step] apply recursively the whole approach for each child of the current node, until one of these recursive executions returns a solution - if no solution, go back the parent node of the current one.

* Section 2 (understanding): [Python script](https://comp-think.github.io/2018-2019/python/s_prepare_written_examination_2019-01-25_ex2.py) to calculate the output of `s(prepare(my_string_id))` - run with `python s_prepare_written_examination_2019-01-25_ex2.py` and follow the instructions.

* Section 3 (development): [implementation](https://comp-think.github.io/2018-2019/python/k_hash_written_examination_2019-01-25_ex3.py) of the function `k_hash`.