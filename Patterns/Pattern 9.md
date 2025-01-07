``` java
public class Main {
    	public static void main (String[] args) {
		P7();
		P8();
	}
	
    public static void P7(){
        int n = 5;
		int i = 0, j = 0;
		for(i = 0; i<n; i++) {
			// Print Spaces Before
			for(j = 0; j < n - i - 1; j++) {
				System.out.print(" ");
			}
			
			// Print Stars
			for(j = 0; j< 2*i+1; j++) {
					System.out.print("*");
			}
			// Print Spaces After
			for(j = 0; j < n - i - 1; j++) {
				System.out.print(" ");
			}
			System.out.println();
		}
    }
    
 
	public static void P8 () {

		int n = 5;
		int i = 0, j = 0;
		for(i = 0; i<n; i++) {
			// Print Spaces Before
			for(j = 0; j<i; j++) {
				System.out.print(" ");
			}
			
			// Print Stars
			for(j = 0; j < 2*n - (2*i + 1); j++) {
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

Output
```
    *    
   ***   
  *****  
 ******* 
*********
*********
 ******* 
  *****  
   ***   
    * 
```

