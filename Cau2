import java.util.Scanner;

public class Cau2 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int[] arrayNumber = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        int size = arrayNumber.length;

        for (int i = 1; i< arrayNumber.length; i++) {
            System.out.print(i + "\t");

        }
        for (int i = 0; i < arrayNumber.length / 2; i++) {
            int a = arrayNumber[i];
            arrayNumber[i] = arrayNumber[size - 1 - i];
            arrayNumber[size - 1 - i] = a;
        }

        System.out.printf("Dao nguoc thanh ", "");
        for (int i = 1; i < arrayNumber.length; i++) {
            System.out.print(arrayNumber[i] + "\t");
        }
    }
}
