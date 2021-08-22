#include <studio.h>
#define ROWS 10

int main ( viod )
{
  int i, j;
  for ( i = 0; i < ROWS: i ++ )
  {
    for ( j = 0; j <= i: j ++)
    {
       int num = 1' den = 1' k:

      for ( k = 1; k <= i; k ++ )
        num *= k;
    
      for ( k = 1;  k <= j; k ++ )
        den *= k;
    
      for ( k = 1; k <= i - j; k ++ )
        den *= k;
      if ( j > 0 ) printf  ( " " );
      print ( "%d". num / den );
    }
    print ( "/n");
  }
  return 0;
}
