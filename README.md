rockstar@suvi

This is my first Git Repository
<br>
Author - suvi tiwary
void main()
{
int i, ar[MAX];
clrscr();
// for input values 
for(i=0;i<MAX;i++)
{
printf("Plz Enter value for ar[%d] : ",i); 
scanf("%d",&ar[i]);
}
printf("\n\n List of array elements - "); 
for(i=0;i<MAX;i++) 
printf("%d, ",ar[i]); 
getch();
}


#define MAX 3 
void main()
{
int i,j,k, a[MAX][MAX],b[MAX][MAX],c[MAX][MAX]={0};
clrscr(); 
for(i=0;i<MAX;i++)
{
printf("Plz Enter 1st Matrix row %d : ",i+1); 
for(j=0;j<MAX;j++)
scanf("%d",&a[i][j]);
}
for(i=0;i<MAX;i++)
{
printf("Plz Enter 2nd Matrix row %d : ",i+1); 
for(j=0;j<MAX;j++)
scanf("%d",&b[i][j]);
}
// algo of Multi of matrix.
for(i=0;i<MAX;i++) 
for(j=0;j<MAX;j++)
for(k=0;k<MAX;k++)
c[i][j] += a[i][k] * b[k][j]; 
printf("\nMulti of Matrix - \n\n"); 
for(i=0;i<MAX;i++)
{
printf("\n\t"); 
for(j=0;j<MAX;j++)
printf("%3d ",c[i][j]);
}
getch();
}


#define MAX 10 
void main()
{
int i,ar[MAX],sum=0; 
float avg; 
clrscr();
// loop for input values 
for(i=0;i<MAX;i++)
{
printf("Enter value for ar[%d] : ",i); 
scanf("%d",&ar[i]);
}
printf("\n\nAll Elements r - ");
for(i=0;i<MAX;i++)
{
printf("%d, ",ar[i]); 
sum = sum + ar[i];
}
avg = (float)sum/MAX;
printf("\n\nSum of all elements r = %d",sum); 
printf("\n\nAverage of all elements r = %f",avg); 
getch();
}


hello Rockstar today _ 
make project

