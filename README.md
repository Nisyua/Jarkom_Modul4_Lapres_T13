# Jarkom_Modul4_Lapres_T13

* Anis Saidatur Rochma 05311840000002
* Desya Ananda Puspita Dewi 05311840000046
---
### Soal
- Soal shift dikerjakan pada Cisco Packet Tracer dan UML menggunakan metode perhitungan CLASSLESS yang berbeda
  - **CLOUD** diberikan IP TUNTAP yaitu `10.151.76.76/30`
  - **Server** diberikan IP DMZ `10.151.77.152/29`

### Cisco Packet Tracker VSLM
- Buat topologi sesuai soal di CPT, lalu tentukan subnet.

  ![](https://github.com/Nisyua/Jarkom_Modul4_Lapres_T13/blob/main/img/Soal%20Shift%20Modul%204.png)

- Tentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan lakukan labelling netmask berdasarkan jumlah IP yang dibutuhkan.

  |  SUBNET | JUMLAH IP | NETMASK |
  | :-----: | :-------: | :-----: |
  |    A1   |	   721    |	  /22   |
  |    A2   |	   252    |	  /24   |
  |  **A3** |	  **2**   |	**/30** |
  |    A4   |	    2     |	  /30   |
  |    A5   |	   521    |	  /22   |
  |    A6   |	    13    |	  /28   |
  |    A7   |	   502    |	  /23   |
  |    A8   |	    2     |	  /30   |
  |    A9   |	   101    |	  /25   |
  |    A10  |	   2021   |	  /21   |
  |    A11  |	   701    |	  /22   |
  |    A12  |	    2     |	  /30   |
  |    A13  |	    2     |	  /30   |
  |  **A14**|	  **2**   |	**/30** |
  |    A15  |    1001   |	  /22   |
  |**Total**|  **5845** | **/19** |

  *note: Untuk Subnet A3 dan A14 merupakan server Mojokerto dan Malang*

  ![](https://github.com/Nisyua/Jarkom_Modul4_Lapres_T13/blob/main/img/topo-vlsm.png)

- Hitung pembagian IP menggunakan tree seperti dibawah
  
  ![](https://github.com/Nisyua/Jarkom_Modul4_Lapres_T13/blob/main/img/vlsm.png)


