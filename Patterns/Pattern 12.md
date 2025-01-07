``` java
public class Main {
    public static void main(String[] args) {
        int n = 6;
        int i = 0, j = 0;

        for (i = 0; i < n; i++) {
            // Print Numbers Before Stars (Spaces replaced by numbers)
            for (j = 1; j <= i; j++) {
                System.out.print(j);
            }

            // Print Spaces Between Numbers and Stars
            for (j = 1; j <= (n - i - 1) * 2; j++) {
                System.out.print(" ");
            }

            // Print Stars After Spaces
            for (j = 1; j <= i; j++) {
                System.out.print(j);
            }

            System.out.println(); // Move to the next line
        }
    }
}
```

Output
```
1        1
12      12
123    123
1234  1234
1234512345
```

