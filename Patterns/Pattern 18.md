``` java
public class Main {
    	public static void main (String[] args) {
		P16();
		
	}
	
    public static void P16(){
       
        
        int n = 5;
		int i = 0, j = 0;
		for(i = 0; i<n; i++) {
			for(char ch =(char)(int)('A'+n-1-i);ch<=(char)(int)('A'+n-1);ch++){
              
              System.out.print(ch + " ");
          }
		        
		        System.out.println();
        }
        
    }
}
```

Output
```
E 
D E 
C D E 
B C D E 
A B C D E 
```

Important code
``` java
for(char ch =(char)(int)('A'+n-1-i);ch<=(char)(int)('A'+n-1);ch++)
```

