#include<bits/stdc++.h>
using namespace std;
int main()
{
	int f[1001],a[1001];
	int i,j,m,n,k;
	cin>>n>>m;
	for(i=1;i<=n;i++)
	   cin>>a[i];
	memset(f,0,sizeof(f)); 
	f[0]=1;
	for(i=1;i<=n;i++)
	   for(j=a[i];j<=m;j++)
	      f[j]+=f[j-a[i]];
	cout<<f[m]<<endl;
	return 0;
}
