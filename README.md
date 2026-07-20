# EasyBook Tavern

Distribusi publik installer **EasyBook** — ERP desktop offline untuk UMKM (Windows & macOS).

Repo ini **bukan** source code. Source ada di repo private. Tavern hanya menampung **GitHub Releases** berisi binary yang siap diunduh dari landing page.

## Unduh

**Rilis terbaru:** https://github.com/irwanphan/easybook-tavern/releases/latest

| Platform | File tipikal |
| --- | --- |
| Windows | `.msi` / `.exe` (NSIS) |
| macOS | `.dmg` (Apple Silicon) |

Pilih asset sesuai sistem kamu di halaman release. Jangan unduh file `.sig` kecuali kamu tahu itu untuk verifikasi updater.

## Apa yang ada di sini

- Installer EasyBook yang dipublish untuk pengguna
- Signature updater (dipakai aplikasi yang sudah terpasang untuk cek pembaruan)
- Tag versi yang selaras dengan rilis produk (mis. `v26.7.20.0`)

## Apa yang tidak ada di sini

- Source code / isu pengembangan
- Lisensi / aktivasi (itu lewat ActiveBook)
- Landing page pemasaran (repo `easybook-landing`)

## Cara rilis dibuat

Release di-upload otomatis oleh workflow **Release** di repo aplikasi EasyBook (private), memakai token yang hanya punya akses tulis ke tavern.

Alur singkat:

1. Maintainer menjalankan Actions → Release di repo app
2. CI build Windows + macOS
3. Artifact dipublish ke **release** di repo ini
4. Setelah release **Published** (bukan Draft), link `/releases/latest` bisa dipakai publik — termasuk dari landing

## Catatan untuk pengguna

- Uji coba: sampai **100 transaksi** jual+beli sebelum wajib aktivasi lisensi
- Data pembukuan tersimpan lokal di PC kamu
- Butuh bantuan atau lisensi: hubungi lewat channel resmi EasyBook (bukan Issues di repo ini, kecuali maintainer membuka Issues untuk unduhan)

## Tautan

- Unduhan: https://github.com/irwanphan/easybook-tavern/releases/latest
- Produk: EasyBook ERP (desktop · offline-first)
