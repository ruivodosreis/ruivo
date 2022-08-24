# ruivo
https://ruivodosreis.github.io/ruivo/
import static java.lang.System.out;
import java.util.Scanner;

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author Aluno
 */
public class seila {
  public static void main(String[] args){
  Scanner entrada = new Scanner(System.in);
  double salario = 1000.00;
  int total_carros;
      System.out.println("Infome a quantidade de carros vendidos");
      total_carros = entrada.nextInt();
      
      if (total_carros<=5){
          total_carros = total_carros*500;
          salario = salario+total_carros;
          System.out.println("valor do salario com a comissão"+ salario);
                  
      }
      else{
          total_carros = total_carros*1000;
          salario =salario+total_carros;
          System.out.println("valor do salario com a comissão"+ salario);

      }
  }
