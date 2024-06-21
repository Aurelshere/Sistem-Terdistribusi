# TUBES SISTEM TERDISTRIBUSI - 1203210098 FRIDA SUKMA, 1203210118 YAYUK AGUSTINA
## Virtualisasi
1. Persiapan server host
```bash
  sudo apt install -y build-essential linux-headers-$(uname -r)
```
2. Mengganti sources list ubuntu
```bash
  sudo nano /etc/apt/sources.list
```
![Screenshot (752)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/c7d63888-c444-4586-a98a-288cd4eca317)

lalu update
```bash
  sudo apt update; sudo apt upgrade -y
```
3. Install lxc lalu lakukan cek konfigurasi
```bash
  sudo apt-get install lxc lxctl lxc-templates net-tools  
```
![Screenshot (779)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/f6daf812-2a3a-4656-8d05-386c9e57a7d1)

4. Membuat container ubuntu dengan nama server1ubuntu
```bash
  sudo lxc-create -n server1ubuntu -t ubuntu  
```

Menjalankan container

![Screenshot (783)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/08fda7f2-2c77-4ab3-83a9-687d9b840c5e)

5. Masuk ke console container dan jalankan update

![Screenshot (784)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/3b94ceb9-3c49-4475-831e-a23383d62616)

6. Tampilkan container yang tersedia

![Screenshot (785)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/ae3ca6ee-cebb-410b-b51b-4fb586541a0d)

## Static IP

1. Cek network
![Screenshot (811)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/cadf635e-0e06-4d13-bca7-3ddaf66fc560)

2. Setup IP statis
![Screenshot (812)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/954463b6-504a-4039-a14d-113e269ba043)
```bash
  sudo netplan apply
  ifconfig  
```
```bash
  ping 1.1.1.1
  ping google.com  
```

3. Buat lxc dengan nama ubuntu_php5.6
![Screenshot (815)](https://github.com/Aurelshere/Sistem-Terdistribusi/assets/129272687/7e475c9c-54ed-4b73-9b51-475a6d0e066e)
