# RianShop Frontend

Storefront dan dashboard admin statis untuk RianShop.

## Menjalankan lokal

```bash
python3 -m http.server 4173
```

Buka `http://localhost:4173` untuk storefront dan
`http://localhost:4173/admin.html` untuk dashboard.

URL backend dapat diubah dari layar login admin. Nilainya disimpan di
`localStorage` dengan key `rianshop_api_url` dan digunakan oleh storefront
serta dashboard pada browser yang sama.

Untuk deployment statis, set `window.RIANSHOP_API_URL` sebelum script utama
bila ingin menentukan URL API tanpa konfigurasi browser.
