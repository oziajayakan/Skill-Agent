# Quality gate

Periksa hasil agent sebelum diteruskan. Tandai tiap butir lulus atau gagal.

## Semua hasil
- [ ] Sesuai tujuan dan format yang diminta di brief
- [ ] Tidak ada bagian yang hilang atau berisi placeholder
- [ ] Tidak ada klaim fakta tanpa dasar; angka dan nama dicek jika penting
- [ ] Bahasa dan nada sesuai permintaan pengguna

## Konten
- [ ] Hook atau pembuka kuat
- [ ] Gaya konsisten di semua format hasil repurpose
- [ ] Panjang sesuai batas platform
- [ ] Ada ajakan bertindak jika relevan
- [ ] Tidak menyalin teks sumber secara mentah

## Kode
- [ ] Sesuai spesifikasi dari planner
- [ ] Bisa dijalankan; langkah menjalankannya jelas
- [ ] Tidak ada rahasia (API key, password) tertanam di kode
- [ ] Error umum ditangani (input kosong, jaringan gagal)
- [ ] Reviewer sudah memeriksa; temuan penting sudah diperbaiki
- [ ] Jika belum diuji, laporan akhir menyatakannya dengan jelas

## Keputusan setelah pemeriksaan
- Semua lulus → teruskan ke langkah berikutnya atau ke pengguna
- Ada yang gagal → kembalikan ke agent dengan catatan spesifik (maksimal 2 putaran)
- Masih gagal setelah 2 putaran → laporkan ke pengguna apa adanya, beserta opsi
