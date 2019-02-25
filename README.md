#include<bits/stdc++.h>
using namespace std;
#define ll long long int
int main()
{

             ll i,n,k,fi,ti,j=-1000000000,a=-1000000000,l1=-1000000000,l2=-1000000000;
              cin>>n>>k;
              for(i=0;i<n;i++)
              { cin>>fi>>ti;
                 if(ti>=k)
                 {j=fi-(ti-k);
                 }
                 else
                 {
                 	a=fi;
				 }
				 if(l1<j)
				 {
				 	l1=j;
				 }
				 if(l2<a)
				 {
				 	l2=a;
				 }
			}
               if(l1>l2)
               {printf("%d",l1);}
               else
               {printf("%d",l2);}
             
}
