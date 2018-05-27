#include <stdio.h>
#include <string.h>
#include <math.h>

int isPalindrome(char s[])
{
    int l = 0,temp = 0;
    int h = strlen(s) - 1;
    while (h > l)
    {
        if (s[l++] != s[h--])
        {
            temp = 1;
            return temp;
        }
    }
    return temp;
}

int main()
{
    char s[100];
    scanf("%[^\n]%*c", s);
    int l = strlen(s);
    if((int)(sqrt(l))*(int)(sqrt(l))==l){
        int temp = isPalindrome(s);
        if(temp == 1) printf("NO\n");
        else printf("YES\n");
    }
    else
    printf("NO\n");
    return 0;
}
