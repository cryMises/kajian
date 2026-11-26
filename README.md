# Kaji AI

Rekomendasi model AI berdasarkan spek perangkatmu. Bahasa Indonesia, tema scrapbook Katchup.

- Deteksi GPU + VRAM otomatis (WebGL + tabel lookup, bisa dikoreksi manual)
- Rekomendasi langsung dari API Hugging Face, diurutkan pakai skor trending
- Teks ke Teks, Teks ke Gambar, Teks ke Video
- Toggle Uncensored (eksklusif: nyala = cuma model uncensored)
- Cuma model yang muat di perangkatmu yang ditampilkan; kalau versi full nggak muat tapi quant-nya muat, otomatis dicariin versi GGUF-nya

Cara pakai: buka `index.html` di browser, atau serve folder ini sebagai static site.
