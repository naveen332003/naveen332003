/*Eg1:
input:a1b10
output:abbbbbbbbbb
Eg2:
input:b3c6d15
output:bbbccccccddddddddddddddd
*/
#include<stdio.h>
#include<string.h>
int main(){
	char str[100],c[100];
	int in[100],p,i,j,t=0,k=0,o=0;
	printf("Enter a sequence:");
	gets(a);
	p=strlen(a);
	for(i=0;i<p;){
	while(a[i]>='a'&&a[i]<='z'){
			c[o++]=a[i];   //array used to store character
			i++;
	}
t=0;
			while(a[i]>='0'&&a[i]<='9'){
			t=t+(a[i]-48);
			t=t*10;
			i++;
		}
		b[k++]=t/10;   //array used to store integer number
}
for(i=0;i<k;i++){
	for(j=0;j<b[i];j++){
	printf("%c",c[i]);
	}
}}
