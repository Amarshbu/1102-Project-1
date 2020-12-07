/******************************************************************************

Austin Marshburn, Peter Mancini, Daniel Pickett
1102-001
Project 1
This program asks the user for their party size. Depending on the party size, 
the program decides where they should sit at.

*******************************************************************************/

#include <stdio.h>

int main()
{
    int iPeople;
    
    printf("************* |WELCOME| *************\n");
    printf("How many people are in your party? ");
    scanf("%d", &iPeople);
    
    printf("Your party has a size of %d person(s).\n\n", iPeople);
    
        if(iPeople == 1)
        {
            printf("      Please sit at a bar seat.\n");
        }
        
        else if(iPeople == 2)
        {
            printf("     Please sit at a small table.\n");
        }
        
        else if(iPeople >= 3 && iPeople <= 4)
        {
            printf("    Please sit at a medium table.\n");
        }
        
        else if(iPeople >= 5 && iPeople <= 6)
        {
            printf("     Please sit at a large table.\n");
        }
        
        else if(iPeople >= 7 && iPeople <= 8)
        {
            printf("       Please sit at a booth.\n");
        }
        
        else if(iPeople >= 9)
        {
            printf("Please wait 45 minutes or make a reservation for later.\n");
        }
        
        else if(iPeople == 0)
        {
            printf("    Come dine at our restaurant!\n");
        }
        
        else
        {
            printf("    Please pick a positive number!\n");
        }
    
    printf("************ |THANK YOU| ************\n");

    return 0;
}
