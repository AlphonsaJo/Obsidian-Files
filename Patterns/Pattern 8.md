``` java
public class Main {
	public static void main (String[] args) {
		int n = 9;
		int i = 0, j = 0;
		for(i = 0; i<n; i++) {
			// Print Spaces Before
			for(j = 0; j<i; j++) {
				System.out.print(" ");
			}
			
			// Print Stars
			for(j = n; j <= 2*n - (2*i + 1); j++) {
					System.out.print("*");
			}
			// Print Spaces After
			for(j = 0; j < i; j++) {
				System.out.print(" ");
			}
			System.out.println();
			
		}
		
	}
}
```



Output:
```
*********
 ******* 
  *****  
   ***   
    * 
```
