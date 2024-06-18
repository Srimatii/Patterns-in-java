## PRINTING PATTERNS IN JAVA

1. **PATTERN 1** (Solid Rectangle)
```Java
public class Solidrectangle {
   
    public static void main(String[] args) {
        int n = 4;
        int m = 5;

        //outer loop
        for(int i = 1; i<=n ; i++)
        {
            //inner loop
            for(int j = 1; j<=m; j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```
