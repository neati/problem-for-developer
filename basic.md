# 1번

```java
public class Main {
    public static void main(String[] args) {
        for (int i = 1; i < 6; i++) {
            for (int j = 1; j < 6; j++) {
                System.out.print((i / j) * (j / i));
            }
            System.out.println();
        }
    }
}
```

```java
// 나누기는 버림 처리된다.
// 예제
System.out.println(1 / 2); // 0
System.out.println(3 / 2); // 1
```

1. 위 코드의 결과를 작성하시오.
2. 위 코드에서 개선점이 보이는가? 개선점이 보인다면 개선된 코드를 작성하시오.

# 2번

다음에 대하여 설명하시오. (모두 작성할 필요 없이 정확하게 파악하는 내에서 작성)

1. Garbage Collection의 작동원리, 장점, 단점
2. Thread의 작동원리, 장점, 단점
