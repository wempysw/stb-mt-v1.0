# stb-mt-v1.0
STB Mining Tools V1.0

Syarat install:
-Login root
-semua password root wajib sama
-IP & MAC wajib Static
-Jaringan pada eth0 LAN atau kabel (bukan wireless atau wlan0!)

Fitur stb-mt-v1.0 :
1. Ganti wallet Luckpool dan Zergpool dari server.
2. Ganti mining pool dari server > sementara support hanya luckpool & zergpool.
2. Edit temperatur dari server > Jika mencapai max. temp autostop mining dan jika sudah menyentuh min. temp autostart mining.
3. Edit ping ip dari server > berguna untuk cek status interface lan agar selalu up jika bengong.
4. Start/stop automining semua stb dari server.
4. Full nonstop auto mining. saat power on, loss job atau bengong. Ga perlu reboot atau menurunkan clockspeed cpu.
5. Remote stb server dari ip publik > remote dari mana aja untuk akses ke ip stb server.
6. Auto generate nama worker berdasarkan nomor rig, nomor stb dan nomor belakang IP > mempermudah identifikasi stb.
7. Install ccminer, tools & automining ke semua stb client dari server.
8. Monitor realtime status semua stb sperti nama worker, suhu cpu, hashrate & uptime stb.
9. Otomatis kirim status semua stb setiap 6 jam sekali ke telegram bot atau secara manual.
10. Semua status aktifitas terkirim ke telegram bot & tersimpan di stb server.
11. Auto run stb-mt-v1.0 pada saat login ke stb server.
12. 1 server STB support up to 70 stb client.
