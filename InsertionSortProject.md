[22,27,16,2,18,6] -> Insertion Sort

1-)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-)Big-O gösterimini yazınız.
3-)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5-)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


1-)
  16,22,27,2,18,6
  2,16,22,27,18,6 
  2,16,18,22,27,6
  2,6,16,18,22,27

2-)
  O(n^2)'dir.
  
3-)
  Worst Case: 27,22,18,16,6,2
  Best Case: 2,6,16,18,22,27
  Average Case: 2,6,16,18,22,27
  
4-) Average case yöntemine girer çünkü sıralamadan sonra aradığımız sayı (18) ortanca sayıdır


5-)
  7,3,5,8,2,9,4,15,6 BAŞLANGIÇ
  1a-) 3,7,5,8,2,9,4,15,6
  2a-) 3,5,7,8,2,9,4,15,6
  4a-) 2,3,5,7,8,9,4,15,6
  5a-) 2,3,4,5,7,8,9,15,6
  6a-) 2,3,4,5,6,7,8,9,15
  

  







