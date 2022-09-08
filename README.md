# count-space-in-a-String-c
#include<iostream>
using namespace std;
int main()
{
	string st="this is a string";
	cout<<st<<endl;
	int c=0;
	int l=st.length();
	if(l==0)
	{
		return 0;
	}
	for(int i=0;i<l-1;i++)
	{
	//	char ch=st.charAt(i);
		if(st[i]==' ')
		{
			c++;
		}
	}
	cout<<c;

}
