#include<iostream>
#include<bits/stdc++.h>
using namespace std;

int main()
{
	int p,v,m,n,t,i,j,k;
	int w[1001],c[1001],f[1001],a[101][101];
	cin>>v>>n>>t;
	memset(a,0,sizeof(a));
	memset(f,0,sizeof(f));
    for(i=1;i<=n;i++)
       {
       	cin>>w[i]>>c[i]>>p;
       	a[p][++a[p][0]]=i;
	   }
	for(i=1;i<=t;i++)
	   for(j=v;j>=0;j--)
	      for(k=1;k<=a[i][0];k++)
	         if(j>=w[a[i][k]])
	    {
	    	int temp=a[i][k];
	    	if(f[j]<f[j-w[temp]]+c[temp])
	    	   f[j]=f[j-w[temp]]+c[temp];
		}
		cout<<f[v]<<endl;
		return 0;
}
