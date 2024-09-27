Penulis: [Naufal](https://x.com/0xfal)

# Tutorial Menghubungkan VPS lewat Windows Terminal

## 1. Needs

PC atau laptop dengan Windows:

| ✅ Windows 11 | ❓ Windows 10 (untested) |
| ------------- | ------------- |

## 2. Dependencies

Cari di pengaturan Windows `Optional feature`.

![image](https://github.com/user-attachments/assets/a9803db9-814d-4e95-b783-e9851c957237)

Cek, apakah `OpenSSH Client` sudah terinstal di PC atau laptop kalian.

![image](https://github.com/user-attachments/assets/d6db7940-252a-4443-8bcb-2e2b2d2f1c13)

Kalau belum, kalian bisa instal dulu dengan klik tombol `View features` di bagian paling atas.

![image](https://github.com/user-attachments/assets/52b690e9-664c-4ba8-815c-384d75b59cd3)

## 3. Executions

### 3.1 Open Windows Terminal

Buka Terminal, cari di pencarian Windows biar gampang.

![image](https://github.com/user-attachments/assets/d203c623-ef17-46f6-8804-1e4805ad0111)

### 3.2 Connecting

Ubah `YOUR_VPS_USERNAME` sesuai dengan username VPS-mu, dan ubah `YOUR_VPS_IP` juga sesuai dengan IP address VPS-mu.

```
ssh YOUR_VPS_USERNAME@YOUR_VPS_IP
```

Setelah menjalankan perintah itu, nanti akan muncul pertanyaan `Are you sure you want to continue connecting (yes/no/[fingerprint])?`, jawab aja `yes`.
Setelah itu, kamu akan diminta memasukkan password VPS-mu.

> [!WARNING]
> Untuk pengguna VPS-nya Contabo:\
> Password VPS yang dimaksud bukan VNC password yang dikirim Contabo lewat email ya! Melainkan password yang pertama kali kamu isi saat membeli.

---

Reach us if you have any question:\
ZuperHunt's [Discord server](https://discord.gg/ZuperHunt) | [X(Twitter)](https://twitter.com/ZuperHunt)
