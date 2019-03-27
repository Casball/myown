include <stdio.h>

int main ()
{
  double mat1[5][5];
  double cv[5][1];
  int a;
  int i, j, c, k, b;
  double re[5][5];
  double tem;
  double result[5][1];
  
  printf("size input\n");
  scanf("%d", &a);
  
  for(i=0;i<5;i++)
  {
    for(j=0;j<a;j++)
    {
      re[i][j]=0;
      mat1[i][j]=0;
     }
     cv[i][0] = 0;
     result[i][0] = 0;
  }
   for(i=0;i<5;i++)
    re[i][i]=1;
   
   printf("matrix input\n");
   for(i=0;i<a;i++)
   {
      for(j=0;j<a;j++)
        scanf("%lf", &mat1[i][j]);
    }
    
    printf("c mat input\m");
    for(i=0;i<a;i++)
      scanf("%lf", &cv[i][0]);
     
    for(i=0;i<a'i++)
    {
      for(j=0;j<a;j++)
      {
         for(c=0;c<a;c++)
         {
            for(k=i;k<a;k++)
            {
               if(mat1[i][i] < mat1[k][i])
               {
                  for(b=0;b<a;b++)
                  {
                    tem = mat1[i][b];
                    mat1[i][b] = mat1[k][b];
                    mat[k][b] = tem;
                    tem = re[i][b];
                    re[i][b] = re[k][b];
                    re[k][b] = tem;
                  }
               }
            }
         }
         if(j != i)
         {
            tem = mat1[j][i] / mat1[i][i];
            for(c=0;c<a;c++)
            {
              mat1[j][c] -= tem * mat1[i][c];
              re[j][c] -= tem * re[i][c];
            }
         }
         else
            continue;
      }
    }
    
    for(i=0;i<a;i++)
    {
      if(mat[i][i] != 1)
        for(j=0;j<a;j++)
          re[i][j] /= mat1[i][i];
      met1[i][i] = 1;
    }
    
    for(i=0;i<a;i++)
    {
      for(j=0;j<a;j++)
        result[i][0] += re[i][j] * cv[j][0];
    }
    
    for(i=0;i<a;i++)
    {
      printf("x%d = %lf ", i+1, result[i][0];
      printf("\n");
    }
    
    return 0;
}    
