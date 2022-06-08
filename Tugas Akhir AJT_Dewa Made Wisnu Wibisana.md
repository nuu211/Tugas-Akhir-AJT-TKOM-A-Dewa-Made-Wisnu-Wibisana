# Tugas-Akhir-AJT-TKOM-A-Dewa-Made-Wisnu-Wibisana

Dewa Made Wisnu Wibisana

195150300111027

Arsitektur Jaringan Terkini - TKOM A


## Tugas 1 - Membuat Instance dan Instalasi OpenFlow, Mininet dan Ryu

![image](https://user-images.githubusercontent.com/99487952/172600255-9a28f0fe-55b3-4871-9f0d-0a11d5e010af.png)
![image](https://user-images.githubusercontent.com/99487952/172600296-5e21c397-eabe-48ff-af22-38b9c27dfaa7.png)

Membuat instance dan menginisialisasinya, dengan spesifikasi :

-Nama : Tugas Akhir

-OS Image : Ubuntu Server 22.04 LTS 64-bit

-Instance type : t2.medium

-Keypair : vockey

-Edit network settings : allow SSH, allow HTTP, allow HTTPS, allow TCP port 8080, allow TCP port 8081

-Konfigurasi penyimpanan : 30 GiB, gp3


![image](https://user-images.githubusercontent.com/99487952/172600755-6b0dfc98-b07b-46d2-a1fb-d6e39e938c03.png)

![image](https://user-images.githubusercontent.com/99487952/172600859-7774a723-6180-48d5-b9c8-6e71c12b9920.png)

Memastikan Mininet, Ryu, Flowmanager dan OpenFlow telah ter-install dan uji koneksi antara host dan switch

![image](https://user-images.githubusercontent.com/99487952/172600922-cc39f19a-f308-40be-a7f5-ae35c6549c48.png)

Menguji coba salah satu perintah sederhana mininet (help)

Pada tugas 1 ini, saya ditugaskan untuk membuat sebuah instance EC2 di AWS Console sesuai dengan spesifikasi sesuai dengan yang tertera

## Tugas 2 - Mininet Custom Topology

![image](https://user-images.githubusercontent.com/99487952/172603928-7a33d609-10f5-4400-b66b-7ccc2e4d771d.png)

Pada tugas 2 ini, saya ditugaskan untuk membuat sebuah custom topology, lalu dilanjutkan dengan membuat flow antara host 1 dengan host 2 dan diuji koneksinya

## Tugas 3 - Ryu Load Balancer

![image](https://user-images.githubusercontent.com/99487952/172606238-45f404ec-598c-4eb8-b702-2684ceaaee57.png)

![image](https://user-images.githubusercontent.com/99487952/172607219-1d043459-ae55-485d-bb0b-6091c1362587.png)

![image](https://user-images.githubusercontent.com/99487952/172606279-848aece0-10b5-473a-88a2-694dcf7a2c31.png)

Pada tugas 3 ini, saya ditugaskan untuk membuat sebuah load balancer, yang merupakan proses pembagian beban traffic pada sebuah aplikasi atau server. Dengan adanya load balancer, beban traffic tidak akan dibebankan ke beberapa jalur koneksi, sehingga keseluruhan pemrosesan menjadi lebih cepat dan efisien serta mencegahnya dari overloading.


## Tugas 4 - Shortest Path Routing

Tampilan terminal 1 :

![image](https://user-images.githubusercontent.com/99487952/172608395-925a48df-5820-4b95-b07f-5e940288ec8e.png)

![image](https://user-images.githubusercontent.com/99487952/172608422-47cbae14-75e5-4bc2-8a1a-725e43294a88.png)

![image](https://user-images.githubusercontent.com/99487952/172608967-428747b8-1ccc-4ec2-a8e1-06c731b298de.png)

Tampilan terminal 2 :

![image](https://user-images.githubusercontent.com/99487952/172609245-f97db450-5395-4f3f-b8e6-6aa174411a76.png)

Pengujian koneksi (h1 ping -c 4 h4)

Tampilan terminal 1 :

![image](https://user-images.githubusercontent.com/99487952/172609479-e63265b4-bdcd-4043-aa9a-069ae8428aec.png)

Tampilan Terminal 2 :

![image](https://user-images.githubusercontent.com/99487952/172609539-07505227-8e96-4c06-adbb-d93d66e76fb6.png)

Pengujian koneksi (h5 ping -c 4 h6)

Tampilan terminal 1 :

![image](https://user-images.githubusercontent.com/99487952/172610150-80e0f109-a52b-40eb-8105-11a1fba16b1f.png)

Tampilan Terminal 2 :

![image](https://user-images.githubusercontent.com/99487952/172610197-4dd549c3-a42e-4afa-ae4d-65f9c057d272.png)

Pada tugas 4 ini, kita diajarkan tentang cara pengaplikasian SPF Routing, yang merupakan algoritma routing di mana router menghitung jalur terpendek antara setiap pasangan node yang terdapat di dalam jaringan. Protokol Open Shortest Path First (OSPF) dibuat berdasarkan algoritma Shortest Path First (SPF)



