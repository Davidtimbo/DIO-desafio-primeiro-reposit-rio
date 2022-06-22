# DIO-desafio-primeiro-repositório

Alguns códigos  que fiz em C :
/*Faça um programa que leia 3 números e imprima uma das seguintes mensagens:Todos os números são iguais,Todos os números são diferentes ou Apenas dois números são iguais.*/

    #include <stdio.h>    
      int main()      {


    printf("Entre com um valor: "); 
          scanf("%d",&a);
  
    printf("Entre com outro valor: ");
      scanf("%d",&b);
  
    printf("Entre com outro valor: ");
      scanf("%d",&c);

    if (a == b && a == c)
      printf("Todos são iguais");

      else if (a==b || a==c || b==a || b==c || c==a || c==b)
        printf("Apenas dois são iguais"); 

      else      
        printf("Todos sao diferentes");
          }


  /* 7 Entrar com um número e informar se é divisível por 10, ou é divisível por 5, ou é divisível por 2 ou se não é divis l por nenhum destes.*/
  
          #include <stdio.h>    
            int main(){
        
         int n1;
     printf("digite um numero ");
      scanf("%d",&n1);

    if (n1 % 10 == 0 ) { 
      printf("É divisivel por 10\n");
      }
 
    else if (n1 % 5 == 0) { 
      printf("É divisivel por 5 \n");
      }
  
    else if (n1 % 2 == 0) { 
        printf("É divisivel por 2");
      }
      
       else {   
        printf("Não é divisivel por nenhum desses");
      }
      }



/*Faça um programa que leia 3 números e imprima uma mensagem dizendo se
correspondem aos lados de um triângulo. */

        #include <stdio.h>    
        int main(){
        
      float a, b, c;  

    printf("Digite 3 numeros: ");
      scanf("%f %f %f",&a,&b,&c);

    if (( a < b + c) && (b < a + c) && (c < a + b))
      printf("%.2f %.2f %.2f podem ser lados de um triangulo",a,b,c);
    else
      printf("%.1f %.1f %.1f não podem ser lados de um triangulos",a,b,c);
      }     
