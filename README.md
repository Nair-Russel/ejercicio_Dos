# Nair.De.La.Cruz.Chate-Ejercicio_Dos

import java.util.Scanner;

public class PerimetroRectangulo {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Introduce la longitud del rectángulo:");
        double longitud = scanner.nextDouble();

        System.out.println("Introduce la anchura del rectángulo:");
        double anchura = scanner.nextDouble();

        double perimetro = 2 * (longitud + anchura);

        System.out.println("El perímetro del rectángulo es: " + perimetro);

        scanner.close();
    }
}
