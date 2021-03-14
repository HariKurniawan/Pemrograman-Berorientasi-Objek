class Kalkulator {
    public static void main(String[] args) throws Exception {
        Scanner input = new Scanner(System.in);
        int number1, number2, choice, result = 0;
        System.out.println("Program Kalkulator Sederhana");
        System.out.println("1. Penjumlahan");
        System.out.println("2. Pengurangan");
        System.out.println("3. Pembagian");
        System.out.println("4. Perkalian");
        System.out.println("5. Sisa Bagi");
        System.out.println("-----------------------------");
 
        System.out.println("Masukkan Angka Pertama: ");
        number1 = input.nextInt();
        System.out.println("Masukkan Angka Kedua: ");
        number2 = input.nextInt();
  
        switch (choice)
        {
            case 1 : result = number1 + number2; break;
            case 2 : result = number1 - number2; break;
            case 3 : result = number1 / number2; break;
            case 4 : result = number1 * number2; break;
            case 5 : result = number1 % number2; break;
            default : System.out.println("Salah Memasukkan Pilihan !!");
        }
        System.out.println("Hasil : " + result);
    }
}
