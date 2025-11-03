#include <stdio.h>

int main() {
     int coustmer_id, coustmer_telephone_no;
     char from_month[20], to_month[20];
     char status; char date[20]; 
     char coustmer_name[50]; 
     int choice;
     int unit_use, rate_per_unit, total;

printf("*************** ELECTRICITY BILL ****************\n");
printf("=================================================\n");

printf("Enter customer name: ");
scanf("%s", coustmer_name);
printf("Enter customer ID: ");
scanf("%d", &coustmer_id);
printf("Enter customer telephone number: ");
scanf("%d", &coustmer_telephone_no);
printf("Enter status (single character): ");
scanf(" %c", &status);

printf("=================================================\n");
printf("Customer Name: %s\n", coustmer_name);
printf("Customer ID: %d\n", coustmer_id);
printf("Customer Telephone No: %d\n", coustmer_telephone_no);
printf("Status: %c\n", status);
printf("=================================================\n");

printf("Consume from month: ");
scanf("%s", from_month);
printf("Consume to month: ");
scanf("%s", to_month);
printf("Enter the unit used: ");
scanf("%d", &unit_use);
printf("Enter the rate per unit: ");
scanf("%d", &rate_per_unit);

printf("=================================================\n");
total = rate_per_unit * unit_use;
printf("Total: %d\n", total);
printf("=================================================\n");
printf("******************* THANK YOU ********************\n");

return 0;
}
