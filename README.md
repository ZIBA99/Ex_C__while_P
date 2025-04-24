#include <stdio.h>

//예제 1번
int main(void)
{
	int a;
	int num = 1;

	printf("정수를 입력 하시오: ");
	scanf_s("%d", &a);

	while (num <= a)
	{
		printf("Hello World!\n");
		num++;
	}
	return 0;
}

//예제 2번
int main(void)
{
	int a;
	int num = 1;

	printf("양수를 입력 하시오: ");
	scanf_s("%d", &a);

	while (num <= a)
	{
		printf("%d\n", 3*num);
		num++;
	}
	return 0;
}

//예제 3번

int main(void)
{
    int integer = 0;
    int add = 0;
    printf("정수 입력 : ");
    scanf_s("%d", &integer);
    add = integer + add;

    while (integer != 0) {
        printf("정수 입력 : ");
        scanf_s("%d", &integer);
        add = integer + add;
    }
    printf("합은 %d\n", add);

    return 0;
}
