# Electric Remote-Controlled Boat System
![electrical](/images/electrical.jpg)
## Deskripsi
Sistem ini adalah perancangan kapal yang dikendalikan menggunakan remote control dengan sumber tenaga listrik. Sistem ini memanfaatkan beberapa komponen utama untuk mengontrol pergerakan kapal dan memastikan kelancaran operasinya.

---

## Diagram Sistem
Sistem terdiri dari **9 komponen utama** yang saling terhubung untuk menjalankan fungsi penggerak dan kontrol kapal secara optimal.

---

## Komponen Utama

### 1. Battery
- Sumber daya listrik utama untuk seluruh sistem.  
- Memberikan daya ke **Boost/Buck Converter** untuk menyesuaikan kebutuhan tegangan komponen lainnya.

### 2. Boost/Buck Converter
- Mengatur tegangan dari baterai agar stabil dan sesuai dengan kebutuhan masing-masing komponen, seperti ESC dan Receiver.

### 3. ESC (Electronic Speed Controller)
- Mengontrol kecepatan dan arah motor BLDC berdasarkan sinyal dari Receiver.  
- Berfungsi sebagai penghubung antara motor BLDC dan sistem kontrol.

### 4. BLDC Motor
- Mengubah energi listrik menjadi energi mekanik untuk menggerakkan **Propeller**.

### 5. Propeller
- Menghasilkan gaya dorong untuk menggerakkan kapal maju atau mundur di air.  
- Diputar oleh **BLDC Motor**.

### 6. Receiver
- Menerima sinyal kontrol dari **Remote/Transmitter** dan meneruskannya ke **ESC** dan **Servo**.  
- Menjadi penghubung antara pengguna dan komponen kapal.

### 7. Remote/Transmitter
- Perangkat pengendali jarak jauh yang mengirimkan perintah ke **Receiver** untuk mengatur kecepatan dan arah kapal.

### 8. Servo
- Mengontrol posisi **Rudder** berdasarkan sinyal dari **Receiver**.  
- Memungkinkan kapal untuk berbelok ke kiri atau kanan.

### 9. Rudder
- Berfungsi sebagai kemudi untuk mengatur arah kapal.  
- Posisi **Rudder** dikontrol oleh **Servo**.

---

## Alur Kerja Sistem

### 1. Penyediaan Daya
- **Battery** menyediakan daya ke seluruh sistem.
- Tegangan distabilkan oleh **Boost/Buck Converter** untuk digunakan oleh komponen seperti **ESC** dan **Receiver**.

### 2. Pengendalian Jarak Jauh
- Pengguna menggunakan **Remote/Transmitter** untuk mengirimkan sinyal kontrol ke **Receiver**.

### 3. Distribusi Sinyal
- **Receiver** mendistribusikan sinyal ke:  
  - **ESC**, untuk mengatur kecepatan dan arah putaran **BLDC Motor**.  
  - **Servo**, untuk mengontrol posisi **Rudder**.

### 4. Pergerakan Kapal
- **ESC** mengatur putaran **BLDC Motor**, yang memutar **Propeller** untuk menggerakkan kapal.
- **Servo** mengatur orientasi **Rudder**, menentukan arah kapal.

### 5. Navigasi Kapal
- Kapal bergerak sesuai kombinasi kontrol pada **Propeller** dan **Rudder**, berdasarkan perintah dari **Remote/Transmitter**.

---

## Daftar Pustaka
Raharja, L. P. S., Darmawan, A., Kristio, P., & Nugroho, P. (2023). Rancang Bangun Prototipe Kapal Elektrik Dengan Sistem Kendali Jarak Jauh. *Jurnal Teknologi Terpadu, 11*(1), 1-xx. ISSN: 2338-6649.




# Remote-Controlled Fuel Engine Boat System
![fuel engine](/images/fuel.jpg)
## Deskripsi
Sistem ini adalah perancangan dan implementasi dari kapal berbahan bakar mesin yang dikendalikan secara jarak jauh menggunakan remote control. Kapal ini dilengkapi dengan berbagai komponen elektronik dan mekanik yang bekerja secara bersama-sama untuk memastikan kontrol yang baik.

---

## Diagram Sistem
Sistem ini terdiri dari **11 komponen utama**, yang masing-masing memiliki fungsi spesifik dalam mendukung operasi kapal.

---

## Komponen Utama

1. **Battery**
   - Menyediakan daya listrik untuk semua komponen elektronik, seperti receiver, servo, motor, dan lainnya.
   - Tegangan dari baterai dikendalikan agar sesuai kebutuhan dengan bantuan Boost/Buck Converter.

2. **Boost/Buck Converter**
   - Mengatur tegangan dari baterai agar stabil sesuai dengan kebutuhan masing-masing komponen elektronik, seperti Receiver dan Motor.

