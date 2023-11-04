# AssignmentCoding1

## Nomor 1
program ini akan mencetak angka dari 1 sampai 9 dan kemudian mencetak string "Abid Al Husain" sebanyak 91 kali.
```sh
   for (int nilai = 1; nilai <= 9; nilai++) {

            System.out.println(nilai);
        }
        for (int nilai = 10; nilai <= 100; nilai++){

            System.out.println("Abid Al Husain");
        }
   ```

## Nomor 2
Program tersebut merupakan penentu angka termasuk dalam genap atau termasuk ganjil.
```sh
     public static void main(String[] args) {
        // TODO code application logic here
        int count = 1;

        while (count <= 10) {
            if (count % 2 == 0) {
                System.out.println(count + " is an even number.");
            } else {
                System.out.println(count + " is an odd number.");
            }
            count++;
```
## Nomor 3
program array
public static void main(String[] args) {
        // TODO code application logic here
        // Membuat sebuah variabel dengan tipe data array
        int[] array = {1, 2, 3, 4, 5};

        // Menggunakan perulangan for untuk menampilkan semua nilai dalam variabel array
        for (int i = 0; i < array.length; i++) {
            System.out.println(array[i]);
        }
    }
## Nomor 4
Program tersebut memungkinkan pengguna untuk memasukkan tanggal lahir dan bulan, dan kemudian menentukan zodiak yang sesuai. 
```sh
   public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Masukkan tanggal lahir Anda (dd-mm-yyyy): ");
        String[] dateParts = scanner.nextLine().split("-");
        int day = Integer.parseInt(dateParts[0]);
        int month = Integer.parseInt(dateParts[1]);

        String zodiacSign;

        if ((month == 1 && day >= 20) || (month == 2 && day <= 18)) {
            zodiacSign = "Aquarius";
        } else if ((month == 2 && day >= 19) || (month == 3 && day <= 20)) {
            zodiacSign = "Pisces";
        } else if ((month == 3 && day >= 21) || (month == 4 && day <= 19)) {
            zodiacSign = "Aries";
        } else if ((month == 4 && day >= 20) || (month == 5 && day <= 20)) {
            zodiacSign = "Taurus";
        } else if ((month == 5 && day >= 21) || (month == 6 && day <= 20)) {
            zodiacSign = "Gemini";
        } else if ((month == 6 && day >= 21) || (month == 7 && day <= 22)) {
            zodiacSign = "Cancer";
        } else if ((month == 7 && day >= 23) || (month == 8 && day <= 22)) {
            zodiacSign = "Leo";
        } else if ((month == 8 && day >= 23) || (month == 9 && day <= 22)) {
            zodiacSign = "Virgo";
        } else if ((month == 9 && day >= 23) || (month == 10 && day <= 22)) {
            zodiacSign = "Libra";
        } else if ((month == 10 && day >= 23) || (month == 11 && day <= 21)) {
            zodiacSign = "Scorpio";
        } else if ((month == 11 && day >= 22) || (month == 12 && day <= 21)) {
            zodiacSign = "Sagittarius";
        } else {
            zodiacSign = "Capricorn";
        }

        System.out.println("Zodiak Anda adalah: " + zodiacSign);

        // Menggunakan perulangan for untuk menampilkan semua nilai dalam variabel array
        for (int i = 0; i < array.length; i++) {
            System.out.println(array[i]);
        }
    }
   ```
