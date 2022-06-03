# Bootcamp-Santander-Bootcamp-Fullstack-Developer
conversão do código média aluno do Portugol para o Java
import java.util.Locale;
import java.util.Scanner;

public class media_aluno {
    public static void main(String[] args) {

        Locale.setDefault(Locale.US);
        Scanner sc = new Scanner(System.in);

        double a, b, nota_a, nota_b;

            System.out.println("Digite as notas da p1 e p2 do aluno A: ");
            a = sc.nextDouble();
            b = sc.nextDouble();
            System.out.println("Digite as notas da p1 e p2 do aluno B: ");
            nota_a = sc.nextDouble();
            nota_b = sc.nextDouble();

            //double media_alunoA = (a+b)/2;
            //double media_alunoB = (nota_a+nota_b)/2;
            System.out.println("Média do aluno A: " + String.format("%.1f",media_aluno(a,b)));
            System.out.println("Média do aluno B: " + String.format("%.1f",media_aluno(nota_a,nota_b)));
        }

        static double media_aluno(double nota_a, double nota_b) {
        return (nota_a + nota_b)/2;
        }
    }
