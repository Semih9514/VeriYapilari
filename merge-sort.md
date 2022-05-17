# Merge Sort

                                [16,21,11,8,12,22]
Level 0                
                        [16,21,11]                [8,12,22]
Level 1
                    [16,21]        [11]        [8,12]        [22]
Level 2
                [16]    [21]    [11]       [8]    [12]    [22]
Merge(Level 2)
                    [16,21]   [11]             [8,12]   [22]
Merge(Level 1)
                        [11,16,21]                [8,12,22] 
Merge(Level 0)
                                [8,11,12,16,21,22]

# Big O Notation

O(nlogn)