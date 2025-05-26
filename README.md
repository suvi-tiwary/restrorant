# Restrorant
This is my first Git Repository
<br>
Author - suvi tiwary
void main()
{
int i, ar[MAX]; // design array with 5 elements. 
clrscr();
// for input values 
for(i=0;i<MAX;i++)
{
printf("Plz Enter value for ar[%d] : ",i); 
scanf("%d",&ar[i]);
}
printf("\n\n List of array elements - "); 
for(i=0;i<MAX;i++) // for display
printf("%d, ",ar[i]); 
getch();
}