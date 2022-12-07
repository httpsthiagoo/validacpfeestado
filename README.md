# validacpfeestado
#include <stdio.h>
int main(void){
    char num[11];

    printf("Digite seu CPF: ");
    scanf("%s", &num);

    printf("O documento foi emitido em: \n\n");

    switch(num[8])
    {
      
    case '1':
        printf("DF, GO, MS ou TO");
        break;
    case '2':
        printf("PR, AM, AC, AP, RO ou RR");
        break;
    case '3':
        printf("CE, MA ou PI");
        break;
    case '4':
        printf("PE, RN, PB ou AL");
        break;
    case '5':
        printf("BA ou SE");
        break;
    case '6':
        printf("MG");
        break;    
    case '7':
        printf("RJ ou ES");
        break;
    case '8':
        printf("SP");
        break;
    case '9':
        printf("PR ou SC");
        break;
    case '0':
        printf("RS");
        break;
    default:
        printf("ERRO");
        break;
    }
}
