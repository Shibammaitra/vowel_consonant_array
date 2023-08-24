# vowel_consonant_array
To read a string and then to separated vowels and consonant in separate array
#include<stdio.h>
int main()
{
	char st[1],vo[1],con[1];  //array declaration
	int i,j;    
	for(i=0;i<1;i++)
	{   
	    printf("enter a number :");  //input charachter
		scanf("%c",&st[i]);
	    for(i=0;i<1;i++)
	    {
	    	if(st[i]=='A'||st[i]=='E'||st[i]=='I'||st[i]=='O'||st[i]=='U'||st[i]=='a'||st[i]=='e'||st[i]=='i'||st[i]=='o'||st[i]=='u')
	    	{
	    		printf("Vowel\n");    //print vowel
	    		for(j=0;j<1;j++)
	    		{
	    			vo[j]=st[i];     //assign vowel value
				}
				for(j=0;j<1;j++)
				{
					printf("%c",vo[j]);    //check 2nd array value
				}
			}
			else 
			{
				printf("Consonant\n");    //print consonant
				for(j=0;j<1;j++)
	    		{
	    		     con[j]=st[i];      //assign consonant value
				}
				for(j=0;j<1;j++)
				{
					printf("%c",con[j]);     //check 3rd array value
				}
			}
		}
	}
	return 0;
}
