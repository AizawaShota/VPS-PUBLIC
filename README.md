# VPS_RDP_Windows


- Spesifikasi : VPS 2 Core CPU - 7GB RAM
- Durasi      : 6 Jam
- OS          : Windows 10 - Server 2019


# Step Menggunakan VPS:

- Masuk/Buat akun Ngrok kalian di https://dashboard.ngrok.com/
- Jika sudah klik Settings > Secrets > New repository secret lalu buat dengan nama NGROK_AUTH_TOKEN, untuk value pastekan Token NGROK kalian
- Klik Add Secrets
- Lalu klik Action > CI > Run workflow, setelah itu klik CI > build
- Tunggu hingga proses pembuatan VPS selesai lalu akan muncul IP, User, Password

# Note

- Jika tidak keluar IP maka coba gunakan TOKEN lain atau jangan gunakan satu token secara bersamaan 
- Jika ingin menggunakan Banyak VPS, maka gunakan TOKEN yang berbeda, disarankan membuat akun NGROK dengan email sementara (https://emailfake.com/)
- Jika masih tidak mau berjalan maka buat akun github lg :)
