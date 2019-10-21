## 预习作业~~讲评~~答案



### Lv0：

```java
public class Lv0 {
    public static void main(String[] args) {
        System.out.println("Hello world!");
    }
}
```





### Lv1：



```java
public class Lv1 {
    public static void main(String[] args) {
        int a = 999;
        while (555555 % a != 0) a--;
        System.out.println("555555的最大三位约数是：" + a);
    }
}
```





### Lv2:

```Java
public class Lv2 {
    public static void main(String[] args) {
        for (int i = 0; i < 10; i++) {
            for (int j = i; j < 9; j++) {
                System.out.printf("   ");
            }
            for (int j = 0; j <= i; j++) {
                System.out.printf("*");
            }
            System.out.println();
        }
        for (int i = 0; i < 9; i++) {
            for (int j = 0; j <= i; j++) {
                System.out.printf("   ");
            }
            for (int j = i; j < 9; j++) {
                System.out.printf("*");
            }
            System.out.println();
        }
    }
}
```



### Lv3:

```Java
public class Lv3 {
    public static void main(String[] args) {
        int[] array1 = {123, 156, 187};
        int[] array2 = {145, 154, 199, 201};

        int length = array1.length + array2.length;
        int [] array3 = new int[length];

        for (int i = 0; i < length; i++) {
            if (i<3){
                array3[i] = array1[i];
            }else {
                array3[i] = array2[i-3];
            }
        }

        for (int i = 0; i < 7; i++) {
            for (int j = i+1; j < 7; j++) {
                if (array3[i]>array3[j]){
                    int temp = array3[i];
                    array3[i] = array3[j];
                    array3[j] = temp;
                }
            }
        }
        for (int a :
                array3) {
            System.out.println(a);
        }
        System.out.println(array3[3]);
    }
}
```





内部资料，请珍惜我们的劳动成果，请勿外传。

© 红岩网校工作站移动开发部 