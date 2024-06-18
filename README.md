## PRINTING PATTERNS IN JAVA

1. **PATTERN 1** (Solid Rectangle)
```
* * * * *
* * * * *
* * * * *
* * * * *
```
```Java
public class Solidrectangle {
    public static void main(String[] args) {
        int n = 4;
        int m = 5;
        //outer loop
        for(int i = 1; i<=n ; i++) {
            //inner loop
            for(int j = 1; j<=m; j++){
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```
2. **PATTERN 2** (Hollow Rectangle)
```
* * * * *
*       *
*       *
* * * * *
```
```Java
public class HollowRectangle {
    public static void main(String[] args) {
        int n = 4;
        int m = 5;
        //outer loop
        for(int i = 1; i<= n ;i++){
            //inner loop
            for(int j = 1; j <= m; j++){
               if(i == 1 || j == 1 || i == n || j == m){
                System.out.print("*");
               }else{
                System.out.print(" ");
               }
            }
            System.out.println();
        }
    }    
}
```

3.**PATTERN 3** (Pyramid)
```
    *
   * *
  * * *
 * * * *
* * * * *
```
```Java
public class Pyramid {
    public static void main(String[] args) {
        int n = 5;
        for(int i =1; i <= n ; i ++){
            for(int j = 0 ; j <= n-i ; j++){
                System.out.print(" ");
            }
            for(int k = 1; k <= i ; k++){
                System.out.print("* "+ " ");
            }
            System.out.println();
        }
    }
}
```
