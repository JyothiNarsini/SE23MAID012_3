# Binary Search Tree (BST) Test
This repository contains Java code for testing the performance of a Binary Search Tree (BST) with multithreading. The code allows you to evaluate the concurrent behavior of a BST with multiple threads, performing operations such as insertion, deletion, and searching within the tree.

## Overview of the Components
The code consists of the following components:
1. BST_Test.java: The main class that orchestrates the testing of the BST with multithreading.
2. BinarySearchTree.java: The implementation of a binary search tree.
3. ThreadID.java: A utility class for obtaining thread-specific IDs.
4. Counter.java: A simple counter utility class used to count thread operations.

## Running of the Test
You can run the test by compiling and executing `BST_Test.java`. The program takes command-line arguments to specify the number of threads, the prefill size of the tree, and the workload. The workload is defined as a string in the format "D-I-C," where:
- "D" represents the percentage of delete operations.
- "I" represents the percentage of insert operations.
- "C" represents the percentage of contains operations.


Example command to run the program:
```shell
java BST_Test <num_threads> <prefill_size> <workload>
```
Replace `<num_threads>`, `<prefill_size>`, and `<workload>` with appropriate values.

## Testing Strategies
The code initializes a BST with a specified number of nodes, prefilling the tree with random values. Threads are then spawned to perform operations based on the defined workload percentages. The program measures the throughput and reports the results.

## Output of the Result
The program reports the following metrics:
- `num_threads`: The number of threads used for testing.
- `totalOps`: The total number of operations performed.
- `throughput`: The throughput in operations per second (ops/s).

## Example Output
BST_Test:num_threads:<num_threads>:totalOps:<totalOps>:throughput:<throughput> ops/s

## Final Conclusion
This code allows you to test the concurrent behavior of a binary search tree with different workloads and analyze its performance under multi-threaded scenarios. You can adjust the number of threads, prefill size, and workload to assess the behavior of the BST for your specific use case.

##  Graphs plotted against throughput by varying no.of threads for different locks 
![1]![image](https://github.com/JyothiNarsini/SE23MAID012_3/assets/88646255/0c223b69-daab-4389-9070-9a176be9dc03)
![2]![image](https://github.com/JyothiNarsini/SE23MAID012_3/assets/88646255/364b785d-3067-4d1c-8799-0ac0f9b47c91)
![3]![image](https://github.com/JyothiNarsini/SE23MAID012_3/assets/88646255/835201b6-2abf-44aa-882b-aa8ed7477ec6)
![4]![image](https://github.com/JyothiNarsini/SE23MAID012_3/assets/88646255/9e149e1f-190b-4671-92f3-fda55a4233e3)
![5]![image](https://github.com/JyothiNarsini/SE23MAID012_3/assets/88646255/06ad18a4-0961-4046-8bcf-2aec5815b64e)
![6]![image](https://github.com/JyothiNarsini/SE23MAID012_3/assets/88646255/7be7d28f-334d-4044-bbf4-cd26ee869822)






