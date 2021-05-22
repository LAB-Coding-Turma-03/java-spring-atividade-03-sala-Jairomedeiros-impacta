[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=4765742&assignment_repo_type=AssignmentRepo)
Elabore um algoritmo para dizer a partir da idade se a 
pessoa tem mais ou menos do que 18 anos.
Retornar os seguintes textos:
Para maiores de dezoito anos -> Possui mais de 18 anos
Para menores de dezoito anos -> Possui menos de 18 anos

package idade;
import java.util.Scanner;
public class Idade {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        
        int idade;
            System.out.println("Digite a idade: ");
            idade = ler.nextInt();
            
            if(idade >= 18){
                System.out.println("Maior de idade");
            }else{
                System.out.println("Menor de idade");
            }
    }
    
}
