# Search-and-Sort-Project
Sort an array of 10,000 elements using the quick sort algorithm as follows: 

a. Sort the array using pivot as the middle element of the array. 
b. Sort the array using pivot as the median of the first, last, and middle elements of the array. 
c. Sort the array using pivot as the middle element of the array. However, when the size of any sublist reduces to less than 20, sort the sublist using an insertion sort. 
d. Sort the array using pivot as the median of the first, last, and middle elements of the array. When the size of any sublist reduces to less than 20, sort the sublist using an insertion sort. 
e. Calculate and print the CPU time for each of the preceding four steps. To find the current CPU time, declare a variable, say, x, of type clock_t. The statement x = clock(); stores the current CPU time in x. You can check the CPU time before and after a particular phase of a program. Then, to find the CPU time for that particular phase of the program, subtract the before time from the after time. Moreover, you must include the header file ctime to use the data type clock_t and the function clock. Use a random number generator to initially fill the array.
