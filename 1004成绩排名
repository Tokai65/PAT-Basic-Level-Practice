#include<stdio.h>
#include<stdlib.h>
struct student
{
	char name[15];
	char IDnumber[15];
	int score;
};
typedef struct student student;
int main(int argc,char **argv)
{
	int cnt;
	scanf("%d",&cnt);
	student max={"","",0},min={"","",100};
	while(cnt--)
	{
		student new;
		scanf("%s%s%d",new.name,new.IDnumber,&new.score);
		if(new.score>max.score)
			max=new;
		if(new.score<min.score)
			min=new;
	}
	printf("%s %s\n",max.name,max.IDnumber);
	printf("%s %s\n",min.name,min.IDnumber);
	return EXIT_SUCCESS;
}
