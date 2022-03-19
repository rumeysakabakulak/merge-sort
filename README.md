# merge sort

     [16,21,11,8,12,22]  dizinin Merge Sort türüne göre gösterimi:
            / \
 [16,21,11]     [8,12,22]
    /\            /\
[16] [21,11]   [8] [12,22]
  |     /\      |     /\
[16] [21][11]  [8]  [12][22]
  |     \/      |     \/
 [16] [11,21]  [8]  [12,22]
     \ /           \ /
 [11,16,21]    [8,12,22]
           \   /
    [6,11,12,16,21,22]
    
 BigO gösterimi: O(nlogn)
