# hello_people
just for fun 
#comment here
int i=0;
int j=0;
System.out.println("please enter the rows and column respectively");
i=in.nextInt();
j=in.nextInt();
System.out.println("pleased enter the array");
int a[][]=new int [i][j];
for(int k=0;k<i;k++)
{
for(int l=0;l<j;l++)
{
 a[k][l]=in.nextInt();
 }
 }
 for(int k=0;k<i;k++)
 {for(int l=0;l<j;l+=0
 { for(int m=k;k<i;k++)
 {for(int n=l;n<j;n++)
 {

 if(a[k][l]<a[m][n];
 { int temp=a[k][l];
 a[k][l]=a[m][n];
 a[m][n]=temp;
 }
 }
 }
 }
 }
 end
