``` java
	public static void main (String[] args) {
		int i = 0, j = 0;
		for(i = 5; i>=1; i--) {
			for(j = 1; j<= i; j++) {
				System.out.print(j);
			}
			System.out.println();
		}
	}
```


Output
```
12345
1234
123
12
1

```