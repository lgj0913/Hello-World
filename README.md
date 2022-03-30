//# Hello-World
//My first repository
//分支语句
#define_CRT_SECURE_NO_WARNINGS 1
#incude<stdio.h>
int main()
{
  int age = 100;
  if(age<18)
  {
    printf("未成年\n");
    printf("不能谈恋爱\n");
  }
   else
   {
      if(age >= 18 && age < 28)
        printf("青年\n");
       else if(age >= 28 && age < 50)
        printf("中年\n");
       else if(age >= 50 && age < 100)
        printf("老年\n");
       else
        printf("老不死\n");
   }
}

/*int main()
{
	int i = 1;
	while (i <= 100)
	{
		if (i % 2 == 1)
			printf("%d ", i);
		i++;
	}
	return 0;
}
*/
