# Lecture26--Sliding-Window-Course-Programming-Using-Java
class Solution{
    static maximumSumArray(int k, ArrayList< Integer,Arr, int N)
    //int max = Integer.MIN_VALUE;
    // for (int i =0;i<=N-K;i++);
    //{
    //int sum =0;
    //for(int j =0; j<K;j++)
    //{
    //sum  = sum + Arr.get(i+j);
    //}
    //where we have found the sum of the subarray
    //if (sum > max)max = sum;
    //}
    //return max;
    int max =  Integer.MIN_VALUE;
    int sum =0;
    //Finding sum of first window
    for(int i =0;i<K;i++)
    {
       sum = summ + Arr.get(i);
    }
    // Sum if first window found
    for (int i =0;i< n-k; i++);
    {
      sum = sum - Arr.get(i)+ arr.get(i+k);
