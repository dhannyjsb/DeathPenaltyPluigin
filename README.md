# DeathPenaltyPluigin
Just for Check version
<br>
<a href="https://github.com/dhannyjsb/DeathPenaltyPluigin" align="center">
  <img align="center" src="https://img.shields.io/bstats/players/12267?color=red&style=for-the-badge">
    <img align="center" src="https://img.shields.io/bstats/servers/12267?color=red&style=for-the-badge">
  </a>

<a href="https://github.com/dhannyjsb/DeathPenaltyPluigin">
  <img align="center" src="https://bstats.org/signatures/bukkit/DeathPenaltyID.svg">
  </a>


# DeathPenalty

# DeathPenalty

TODO List:
- [X] Get region name di debug saat mati
- [X] Support java 11
- [X] Gunakan methode selain equal name untuk nama monster
- [X] Tambahan Placeholder
- [X] Support World Guard
- [X] World Guard Flags
- [X] Delete beberapa item ketika player mati -> masih perlu di check
- [X] Pisah message file
- [X] Support HEX Color
- [X] Kirim pesan death ketika respawn
- [X] cari cara update sql database saat update -> Dapat, tapi perlu dicheck lagi
- [X] Ubah group menjadi permission base
- [X] ActionBar, BossBarr di pesan death.
- [X] Drop money saat player mati
- [X] Tambahankan GUI untuk config
- [X] Bikin GUI tersendiri untuk type Monster
- [X] Bikin GUI tersendiri untuk type Item 
- [X] Jalankan command saat player mati
- [ ] Tambahankan sign board
- [ ] Set armor monster untuk zombie, skeleton, husk dll


Change log : v1.5.9 
- Ubah cara pewarna untuk Hex #abcdef#
- Fix ilegall blablablablaba wkwk
- FTambah InfoGUI

Change log : v1.5.8
- Add server command
- Fix health and food tidak berfungsi saat uang player di bawah minimal
- Ubah metode drop item saat keepinventory on dan beberapa perbaikan metodenya.
- Ubah layout item config
- perbaikan beberapa coding yang lumayan tidak dibutuhkan

Change log : v1.5.7
- Memperbaiki cek versi, operatornya kurang, maklum, gak pinter math wkwkw
- tambah GUI per item dan mobs. (Skill +) wkwkwk


Change log : v1.5.6
- Drop money saat player mati (item based)
- hapus player name monster prefix dan menambahkan placeholder %player%
- Perubahan metode enbale disable di GUI (buanyak cok) kwkwkwk
- Tambahnak GUI check update
- Ubah metode update, jika versi lebih besar dari versi di spigot, tidak muncul.

Change log : v1.5.5
- Menambahkan GUI untuk config
- ada perbaikain sedikit keasalhan code


Change log : v1.5.4
- Ubah Pergroup menjadi PerPermission (deathpenalty.group.xxxxx)
- Ubah UserPergroup menjadi UserPerPermission di config.yml
- Tambah penjelasna di config.yml
- Tambhan pengaturan ACtion_bar, BossBar, dan Chat di message.

Change log : v1.5.3.1
- Kirim pesan saat player respawn
- Bikin check column dan update sqlite nya

Change log : v1.5.3
- Delete beberapa item ketika player mati
- Menambahkan file message.yml
- Pisah setting biasa dan setting message
- Get Region saat player mati
- Fix debug reload
- Fix beberapa string yang salah, (layau)
