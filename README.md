Chocolate Factory Packing Problem
Problem Description
In a chocolate factory, packets of chocolates are represented as an array of integers. Each integer value corresponds to a packet, where 0 indicates an empty packet, and any positive integer represents a filled packet with chocolates. The task is to rearrange the array such that all empty packets (i.e., 0s) are moved to the end of the array while maintaining the order of the filled packets.

Example
Given:
  Input:

Number of packets, N=8
Array of packets, arr=[4,5,0,1,9,0,5,0]

  Output:

  Rearranged array, arr=[4,5,1,9,5,0,0,0]

  Requirements
Input: An integer array containing a mixture of positive integers and zeros.
Output: A modified array where all zeros are shifted to the end, while the order of non-zero integers remains unchanged.

Implementation
The solution involves iterating through the array, moving non-zero elements to the front, and counting the zeros. Finally, the remaining positions in the array are filled with zeros.

