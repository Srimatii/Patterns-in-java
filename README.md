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
4.**PATTERN 4** (Half Pyramid)
```
*
* *
* * *
* * * *
```
```Java
public class HalfPyramid {
    public static void main(String[] args) {
        int n = 4;
        for (int i = 1 ; i <= n; i++){
            for (int j = 1 ; j <= i ; j++){
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```
5.**PATTERN 5**(Floyds Triangle)
```
1
2  3
4  5  6
7  8  9  10
11 12 13 14 15
```
```Java
public class FloydsTriangle {
    public static void main(String[] args) {
        int n = 5;
        int number = 1;
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print(number + " ");
                number++;
                }
                System.out.println();
            }
            
        }
}
```
6. **PATTERN 6** (ZERO - ONE Pyramid)
```
1
0 1
1 0 1
0 1 0 1
1 0 1 0 1
```
```Java
public class FloydsTriangle {
    public static void main(String[] args) {
        int n = 5;
        int number = 1;
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print(number + " ");
                number++;
                }
                System.out.println();
            }
            
        }

    }
```
