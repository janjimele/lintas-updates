# Kanal pembaruan Lintas

Repo ini hanya berisi `latest.json` yang dibaca aplikasi Lintas untuk memeriksa versi terbaru.
Repo utama (`janjimele/lintas-tauri`) tetap privat, dan installer tidak pernah diunggah ke sini.

Format:

```json
{ "version": "0.1.6", "url": null }
```

- `version`: versi terakhir yang dirilis (semver).
- `url`: opsional dan harus `https://`. Bila diisi, toast pembaruan menampilkan tombol untuk
  membuka halaman itu; bila `null`, tester diminta menghubungi pengelola untuk installer.

Berkas ini diterbitkan dari repo utama dengan `npm run update:channel`.
