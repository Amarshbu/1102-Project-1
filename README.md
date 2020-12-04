/******************************************************************************

Austin Marshburn, Peter Mancici, Daniel Pickett
1102-001
Project 1

*******************************************************************************/
/*
#include <stdio.h>

int main()
{
    int iPeople;
    
    printf("How many people are in your party? ");
    scanf("%d", &iPeople);
    
    printf("Your party has a size of %d.\n\n", iPeople);
    
        if(iPeople = 1)
        {
            printf("Please sit at bar seat.\n");
        }
        
        else if(iPeople = 2)
        {
            printf("Please sit at small table.\n");
        }
        
        else if(iPeople = 3 || 4)
        {
            printf("Please sit at medium table.\n");
        }
        
        else if(iPeople = 5 || 6)
        {
            printf("Please sit at large table.\n");
        }
        
        else if(iPeople = 7 || 8)
        {
            printf("Please sit at a booth.\n");
        }
        
        else
        {
            printf("Please wait 45 minutes or make a reservation for later.\n");
        }
        

    return 0;
}
******************************************************************
*/

#include <stdio.h>

int main()
{
    int iPeople;
    
    printf("How many people are in your party? ");
    scanf("%d", &iPeople);
    
    printf("Your party has a size of %d.\n\n", iPeople);

        switch (iPeople)
    {
         case 1:
            printf("Case1");
            break;
         case 2:
            printf("Case2");
            break;
         case 3:
            printf("Case3 or 4");
            break;
         case 5:
            printf("Case5 or 6");
            break;
         default:
            printf("Default ");
    }
    return 0;
}






