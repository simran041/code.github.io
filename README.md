# code.github.io

#include <iostream>
using namespace std;

int main() {
	//code
	int t;
	scanf("%d",&t);
	while(t--)
	{
		int n;
		cin>>n;
		int a[n],sum,i,j;
		cin>>sum;
		for( i=1;i<n+1;i++)
		{
	
			cin>>a[i];
		
		}
	
		for( i=1;i<n+1;i++)
		{
			int s=0;
			for(j=i;j<n+1;j++)
			{
				s=s+a[j];
				if(s==sum)
				{
					cout<<i;
					cout<<j;
	
				}
			
			
			
			}

		
		}
		
		
		

	}
	return 0;
}
