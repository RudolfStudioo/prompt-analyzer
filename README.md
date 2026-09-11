# prompt-analyzer

Prompt Analyzer

Aplikasi web statis (HTML/Tailwind/JS murni, tanpa build step) yang mengubah ide proyek jadi workflow bertahap lengkap dengan prompt eksekusi siap pakai untuk AI coding assistant lain (ChatGPT, Claude, Gemini).

Cara pakai
Buka index.html (langsung di browser, atau lewat deploy).
Klik ikon gear (Pengaturan) di sidebar, masukkan Gemini API key kamu (gratis di https://aistudio.google.com/apikey). Daftar model akan otomatis dimuat dari akun Google-mu — pilih salah satu. Key & model hanya tersimpan di localStorage browser, tidak pernah dikirim ke server manapun selain langsung ke Google.
Ceritakan ide proyek di kolom chat.
Jawab pertanyaan klarifikasi yang dibuat AI.
Periksa ringkasan, tambahkan catatan kalau perlu → Buat Workflow.
Dapatkan langkah kerja lengkap dengan prompt siap salin per tahap, atau unduh semuanya sebagai .md.
