``` java
public class Main {
    	public static void main (String[] args) {
		P14();
		
	}
	
    public static void P14(){
        char c = 'A';
        int count = 0;
        int n = 5;
		int i = 0, j = 0;
		for(i = 1; i<=n; i++) {
		    c = 'A';
			for(j = 1; j <= i; j++) {
			    System.out.print(c);
			    c++;
		    }
		        System.out.println();
        }
        
    }
}
```

Output
```
A
AB
ABC
ABCD
ABCDE
```

