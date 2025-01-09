
``` java
class Main {
   public static void main(String[] args) {
        int N = 5;
        P21(N);
    }
   static void P21(int n)
    {
      // outer loop for row
     for(int i=0;i<n;i++){
         
         // inner loop 
         for(int j=0;j<n;j++)
         
             // if boundary index, print star
             if(i==0 || j==0 || i==n-1 || j==n-1)
             // OR condition for: 
             // i = 0 (entire first row), i == n-1 (entire last row), j == 0 (only first column), j == n-1 (only last column)
                System.out.print("*");
                
             // if not boundary, print star
             else System.out.print(" ");
         }
         
          
          System.out.println();
        }
    }

}

```


Output
```
*****
*   *
*   *
*   *
*****
```

