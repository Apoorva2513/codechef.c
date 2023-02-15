# codechef.c
#include <stdio.h>

int main(void) {
    int t,n,m,c=0;
    scanf("%d",&t);
    while(t--)
    {
        int c=0;
        scanf("%d%d",&n,&m);
        for(int i=1;i<=n;i++)
        {
            for(int j=1;j<=m;j++)
            {
                c++;
                j++;
            }
            i++;
        }
        printf("%d\n",c);
    }
	// your code goes here
	return 0;
}

