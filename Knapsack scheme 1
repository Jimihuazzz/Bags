#include<bits/stdc++.h>
using namespace std;
int main()
{
	int f[1001],a[1001];
	int i,j,m,n,k;
	cin>>n>>m;
	for(i=1;i<=n;i++)
	   cin>>a[i];
	f[0]=1;
	for(i=1;i<=n;i++)
	  for(j=m;j>=a[i];j--)
	     for(k=1;k<=j/a[i];k++)
	        f[j]+=f[j-k*a[i]];
	cout<<f[m]<<endl;
	return 0;
}
