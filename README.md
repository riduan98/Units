# Units
Units tx
Install Python
sudo apt update && sudo apt install git
sudo apt install python3 python3-pip && pip install requests python-dotenv eth_account colorama
Clone Github
git clone https://github.com/jamikoas/units-tx-bot.git
cd units-tx-bot
Buat File .env
nano .env
Paste dan Ubah
PRIVATE_KEY=PK-KALIAN
SENDER_ADDRESS=ALAMAT-PENGIRIM-KALIAN
CTRL X + Y Untuk Simpan
Jalankan Dan Mulai Transaksi
python3 units.py
