class Operacion {   // se recomienda guardarlo en un archivo .java separado
  public static double[][] suma(double [][]matA, double [][] matB) {
    double[][] matR;

    // ... completar el desarrollo del método
    return matR;
  }

  public static double[][] producto(double [][]matA, double [][]matB) {
    double[][] matR;

    // ... completar el desarrollo del método
    return matR;
  }

  // ... continuar con los demás métodos
}

class Captura {   // se recomienda guardarlo en un archivo .java separado
  private Scanner leer = new Scanner();

  public static double nextDouble(String message) {
    System.out.print(message);
    return leer.nextDouble(message);
  }

  public static double [][] readMat(int filas, int cols) {
    double [][] matR = new double[filas][cols];

    // ... completar el desarrollo del método
    return matR;
  }
}

// Clase principal de la aplicación (por ello es la única  que contiene el método main)
class Implementacion {   // se recomienda guardarlo en un archivo .java separado

  public static void main(String args[]) {

    /*
       Montar aquí un menú repetitivo que maneje cada una de las opciones referidas.

       Dependiendo de la opción escogida, leer: dos matrices, una matriz y un escalar o,
       una sola matriz.

       Luego, proceder a realizar la operación correspondiente y presentar su resultado.

       Se recomienda usar las clases referidas anteriormente par facilitar el desarrollo
       del programa (algunos métodos se requiere completarlos)
    */

  }
}