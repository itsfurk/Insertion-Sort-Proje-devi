# Proje 3 **Binary Search Tree**
 + **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**

    + *Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.*


## Cevap:

+ **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**

+ **Dizisinin Binary Search Tree aşamalarını yazmak için öncelikle bir '' Root '' yani kök sayıya ihtiyacımız var.
Bu işlemi yaparken dizinin *soldan* ilk sayısı root sayımızdır, kendi dizimiz için bu sayı 7'dir.
Root'dan küçük sayılar root sayısının soluna, roottan büyük sayılar ise sağına yazılarak devam edilir.**


+                                                           7
                                                           / \
                                                          5   8

                                 
                                 
                                 
                                 
                               
                               
+                                                            7                               
                                                            / \
                                                           5   8
                                                         /   \   \
                                                        1     6   9
                                                  



+                                                            7                               
                                                            / \
                                                           5   8
                                                         /   \   \
                                                        1     6   9
                                                      /  \
                                                     0    3
                                                         / \
                                                        2   4                                                        
                                    
