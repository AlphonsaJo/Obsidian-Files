``` java
class Main {
   
   static void P19(int N)
{
      // for upper half 
      
      // initial spaces.
      int space = 0;
      for(int i=0;i< N;i++){
          
          //for stars 
          for(int j=1;j<=N-i;j++){
              System.out.print("*");
          }
          
          //for spaces
          for(int j=0;j<space;j++){
              System.out.print(" ");
          }
          
          //for stars 
          for(int j=1;j<=N-i;j++){
              System.out.print("*");
          }
          
          // The spaces increase by 2 for every row
          space+=2;
          
    
          System.out.println();
      }
      
      // for lower half 
      
      // initial spaces.
      space = 2*N -2;
      for(int i=1;i<=N;i++){
          
          //for stars
          for(int j=1;j<=i;j++){
              System.out.print("*");
          }
          
          //for spaces
          for(int j=0;j<space;j++){
              System.out.print(" ");
          }
          
          //for stars 
          for(int j=1;j<=i;j++){
              System.out.print("*");
          }
          
          // The spaces decrease by 2 for every row
          space-=2;
          
         
          System.out.println();
      }
}

    public static void main(String[] args) {
        
        int N = 5;
        P19(N);
    }
}

```


Output
```
**********
****  ****
***    ***
**      **
*        *
*        *
**      **
***    ***
****  ****
**********
```