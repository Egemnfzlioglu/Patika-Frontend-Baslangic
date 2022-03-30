[22,27,16,2,18,6] -> Insertion Sort**

## [22,27,16,2,18,6] -> Insertion Sort

**
**1.**  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

|Cevap|  |
|--|--|


			[22,27,16,2,18,6]
			
			[2,27,16,22,18,6]
			
			[2,6,16,22,18,27]
			
			[2,6,16,18,22,27]			
***  



**2.**.  Big-O gösterimini yazınız.

|Cevap|  |
|--|--|
	
	
	Big-O = n + (n - 1) + (n - 2) + (n - 3) + (n - 4) + (n - 5) + (n - 6) + .......+ 1=
			
		  = n . (n + 1) / 2
			
		  = (n^2 + n) / 2
			
		  = O ( n^2 )		
				
***
**3.**  **Time Complexity**: 

|Cevap|  |
|--|--|




   ***Average case:***  Aradığımız sayının ortada olması,

			Average case: O(n^2)  

   ***Worst case*:**  Aradığımız sayının sonda olması, 

			Worst case: O(n^2) 

   ***Best case:***  Aradığımız sayının dizinin en başında olması.
   
		   	Best case: O(n)





***




**4.**  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

|Cevap|  |
|--|--|


		Avarage case kapsamına girer.


***
***






## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre   *` ilk 4 `* adımını yazınız.


|Cevap|  |
|--|--|

			[ 7, 3, 5, 8, 2, 9, 4, 15, 6 ]
			
			[ 2, 3, 5, 8, 7, 9, 4, 15, 6 ]
			
			[ 2, 3, 4, 8, 7, 9, 5, 15, 6 ]
			
			[ 2, 3, 4, 5, 7, 9, 8, 15, 6 ]
			
			[ 2, 3, 4, 5, 6, 9, 8, 15, 7 ]