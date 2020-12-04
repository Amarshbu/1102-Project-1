/******************************************************************************

Austin Marshburn, Peter Mancici, Daniel Pickett
1102-001
Project 1

*******************************************************************************/
#include <stdio.h>

int main()
{
    int iPeople;
    
    printf("How many people are in your party? ");
    scanf("%d", &iPeople);
    
    printf("Your party has a size of %d.\n", iPeople);
    
        if(iPeople = 1){
            printf("Please sit at bar seat.\n");
        }
        
        if(iPeople = 2){
            printf("Please sit at small table.\n");
        }
        
        if(iPeople = 3 || 4){
            printf("Please sit at medium table.\n");
        }
        
        if(iPeople = 5 || 6){
            printf("Please sit at large table.\n");
        }
        
        if(iPeople = 7 || 8){
            printf("Please sit at a booth.\n");
        }
        
        if(iPeople > 8){
            printf("Please wait 45 minutes or make a reservation for later.\n");
        }
        

    return 0;
}
