# OHLI Social v3.6.21 — Buildfix 1

Perubahan hanya pada workflow CI. Aplikasi tetap `versionName 3.6.21` dan
`versionCode 50`. Perbaikan menghindari HTTP 504 di `gradle/actions/setup-gradle`
dengan mengunduh Gradle 8.9 dari host distribusi resmi menggunakan retry dan
validasi SHA-256. Tidak ada perubahan kode runtime OHLI.
