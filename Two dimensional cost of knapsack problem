#include<bits/stdc++.h>
using namespace std;

int main()
{
	int f[101][101],a[1001],b[1001],w[1001];
	int l,v,u,k,i,j,m,n;
    cin>>v>>u>>k;
    memset(f,127,sizeof(f));
    f[0][0]=0;
    for(i=1;i<=k;i++)
       cin>>a[i]>>b[i]>>w[i];
    for(i=1;i<=k;i++)
       for(j=v;j>=0;j--)
          for(l=u;l>=0;l--)
             {
             	int t1=a[i]+j;
             	int t2=b[i]+l;
             	if(t1>v) t1=v;
             	if(t2>u) t2=u;
             	if(f[t1][t2]>f[j][l]+w[i]) f[t1][t2]=f[j][l]+w[i];
			 }
			 cout<<f[v][u]<<endl;
}
