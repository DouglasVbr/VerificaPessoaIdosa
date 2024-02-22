# VerificaPessoaIdosa


package verificapesoaidosa;
import java.util.Scanner;


public class VerificaPesoaIdosa {

    
    public static void main(String[] args) {
        
    Scanner Scanner = new Scanner(System.in);   
        
    // Solicita ao usuario que insira a idade
        System.out.println("Digite sua idade");
        int idade = Scanner.nextInt();
        // verifica se a pessoa é idosa
        if(idade>=60){
            System.err.println("voce é idosa(o).");
        }else{
            System.out.println("voce não é idosa(o).");
            
        }
        // fecha o Scanner
        Scanner.close();
        }
           }
