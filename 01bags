#include<iostream>
using namespace std;
int max(int a,int b)
{
	return a>b?a:b;
}
int main()
{
	int f[1001];
	int w[1001],c[1001];
	int i,j,n,v,m,k;
	cin>>m>>n;
	for(i=1;i<=n;i++)
	   cin>>w[i]>>c[i];
	for(i=1;i<=n;i++)
	   for(v=m;v>=w[i];v--)
	     f[v]=max(f[v],f[v-w[i]]+c[i]);
    cout<<f[m];
    return 0;
 } 
