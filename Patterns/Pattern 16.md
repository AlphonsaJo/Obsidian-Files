``` java
public class Main {
    	public static void main (String[] args) {
		P16();
		
	}
	
    public static void P16(){
        char c = 'A';
        int count = 0;
        int n = 5;
		int i = 0, j = 0;
		for(i = 1; i<=n; i++) {
			for(j = 1; j <= i; j++) {
			    System.out.print(c);
			    
		    }
		        c++;
		        System.out.println();
        }
        
    }
}
```

Output
```
A
BB
CCC
DDDD
EEEEE
```
