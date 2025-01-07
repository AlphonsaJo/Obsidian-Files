``` java
public class Main {
    	public static void main (String[] args) {
		P7();
		
	}
	
    public static void P7(){
        int count = 0;
        int n = 5;
		int i = 0, j = 0;
		for(i = 1; i<=n; i++) {
			for(j = 1; j <= i; j++) {
			 count+=1;
			System.out.print(count + " ");
			
		    }
		    System.out.println();
        }
        
    }
}
```

Output
```
1 
2 3 
4 5 6 
7 8 9 10 
11 12 13 14 15
```

