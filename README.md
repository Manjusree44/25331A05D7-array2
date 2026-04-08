
#include<stdio.h>
int main(){
int a[10][10], i,j, rows, cols;
printf(“25331a05d7\n”);
printf("enter the rows and colms");
scanf("%d %d", &rows, &cols);
for(i= 0; i < rows; i++){
for(j = 0; j < cols;j++){
scanf("%d", &a[i][j]);
}
}
printf("matrix is : \n");
for(int i = 0; i <rows; i++){
for(int j = 0; j < cols; j++){
printf("%d", a[i][j]);
}
printf("\n");
}
return 0;
}

