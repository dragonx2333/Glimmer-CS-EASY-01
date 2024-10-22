代码块：

~~~c
#include <stdio.h>
int main()
{
    unsigned int m = 0;
    unsigned int n = 0;
    unsigned int r = 0;
    scanf_s("%d %d", &m, &n);
    while (m%n)
    {
        r = m % n;
        m = n;
        n = r;
    }
    printf("%d\n", n);
    return 0;
}

~~~

