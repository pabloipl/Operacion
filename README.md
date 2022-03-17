public class Operacion {
    public static void main(String[] args) {
        System.out.print("La suma es: " + Suma(2, 3) + "\n");
        System.out.print("La resta es: " + Resta(2, 3));
    }

    public static int Suma(int x, int y) {
        return x + y;
    }

    public static int Resta(int x, int y){
        return x-y;
    }
}
