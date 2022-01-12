#include <stdio.h>
int main()
{
    long long int n, sum, first, last;
    printf("Enter the value here: ");
    scanf("%lld", &n);
    last = n % 10;
    while(n >= 10)
    {
        n = n / 10;
    }
    first = n;
    printf("The first & last digits are: %lld & %lld\n", first,last);
    sum = first+last;
    printf("Sum of first and last digits: %lld\n",sum);
    return 0;
}
