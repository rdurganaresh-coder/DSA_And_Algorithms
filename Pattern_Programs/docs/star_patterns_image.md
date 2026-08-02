# ⭐ Star Patterns


[⏪ Back to Pattern Page](../docs/Star_Patterns.md)

---

![Star Patterns](../images/star_patterns.png)

---
## P1. Square Star Pattern

```java
public static void squareStar(int n) {
        System.out.println("P1. Square Star Pattern (n=" + n + "):");
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < n; j++) System.out.print("* ");
            System.out.println();
           }
    }
```