3. **Remote/Transmitter**
   - Mengirimkan sinyal kontrol dari pengguna ke kapal.
   - Sinyal ini mencakup perintah untuk mengatur gas mesin (**Linear Actuator**) dan arah kapal (**Servo**).

4. **Receiver**
   - Menerima sinyal dari **Remote/Transmitter**.
   - Mendistribusikan perintah ke:
     - **Servo**, untuk mengontrol **Rudder** (kemudi kapal).
     - **Linear Actuator**, untuk mengontrol gas pada mesin.

5. **Gas Tank**
   - Menyimpan bahan bakar yang disuplai ke **Fuel Engine**.
   - Memastikan mesin dapat bekerja terus-menerus selama bahan bakar tersedia.

6. **Propeller**
   - Mengubah tenaga mekanis dari **Fuel Engine** menjadi gaya dorong untuk menggerakkan kapal di atas air.

7. **Rudder**
   - Berfungsi sebagai kemudi untuk mengarahkan kapal.
   - Orientasi **Rudder** dikontrol oleh **Servo**, memungkinkan kapal berbelok ke kiri atau kanan.

8. **Servo**
   - Mengontrol posisi **Rudder**, yang menentukan arah kapal sesuai perintah dari remote control.

9.  **Linear Actuator**
    - Mengontrol gas pada kapal.
   

10. **Water Pump**
    - Berfungsi untuk memompa air, yang biasanya digunakan untuk sistem pendinginan mesin atau aplikasi lainnya.
    - Digunakan bersama **Motor**, yang menggerakkan pompa untuk menjaga aliran air yang stabil.

---

## Alur Kerja Sistem

1. **Battery** menyediakan daya ke seluruh sistem. Tegangan dari baterai distabilkan dengan **Boost/Buck Converter** sebelum dialirkan ke komponen lainnya.

2. Pengguna menggunakan **Remote/Transmitter** untuk mengirimkan sinyal kontrol ke **Receiver**.

3. **Receiver** menerima sinyal kontrol dari remote dan meneruskannya ke:
   - **Servo**, untuk mengontrol arah kapal melalui **Rudder**.
   - **Linear Actuator**, untuk mengatur gas pada supaya bisa berjalan.

4. **Propeller** menghasilkan gaya dorong yang memungkinkan kapal bergerak di atas air.

5. Arah kapal dikendalikan oleh **Rudder**, yang posisinya diatur oleh **Servo**, sesuai perintah dari remote.

6. Maju kapal diatur melalui **Linear Actuator**, yang mengontrol gas pada kapal.

7. **Water Pump**, digerakkan oleh **Motor**, memompa air yang dapat digunakan untuk sistem pendinginan mesin atau aplikasi lainnya.

---

## Daftar Pustaka

- Adwinda, E. G. (2024). RC Boat Fuel Engine. Tidak diterbitkan.

---


