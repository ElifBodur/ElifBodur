[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
root 7 dir.
5, 7 den küçük olduğu için solunda bulunur.
1, 7 den küçük olduğu için sol,5 den de küçük olduğu için solunda bulunur.
8, 7 den büyük olduğu için sağında bulunur.
3, 7 den küçük olduğu için solunda, 5 ten de küçük olduğu için solunda, 1 den büyük olduğu içinde sağında bulunur.
6, 7 den küçük olduğu için solunda, 5 ten de büyük olduğu için sağında bulunur.
0, 7 den küçük olduğu için solunda, 5 ten de küçük olduğu için solunda, 1 den de küçük olduğu için solunda bulunur.
9, 7 den büyük olduğu için sağında, 8 den de büyük olduğu için sağında bulunur.
4, 7 den küçük olduğu için solunda, 5 den de küçük olduğu için solunda, 1 den de büyük olduğu için sağında, 3 den de büyük olduğu için sağında bulunur.
2, 7 den küçük olduğu için solunda, 5 den de küçük olduğu için solunda, 1 den büyük olduğu için sağında , 3 den küçük olduğu için solunda bulunur.


                                     7
                              5
                                   
                                   7
                              5
                               1
                               
                               
                               
                                    7
                               5
                                 1
                                 
                                 
                                      7 
                                  5        8
                                    1
                                    
                                      7
                                   5       8
                                    1
                                      3
                                      
                                      
                                      7
                                  5         8
                                    1
                                      3
                                      
                                      
                                      
                                      
                                      
                                   
                                    
                                 
