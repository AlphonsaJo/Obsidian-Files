``` java
public class Main {
    	public static void main (String[] args) {
		    P7();
	    }   
    public static void P7(){
        int n = 4;
		int i = 0, j = 0;
		for(i = 0; i<n; i++) {
			// Print Spaces Before
			for(j = 0; j < n - i - 1; j++) {
				System.out.print(" ");
			}
			char ch = 'A';
            int breakpoint = (2*i+1)/2;
			// Print Stars
			for(j = 1; j<= 2*i+1; j++) {
			        System.out.print(ch);
			        if(j <= breakpoint) ch++;
                    else ch--;
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
   A   
  ABA  
 ABCBA 
ABCDCBA
```

