#include<bits/stdc++.h>
using namespace std;
int max(int a,int b)
{
	return a>b?a:b;
}
int main()
{
	int c[1001],s[1001],w[1001],f[1001];
	int m,n,i,j,k;
	cin>>m>>n;
	for(i=1;i<=n;i++)
	   cin>>w[i]>>c[i]>>s[i];
	memset(f,0,sizeof(f));
	for(i=1;i<=n;i++)
	   if(s[i]==0)
	      {
	      	for(j=w[i];j<=m;j++)
	      	   f[j]=max(f[j],f[j-w[i]]+c[i]);
		  }
		else
		{
		   for(k=0;k<=s[i];k++)
			for(j=m;j>=w[i];j--)
			      f[j]=max(f[j],f[j-w[i]]+c[i]);
	}
	cout<<f[m]<<endl;
	return 0;
}
