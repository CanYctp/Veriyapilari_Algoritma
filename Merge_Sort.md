# Merge Sort

[16,21,11,8,12,22] -> Merge Sort

- Q1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. (Write the stages of the above array according to the sort type.)
- Q2. Big-O gösterimini yazınız. (Write the Big-O notation.)

# Q1


                                                        [16,21,11,8,12,22]
          
                                              [16.21.11]                  [8,12,22]
                                  
                                  
                                         [16,21]        [11]           [8,12]        [22]
                        
                        
                                      [16]    [21]      [11]        [8]     [12]     [22]
                      
                      
                                         [16,21]        [11]           [8,12]        [22]
                      
                      
                                              [11,16,21]                  [8,12,22]
                                              
                                              
                                                        [8,11,12,16,21,22]
                                                        
                                                        
# Q2

0(nlogn)
