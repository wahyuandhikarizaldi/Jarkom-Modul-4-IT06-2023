# Jarkom-Modul-4-IT06-2023
**Modul 4 Jaringan Komputer 2023**

## Kelompok IT06
| Nama | NRP |
|---------------------------|------------|
|Wahyu Andhika Rizaldi | 5027211003 |
|Sedtia Prakoso Budi Tirto Arto | 5027211014 |

## Topologi
![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/ded5c991-1497-4edf-a546-a9f216b1892d)

## VLSM
## Topologi CPT
Tentukan subnet dari topologi, dengan metode VLSM.
![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/705bb670-0093-4462-8dd0-dfffac76f60d)

### Rute dan Subnet Mask
Tentukan subnet mask dari masing-masing subnet, dengan jumlah host yang dibutuhkan yang tercamtum di topologi.
![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/4ea47002-c4cf-41e7-9724-9295d2c92ca9)

### Konfigurasi IP
Buat perhitungan dari subnet mask dari masing-masing subnet untuk menentukan pembagian konfigurasi IP.
![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/4ff04c13-4dac-470e-a79e-88eeab162f7e)

### VLSM Tree
Berdasarkan konfigurasi IP yang sudah didapatkan, gambarkan tree VLSM nya.
![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/2c2c4633-cbdf-4e61-b50b-a6ccfa810ad4)

### Konfigurasi di CPT
1) Subnetting
   Atur IP interface dari router yang mengarah ke client.
   (Contoh: Subnet A2, Frieren -> Switch3 -> LakeKorridor)
   ![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/7ad90ecb-dc50-4411-b954-72d2be9f7adf)
   Atur IP interface dari client yang mengarah ke router.
   (Contoh: Subnet A2, LakeKorridor -> Switch3 -> Frieren)
   ![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/e2b876db-4800-4dbe-9a25-fd50e0f3a2d8)
   ![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/ca91bf8b-12cc-46ad-9c1f-671c2a854944)
   Atur IP interface dari router utama yang mengarah ke router subnet.
   (Contoh: Subnet A1, Aura -> Frieren)
   ![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/320e421c-9c7e-4b2e-a263-126b55154af8)
   Atur IP interface dari router subnet yang mengarah ke router utama.
   (Contoh: Subnet A1, Frieren -> Aura)
   ![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/4b9e023e-b2d4-419c-bd46-a54a76770f7d)
   Lakukan untuk semua subnet.

2) Routing
   Atur default routing dari router subnet ke router utama.
   (Contoh: Frieren -> Aura)
   ![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/0b5f2de4-ee3c-4c90-abff-97485bc67cc2)
   Atur routing dari router utama ke subnet client.
   (Contoh: Subnet A2, Aura -> Frieren)
   ![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/aebab359-1f79-487a-b107-4c50d4e9d572)
   Lakukan untuk semua subnet.

3) Testing
   Contoh, dilakukan testing dari LakeKorridor ke Aura.
   ![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/239f3695-8b1c-4f5b-b6c7-9eed0430662e)
   ![image](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/113814423/0d3c03b5-3294-456a-96cb-18288f92a23e)


## CIDR
## Topologi GNS
![CIDR](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/99130485/bed9d12c-4ccc-4484-b596-f8f726866f59)

### Konfigurasi IP
Buat perhitungan dari subnet mask dari masing-masing subnet untuk menentukan pembagian konfigurasi IP.
<img width="404" alt="image" src="https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/99130485/a9492bc3-85e3-4197-ae48-6038a75115fa">

### CIDR Tree
Berdasarkan konfigurasi IP yang sudah didapatkan, gambarkan tree CIDR nya.
![modul4-cidr-tree](https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/99130485/2cbf3444-511d-4d73-a418-83dc3c420a73)

### Penggabungan - CIDR
Pada CIDR terdapat proses penggabungan subnet IP dari terkecil hingga menjadi satu kesatuan subnet
<img width="359" alt="image" src="https://github.com/wahyuandhikarizaldi/Jarkom-Modul-4-IT06-2023/assets/99130485/fa9939eb-ed0d-4f91-9084-56c3b721b2fc">










   