# Magang Implementasi bahasa C

         #include <stdio.h>
         #include <stdint.h>

         // =======================
         // Kasus 1: Penjumlahan Variabel
         // =======================
         void kasus1() {
            int a = 1, b = 2;
            int calculate;

            // Operasi penjumlahan
            calculate = a + b; // a=1, b=2, calculate = 3
            printf("Kasus 1: Hasil penjumlahan a dan b adalah: %d\n", calculate);

            // Modifikasi nilai a
            a = a + 1; // a sekarang bernilai 2
            printf("Kasus 1: Nilai a setelah ditambah 1 adalah: %d\n\n", a);
         }

         // =======================
         // Kasus 2: Input dan Output Variabel
         // =======================
         void kasus2() {
            int integer1;
            printf("Kasus 2: Masukkan sebuah bilangan bulat: ");
            scanf("%d", &integer1); // Mengambil input dan menyimpannya ke integer1
            printf("Kasus 2: Bilangan yang Anda masukkan adalah: %d\n\n", integer1);
         }

         // =======================
         // Kasus 3: Ukuran Memori dan Tipe Data
         // =======================
         void kasus3() {
            uint8_t eightBitVariable = 250; // Memakai 8-bit memori
            unsigned int unsignedInt = 255; // Standar 32-bit untuk unsigned int
            printf("Kasus 3: eightBitVariable: %d, ukuran memori: %lu bytes\n", eightBitVariable, sizeof(eightBitVariable));
            printf("Kasus 3: unsignedInt: %u, ukuran memori: %lu bytes\n\n", unsignedInt, sizeof(unsignedInt));
         }

         // =======================
         // Kasus 4: Operasi Float dan Pembagian
         // =======================
         void kasus4() {
            float floatValue1 = 20.0f;
            float floatValue2 = 30.0f;
            float dividedValue = floatValue1 / floatValue2; // 20 / 30 = 0.666...
            printf("Kasus 4: Hasil pembagian %.2f / %.2f adalah: %.2f\n\n", floatValue1, floatValue2, dividedValue);
         }

         // =======================
         // Kasus 5: Manipulasi String dan Karakter
         // =======================
         void kasus5() {
            char stringArray[][6] = {"Arund", "Taib", "Anton"}; // Array string dengan elemen tetap
            printf("Kasus 5: Nama ketiga pada array string adalah: %s\n", stringArray[2]);

            // Menampilkan setiap karakter dalam string
            printf("Kasus 5: Karakter-karakter dalam nama ketiga:\n");
            for (int i = 0; stringArray[2][i] != '\0'; i++) { // Iterasi hingga null terminator
               printf("%c ", stringArray[2][i]);
            }
            printf("\n\n");
         }

         // =======================
         // Kasus 6: Operasi Aritmatika
         // =======================
         void kasus6() {
            int a = 5, b = 2;
            printf("Kasus 6: Operasi Aritmatika\n");
            printf("%d + %d = %d\n", a, b, a + b);
            printf("%d - %d = %d\n", a, b, a - b);
            printf("%d * %d = %d\n", a, b, a * b);
            printf("%d / %d = %d\n", a, b, a / b);
            printf("%d %% %d = %d\n\n", a, b, a % b);
         }

         // =======================
         // Kasus 7: Operasi Bitwise
         // =======================
         void kasus7() {
            unsigned int a = 5, b = 9;
            printf("Kasus 7: Operasi Bitwise\n");
            printf("a & b = %u\n", a & b);
            printf("a | b = %u\n", a | b);
            printf("a ^ b = %u\n", a ^ b);
            printf("~a = %u\n", ~a);
            printf("b << 1 = %u\n", b << 1);
            printf("b >> 1 = %u\n\n", b >> 1);
         }

         // =======================
         // Kasus 8: Percabangan
         // =======================
         void kasus8() {
            int nilai;
            printf("Kasus 8: Percabangan\n");
            printf("Masukkan nilai ujian: ");
            scanf("%d", &nilai);

            if (nilai >= 80) {
               printf("Nilai : A\n");
            } else if (nilai >= 70) {
               printf("Nilai : B\n");
            } else if (nilai >= 60) {
               printf("Nilai : C\n");
            } else {
               printf("Nilai : D\n");
            }
            printf("\n");
         }

         // =======================
         // Kasus 9: Perulangan dan Sorting
         // =======================
         void kasus9() {
            int arr[5] = {10, 2, 5, 11, 3};
            int tmp;

            printf("Kasus 9: Perulangan dan Sorting (Bubble Sort)\n");
            printf("Array sebelum sorting: ");
            for (int i = 0; i < 5; i++) {
               printf("%d ", arr[i]);
            }
            printf("\n");

            for (int i = 0; i < 5 - 1; i++) {
               for (int j = 0; j < 5 - i - 1; j++) {
                     if (arr[j] > arr[j + 1]) {
                        tmp = arr[j + 1];
                        arr[j + 1] = arr[j];
                        arr[j] = tmp;
                     }
               }
            }

            printf("Array setelah sorting: ");
            for (int i = 0; i < 5; i++) {
               printf("%d ", arr[i]);
            }
            printf("\n\n");
         }

         // =======================
         // Kasus 10: Switch Case
         // =======================
         void kasus10() {
            int hari;
            printf("Kasus 10: Switch Case\n");
            printf("Masukkan angka (1-7) untuk memilih hari: ");
            scanf("%d", &hari);

            switch (hari) {
               case 1:
                     printf("Hari Senin\n");
                     break;
               case 2:
                     printf("Hari Selasa\n");
                     break;
               case 3:
                     printf("Hari Rabu\n");
                     break;
               case 4:
                     printf("Hari Kamis\n");
                     break;
               case 5:
                     printf("Hari Jumat\n");
                     break;
               case 6:
                     printf("Hari Sabtu\n");
                     break;
               case 7:
                     printf("Hari Minggu\n");
                     break;
               default:
                     printf("Hari tidak valid\n");
                     break;
            }
            printf("\n");
         }

         int main() {
            // Menjalankan semua kasus secara berurutan
            kasus1();
            kasus2();
            kasus3();
            kasus4();
            kasus5();
            kasus6();
            kasus7();
            kasus8();
            kasus9();
            kasus10();

            return 0;
         }
         // End of program

# Magang Electrical Design
## Schematics Design
![Schematics](/images/Shematics.png)

## PCB Layout
![PCB Layout](/images/PCBlayout.png)

## 3D Print Out
![3D Print](/images/3Dlayout.png)