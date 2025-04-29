Penulis: [Naufal](https://x.com/0xfal)

# Tutorial Menghubungkan VPS lewat Windows Terminal

## 1. Requirements

### Software

PC atau laptop dengan Windows:

| ✅ Windows 11 | ❓ Windows 10 (untested) |
| ------------- | ------------- |

### OpenSSH Client

Cari di pengaturan Windows `Optional features`.

![image](https://github.com/user-attachments/assets/9526784e-d5cd-4281-a7b2-67a4a5632b8e)

Cek, apakah `OpenSSH Client` sudah terinstal di PC atau laptop kalian.

![image](https://github.com/user-attachments/assets/d6db7940-252a-4443-8bcb-2e2b2d2f1c13)

Kalau belum, kalian bisa instal dulu dengan klik tombol `View features` di bagian paling atas.

![image](https://github.com/user-attachments/assets/52b690e9-664c-4ba8-815c-384d75b59cd3)

## 2. Execution

### 2.1 Open Windows Terminal

Buka Terminal, cari di pencarian Windows biar gampang.

![image](https://github.com/user-attachments/assets/d203c623-ef17-46f6-8804-1e4805ad0111)

### 2.2 Connecting

Ubah `<YOUR_VPS_USERNAME>` sesuai dengan username VPS-mu, dan ubah `<YOUR_VPS_IP>` juga sesuai dengan IP address VPS-mu.

```
ssh <YOUR_VPS_USERNAME>@<YOUR_VPS_IP>
```

Setelah menjalankan perintah itu, nanti akan muncul pertanyaan `Are you sure you want to continue connecting (yes/no/[fingerprint])?`, jawab aja `yes`.
Setelah itu, kamu akan diminta memasukkan password VPS-mu.

> [!WARNING]
> Untuk pengguna VPS-nya Contabo:\
> Password VPS yang dimaksud bukan VNC password yang dikirim Contabo lewat email ya! Melainkan password yang pertama kali kamu isi saat membeli.

---

Reach us if you have any question:\
ZuperCollective's [Discord server](https://discord.gg/ZuperCollective) | [X(Twitter)](https://twitter.com/ZuperCollective)
