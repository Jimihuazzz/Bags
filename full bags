#include<iostream>
using namespace std;
int max(int a,int b)
{
	return a>b?a:b;
}
int main()
{
	int i,j,m,n,v;
	int f[1001],w[1001],c[1001];
	cin>>m>>n;
	for(i=1;i<=n;i++)
	   cin>>w[i]>>c[i];
	for(i=1;i<=n;i++)
	   for(v=w[i];v<=m;v++)
	      f[v]=max(f[v],f[v-w[i]]+c[i]);
	cout<<f[m]<<endl;
}
