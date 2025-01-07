
``` java
public class Main {
    	public static void main (String[] args) {
		P7();
		
	}
    public static void P7(){
        int n = 5;
		int i = 0, j = 0;
		for(i = 0; i<n; i++) {
			// Print Spaces Before
			for(j = 0; j < n/2; j++) {
				System.out.print(" ");
			}
			
			// Print Binary Numbers
			for(j = 0; j< 2*i+1; j++) {
					if(i%2==0){
        		        if(j%2==0){
        		            System.out.print("1");
        		        }
        		        else{
        		            System.out.print("0");
        		        }
    		    }
    		    else{
        		        if(j%2==0){
        		            System.out.print("0");
        		        }
        		        else{
        		            System.out.print("1");
        		        }
    		    }
			}
			// Print Spaces After
			for(j = 0; j < n - i - 1; j++) {
				System.out.print(" ");
			}
			System.out.println();
		}
    }

}
```

Output
```
  1    
  010   
  10101  
  0101010 
  101010101
```

Prints odd number of times in each line