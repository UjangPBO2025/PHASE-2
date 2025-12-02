# PHASE 2 HEALTH SURVIVOR
📌 Deskripsi Umum

Health Survivor adalah game survival adventure yang berlatar di sebuah kota yang mengalami kekacauan akibat wabah kuman yang menyebar dengan cepat. Pemain berperan sebagai seorang survivor yang harus bertahan hidup dengan mengumpulkan makanan, menjaga stamina, menghindari musuh, dan memanfaatkan vitamin untuk mendapatkan efek immune sementara.
Game ini dikembangkan sebagai prototype gameplay tahap awal untuk mengeksplorasi mekanik dasar seperti movement, stamina, item pickup, serta interaksi dengan musuh.

🎮 Genre
Survival Adventure
Game ini berfokus pada eksplorasi sederhana, manajemen stamina, dan bertahan hidup dari musuh yang mengurangi energi pemain.

👥 Target Audience
Game ditujukan untuk remaja, khususnya pemain pemula yang ingin merasakan pengalaman sederhana bertahan hidup dalam lingkungan 3D.

🖥 Platform
Windows (PC/Laptop)

⚙ Core Mechanics 
Beberapa mekanik inti yang telah diimplementasikan:

1. Basic Movement
Berjalan
Berlari (mengurangi stamina)
Melompat
Kamera mengikuti player (TPS/FPS)

2. Stamina System
Stamina berkurang saat sprint
Regenerasi stamina saat idle
Makan makanan → memulihkan stamina
Vitamin → memberikan efek immune sementara

3. Item Pickup
FoodItem: memulihkan stamina
VitaminItem: memberi efek kebal terhadap damage musuh
Sistem berbasis Trigger Collider + inheritance (ItemBase)

4. Enemy Interaction
Enemy memberi damage saat bersentuhan
Sistem damage terhubung ke PlayerStats

5. Minimal Prototype Level
Player, enemy, food, vitamin
Lingkungan masih berupa arena dasar (belum desain kota)

🧩 Fitur yang Sudah Berjalan
Movement responsif menggunakan CharacterController
Third-person camera follow
Switching kamera FPS/TPS
UI Stamina yang dinamis (slider)
Damage system
Pickup system berbasis inheritance
Immune system
Main menu + load scene ke level

Struktur Folder Proyek
Assets
Scripts (Player, Item, UI)
Prefabs
Scenes (Menu, Puzzle, Dialog)
Audio
Materials
User Interface

🛠 Teknologi yang Digunakan
Unity (versi terbaru 6000.x)
C# scripting
CharacterController
Unity UI System (Canvas, Slider)
Scene Management
