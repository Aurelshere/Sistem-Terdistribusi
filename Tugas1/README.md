# Tugas 1 - Mencoba LXC [1203210098 FRIDA SUKMA]
1. Persiapkan Server host untuk linux, jika terdapat peringatan -> package tidak ditemukan, maka ubah source listnya dan jangan lupa lakukan 'sudo apt update; sudo apt upgrade -y' setelahnya.
   
![Screenshot (638)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/386a68fc-6603-407b-9ade-f5600f73e260)

2. Install LXC

![Screenshot (641)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/17fbab2f-4254-4583-97f5-91c37f2abeb0)

3. Cek konfigurasi (seluruhnya harus berstatus 'enabled')

![Screenshot (642)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/4782159a-0f95-4cf3-b912-a4dbddc330a7)

4. Install nginx

![Screenshot (644)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/7d95008e-ce45-4f91-adb8-d23d0a25a31d)

5. Create Directory

![Screenshot (645)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/0d849914-1dfd-4695-ba2d-05b053cedbfc)

6. Mengubah isi server_name menjadi sister.local

![Screenshot (646)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/024702fe-1927-4c1b-ab35-8e522a6b8ae3)

7. Membuat isi laman yang akan ditampilkan pada web

![Screenshot (650)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/f22df092-3299-49ce-bdc3-d6aea12119af)

 ![Screenshot (651)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/b52cb2dc-d8ce-4002-ac09-f30e0952c32c)

8. Selanjutnya mengubah isi dalam file 'hosts' dengan menambah ip 'sister.local', web server 'sister.local' dapat dibuka.

![Screenshot (654)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/8006a78e-ccf7-4f2c-8efd-33698e514af9)

9. Membuat microservice1 dan microservice2

![Screenshot (655)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/c88fdd76-9441-4381-9129-cc6ad564c31e)

10. Menyimpan IP masing-masing microservices untuk nantinya di set menjadi IP static

![Screenshot (660)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/49bf2bcc-00a2-4be6-9da0-13475bf8ba59)

11. Mengubah isi laman yang akan ditampilkan sebagai Blog

![Screenshot (663)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/ea2c8ec8-6450-4381-b07a-50e05436acd8)

12. Mengubah isi laman yang akan ditampilkan sebagai About Us

![Screenshot (665)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/63d3f397-6b61-40af-af79-11472462b849)

13. Membuat mcsv1.local dan mcsv2.local

![Screenshot (673)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/39fef88f-0f6b-4e6e-94cd-5d341edac315)

14. Mendaftarkan IP mcsv1.local dan mcsv2.local pada UBUNTU utama

![Screenshot (675)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/93a6c9e7-a18a-491b-b297-c0a11e526bfa)

![Screenshot (677)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/9948b1ec-74ee-4cf6-a713-58d4971cd68d)

15. Web server sister.local/blog dan sister.local/aboutus dapat diakses

![Screenshot (678)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/3b561906-d2f1-4231-9895-c04356e8eb3b)

![Screenshot (679)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/4bb392f0-b99c-40c6-ab92-ecac0c7b27d5)
