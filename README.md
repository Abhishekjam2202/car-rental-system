#include<stdio.h>
#include<conio.h>
void main()
{
    int u,d,r,l,k;
    char name[50],n;
    int age,contact;
    printf("Enter your name:");
    scanf("%[^\n]*c",name);
    printf("Enter your age:");
    scanf("%d",&age);
    printf("Enter your contact:");
    scanf("%d",&contact);
    printf("Name=%s\n",name);
    printf("age=%d\n",age);
    printf("contact=%d\n",contact);
    printf("\n CAR RENTAL APPLICATION \n");
    printf("\n ----------------------- \n");
    printf("\n Press 1 for Deluxe Vehicles \n");
    printf("\n Press 2 for OFF-ROAD Vehicles \n");
    printf("\n Press 3 for Luxury Vehicle \n");
    printf("\n ---------------------------- \n");
    printf("\n Press any Option: \n");
    scanf("%d", &u);
    switch(u)
    {
        case 1:
        printf("\n You have chosen Deluxe Vehicles \n");
        printf("\n Deluxe Vehicle Available are \n");
        printf("\n SWIFT DEZIRE,SAFARI ,ECO SPORT \n");
        printf("\n ------------------------------ \n");
        printf("\n DO you want to hire, Press 1 |SWIFT DEZIRE , 2 | SAFARI, 3 | ECO SPORT \n");
        scanf("%d", &d);
        switch(d)
        {
            case 1:
            printf("\n You have selected SWIFT DEZIRE | Cost 4000rs per day \n GOODBYE! Today's work is over now.\n **THANK YOU** \n");
            break;

            case 2:
            printf("\n You have selected SAFARI | Cost 5000rs per day \n GOODBYE! Today's work is over now.\n **THANK YOU** \n ");
            break;

            case 3:
            printf("\n You have selected ECO SPORT | Cost 15,000 per day \n GOODBYE! Today's work is over now.\n **THANK YOU** \n ");
            break;
        }
        break;

        case 2:
        printf("\n You have chosen OFF-ROAD Vehicles \n");
        printf("\n Vehicles Available are \n");
        printf("\n THAR, GYPSY, RUBICON  \n");
        printf("\n ----------------------------- \n");
        printf("\n do u want to hire , press 1 | THAR, 2 | GYPSY, 3 | RUBICON \n");
        scanf("%d", &r);
        switch (r)
        {
            case 1:
            printf("\n You have selected THAR | Cost 9000rs per day \n GOODBYE! Today's work is over now.\n **THANK YOU** \n");
            break;

            case 2:
            printf("\n You have selected GYPSY | Cost 12,000rs per day \n GOODBYE! Today's work is over now.\n **THANK YOU** \n");
            break;

            case 3:
            printf("\n You have selected RUBICON| Cost 10,000rs per day \n GOODBYE! Today's work is over now.\n **THANK YOU** \n");
            break;

        }
        break;

        case 3:
        printf("\n You have chosen Luxury Cars");
        printf("\n Luxury Vehicles Available are \n");
        printf("\n MERCEDES BENZ, BMW X5, AUDI A4 \n");
        printf("\n ------------------------------ \n");
        printf("\n Do u want to hire, Press 1 | MERCEDES BENZ, 2 | BMW X5, 3 | Audi A4\n");
        scanf("%d", &l);
                switch(l)
        {
            case 1:
            printf("\n You have selected MERCEDES BENZ | Cost 40,000rs per day \n GOODBYE! Today's work is over now.\n **THANK YOU** \n ");
            break;

            case 2:
            printf("\n You have selected BMW X5| Cost 45,000rs per day \n GOODBYE! Today's work is over now.\n **THANK YOU** \n ");
            break;

            case 3:
            printf("\n You have selected AUDI A4| Cost 50,000rs per day\n GOODBYE! Today's work is over now.\n **THANK YOU** \n");
            break;

        }
        break;
    getch();

    }
}
