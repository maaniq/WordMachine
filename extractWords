#include <stdio.h>
#include <string.h>
char *extractedWords[50];
int i, wordCount = 0;
int main ()
{
  char str[] ="12 ght 34 98 23 dfg";
  char * token;
  printf ("Extracted given string - \"%s\" into words:\n",str);
  token = strtok (str," ");
  while (token != NULL)
  {
    extractedWords[i] = token;
    i++;
    wordCount++;
    token = strtok (NULL, " ");
  }
  
  for(i=0;i < wordCount;i++)
  {
    printf(" %s\n",extractedWords[i]);
  }
  return 0;
}
