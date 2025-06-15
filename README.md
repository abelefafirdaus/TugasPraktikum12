📝 ToDoList with Reminder – Android App

Sebuah aplikasi ToDo sederhana berbasis Android yang memungkinkan pengguna menambahkan tugas sekaligus menyetel pengingat waktu untuk tiap tugas.

![screenshot](![Screenshot 2025-06-15 205918](https://github.com/user-attachments/assets/00aa877e-1359-4684-8ffc-aa2e427fae1d) 



## 🚀 Fitur Utama

- ✅ Menambahkan tugas harian
- 🕒 Memilih waktu pengingat dengan TimePicker
- 🔔 Notifikasi pengingat otomatis
- 🗂 Menampilkan daftar tugas dalam RecyclerView
- ✏️ Edit dan hapus tugas langsung dari daftar

---
📱 Tampilan UI

- Desain bersih dan minimalis menggunakan `LinearLayout`
- Input tugas dan tombol pengingat dalam satu halaman
- RecyclerView untuk menampilkan daftar tugas

---

📂 Struktur Folder Penting

```bash
📦 app/
 ┣ 📜 MainActivity.java          # Main logic: input, alarm, list
 ┣ 📜 ReminderReceiver.java     # Menangani notifikasi
 ┣ 📜 TaskAdapter.java          # Adapter RecyclerView dengan edit/delete
 ┣ 📜 Task.java                 # Model data tugas
 ┣ 📁 res/layout/
 ┃ ┣ 📜 activity_main.xml       # Layout utama
 ┃ ┗ 📜 item_task.xml           # Layout item dalam daftar tugas
 ┗ 📜 AndroidManifest.xml       # Permission & deklarasi komponen
