#include <stdio.h>

int main()
{
    int i, j, cur, lastDigit, n;
    long long fact, sum;

    printf("Enter number ");
    scanf("%d", &n);

    printf("Strong numbers between 1 to %d are:\n", n);
    
    for(i=1; i<=n; i++)
    {
        cur = i;

        sum = 0;
 
        while(cur > 0)
        {
            fact = 1ll;
            lastDigit = cur % 10;

            for( j=1; j<=lastDigit; j++)
            {
                fact = fact * j;
            }

            sum += fact; 

            cur /= 10;
        }
        
        if(sum == i)
        {
            printf("%d\t ", i);
        }
    }

    return 0;
}
