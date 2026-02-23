# Algorithms and Data Structures (for Data Science)

* Teacher: [Rossano Venturini](http://pages.di.unipi.it/rossano)
* CFU: 9
* Period: Second semester
* Language: English
* Telegram: [here](https://t.me/+Vf7FqiCLEPw1NmI0)
* Teams: [here](https://teams.microsoft.com/l/team/19%3APhmXqG49uhpl5VZlTXjiVL9p552czBJ7ksHO_Xrqk901%40thread.tacv2/conversations?groupId=bfce4a8d-c6ac-4cda-9e74-17a775351760&tenantId=c7456b31-a220-47f5-be52-473828670aa1)
* Lectures schedule: Monday 11:00-13:00 (Aula Fib C1), Wednesday 11:00-13:00 (Aula Fib E), and Thursday 9:00-11:00 (Aula Fib C).
* Question time: After lectures or by appointment

## Goals and opportunities

The course introduces basic data structures and algorithmic techniques that allow students to solve computational problems on the most important data types, such as sequences, sets, trees, and graphs.

An intensive laboratory activity will complement the lectures.
Students will experiment with algorithms and data structures by writing their own implementations or by using third-party libraries.

The class's goal is to enable students to design and implement efficient algorithms, choosing the most appropriate solutions for their future projects.

### Syllabus

- Introduction and basic definitions: algorithm, problem, instance.

- Computational complexity analysis of algorithms.

- Sorting: Mergesort, Quicksort, and Heapsort.

- Searching: Binary Search, Binary Search Tree, Trie, and Hashing.

- Algorithms on Trees: representation and traversals.

- Algorithms on Graphs: representation, traversals, and the most important problems.

- External memory model: sorting and searching.

## Exam

| Type | Date | Room | Note|
| ------------- | ------------- | ------------- | ----- |
| Lab | 23/03/2026 14:00 | [Google Meet](https://meet.google.com/kwr-arcz-xcq) | Please send your solutions to me by 20/03/2026. **Important:**  Please Cut&Paste your solutions to this [Jupyter Notebook](Lab/Solutions_NAME_SURNAME.ipynb) and **send me just this file** with your name and surname on its filename. Please read the very important note below. |
| Theory | 27/03/2026 14:00 | Room E |  |



**Very important!** You are allowed to verbally discuss solutions (e.g., a strategy to solve a problem) with other students, **BUT** you have to implement all the solutions yourself. Thus, sharing implementations or implementing a solution with others is strictly **forbidden**.

## References
*   Introduction to Algorithms,  3rd Edition, Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Clifford Stein, The MIT Press, 2009 ([Amazon](http://www.amazon.com/Introduction-Algorithms-3rd-Thomas-Cormen/dp/0262033844/ref=sr_1_1?s=books&ie=UTF8&qid=1443160441&sr=1-1&keywords=introduction+to+algorithms)) [CCLR]
*   Algorithms, 4th Edition, Robert Sedgewick, Kevin Wayne, Addison-Wesley Professional, 2011 ([Amazon](http://www.amazon.com/Algorithms-4th-Edition-Robert-Sedgewick/dp/032157351X/ref=pd_sim_14_2?ie=UTF8&refRID=1A2NFN935EST0ZQARB6H&dpID=51UDgHU9z9L&dpSrc=sims&preST=_AC_UL160_SR130%2C160_)) [RS]
*   Algorithms, Sanjoy Dasgupta, Christos Papadimitriou, Umesh Vazirani, McGraw-Hill, 2006\. ([Amazon](http://www.amazon.com/Algorithms-Sanjoy-Dasgupta/dp/0073523402)) [DPZ]

## Lectures
| Date | Lecture | References | Material |
| -------------: | :------------- | :------------- | :------------- |
| 16/02/2026 | Introduction to analysis of algorithms.| CCLR Sect. 2.1 | [Notes next 3 lectures](Notes/Analysis22.pdf)|
| 18/02/2026 | Insertion Sort: Correctness and analysis.| CCLR Sect. 2.2 | [VisuAlgo Sorting](https://visualgo.net/en/sorting) |
| 19/02/2026 | Insertion Sort: Correctness and analysis.| CCLR Sect. 2.2 | [VisuAlgo Sorting](https://visualgo.net/en/sorting) |
| 23/02/2026 | Selection Sort: Correctness and analysis.|  | [Selection Sort vs Insertion Sort ](Notes/L01_Insertion_Sort_vs_Selection_Sort.ipynb) and [VisuAlgo Sorting](https://visualgo.net/en/sorting)|
| 25/02/2026 | Divide and Conquer. Merge Sort. | CCLR Sect. 2.3  | [VisuAlgo Sorting](https://visualgo.net/en/sorting) and  [Notes next 3 lectures](Notes/Mergesort22.pdf) |
| 26/02/2026 | **Laboratory**: Basic sorting algorithms | | [Jupyter Notebook](Lab/Lecture_01/L01_Basic_Sorting_no_sols.ipynb) **Mandatory exercises** |

## Last Year Lectures
| Date | Lecture | References | Material |
| -------------: | :------------- | :------------- | :------------- |
| 05/03/2025 | Binary search. QuickSort. Best and worst cases. No average time analysis. |  CCLR Sect 3.1. CCLR Sects 7.1, 7.2, and 7.3. | [VisuAlgo Sorting](https://visualgo.net/en/sorting) and [Notes next 2 lectures](Notes/Quicksort22.pdf) |
| 07/03/2025 | **Laboratory**: MergeSort and QuickSort. | | [Jupyter Notebook](Lab/Lecture_02/L02_Sorting_no_sols.ipynb) **Mandatory exercises** | 
| 11/03/2025 | QuickSort. Best and worst cases. No average time analysis. Asymptotic notation. | CCLR Sects 7.1, 7.2, and 7.3. | [VisuAlgo Sorting](https://visualgo.net/en/sorting) and [Notes next 2 lectures](Notes/Quicksort22.pdf) |
| 12/03/2025 | Lower Bound for sorting in the comparison model. | CCLR Sect. 8.1 |[Notes](Notes/Lowerbound22.pdf) |
| 14/03/2025 | **Laboratory**: Applications of sorting (I). | | [Jupyter Notebook](Lab/Lecture_03/L03_Sorting_Applications_Greedy_Algorithms_no_sols.ipynb) **Mandatory exercises** | 
| 18/03/2025 | Sorting in linear time: Counting Sort and Radix Sort. | CCLR Sect. 8.2 adn 8.3 | [VisuAlgo Sorting](https://visualgo.net/en/sorting). [Notes](Notes/LinearTimeSorting22.pdf)| 
| 19/03/2025 | Dictionary problem with Hashing.| CCLR Sect. 11.1, 11.2, and 11.4 (no analysis) | [Notes](Notes/Hashing22.pdf) |
| 25/03/2025 | Dictionary problem with Hashing.| CCLR Sect. 11.1, 11.2, and 11.4 (no analysis) | |
| 26/03/2025 | **Laboratory**: Hashing. | | [Jupyter Notebook](Lab/Lecture_04/L04_Hashing_no_sols.ipynb) **Mandatory exercises** |
| 28/03/2025 | Python best practices. | | |
| 01/04/2025 | Python best practices. | | |
| 02/04/2025 | Python best practices. | | |
| 04/04/2025 | Python best practices. | | |
| 11/04/2025 | Python best practices. | | |
| 15/04/2025 | QuickSelect. Priority queues: Heap. | CCLR Sect. 9.1, 9.2 and CCLR Ch. 6 | [Notes next 3 lectures](Notes/Heap.pdf) |
| 16/04/2025 | Priority queues: Heap. | CCLR Ch. 6 | [VisuAlgo Heap](https://visualgo.net/en/heap?slide=1) | 
| 23/04/2025 | Priority queues: Heap. | CCLR Ch. 6 | [VisuAlgo Heap](https://visualgo.net/en/heap?slide=1) |
| 29/04/2025 | Binary Search tree. | CCLR Sect. 12.1, 12.2, and 12.3  | [Visualgo BST](https://visualgo.net/en/bst) | [Notes for next two lectures](Notes/Bst.pdf) |
| 30/04/2025 | Binary Search tree. | CCLR Sect. 12.1, 12.2, and 12.3  | [Visualgo BST](https://visualgo.net/en/bst) |  | 
| 02/05/2025 | **Laboratory**: Hashing: Applications.  | | [Jupyter Notebook](Lab/Lecture_05/L05_Hashing_Applications_no_sols.ipynb) **Mandatory exercises** |
| 06/04/2025 | Exercises: Visits of a tree. |  | [Notes next 2 lectures](Notes/Trees.pdf) | |
| 07/05/2025 | Exercises: Visits of a tree. |  | | | 
| 09/05/2025 | **Laboratory**: Applications of sorting (II). | | [Jupyter Notebook](Lab/Lecture_06/L06_Sorting_Applications_II_no_sols.ipynb) **Mandatory exercises** |
| 13/05/2025 | Graphs: representations and BFS. |CCLR Sect. 22.1 and 22.2 (no proofs) | [Notes next 3 lectures](Notes/Graphs.pdf) | 
| 14/05/2025 | Graphs: representations and BFS. |CCLR Sect. 22.1 and 22.2 (no proofs) | | 
| 16/05/2025 | **Laboratory**: Binary Search Tree.  | | [Jupyter Notebook](Lab/Lecture_07/L07_Binary_Search_Tree_no_sols.ipynb) **Mandatory exercises** |
| 21/05/2025 | Graphs: DFS. |CCLR Sect. 22.3 (no proofs) | [Graph representations](https://visualgo.net/en/graphds) and [BFS/DFS](https://visualgo.net/en/dfsbfs) |
| 23/05/2025 | Exercises | [Exercise 1](Notes/Exam20210610_sol.pdf) and [Exercise 2](Notes/Exam20210723_sol.pdf)|
| 28/05/2025 | **Laboratory**: Graphs.  | | [Jupyter Notebook](Lab/Lecture_08/L08_Graphs_with_NetworkX_no_sols.ipynb) **Mandatory exercises** |

