#include<bits/stdc++.h>
using namespace std;
int max(int a,int b)
{
	return a>b?a:b;
 } 
 int main()
 {
 	
 	int m,n,i,j,k;
 	bool b[1001];
 	int s[1001],w[1001],c[1001],f[1001];
 	cin>>n>>m;
	memset(f,0,sizeof(f));
	memset(b,true,sizeof(b));
 	for(i=1;i<=n;i++)
 	   cin>>w[i]>>c[i]>>s[i];
 	for(i=1;i<=n;i++)
 	   for(j=i+1;j<=n;j++)
 	     if((w[j]>w[i])&&(c[i]<c[j]))
 	     	b[i]=false;
 	for(i=1;i<=n;i++)
 	   for(j=m;j>=0;j--)
 	      for(k=0;k<=s[i];k++){
		   
 	         if(j-k*w[i]<0||b[i]==false) break;
			  else f[j]=max(f[j],f[j-k*w[i]]+k*c[i]);
		}
			  cout<<f[m]<<endl; 
 }
