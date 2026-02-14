# Cara Menggunakan GitHub Desktop

Ikuti langkah-langkah ini untuk upload (sync) projek kad jemputan ke GitHub supaya boleh disambungkan ke Cloudflare.

## 1. Persediaan
Pastikan folder projek dah ada di Desktop:
`Desktop > Hayraz > boboiboy-invite`

## 2. GitHub Desktop
1.  Buka aplikasi **GitHub Desktop**.
2.  Pergi ke menu **File** (sebelah kiri atas) -> Pilih **Add local repository...**
3.  Tekan **Choose...** dan cari folder tadi:
    *   Lokasi: `C:\Users\Administrator\Desktop\Hayraz\boboiboy-invite`
4.  Tekan **Add Repository**.
5.  GitHub Desktop akan tanya "This directory does not appear to be a Git repository".
    *   Tekan link biru **create a repository** di situ.
    *   Isi nama (contoh: `kad-jemputan-hayraz`).
    *   Tekan **Create Repository**.

## 3. Publish ke GitHub
1.  Sekarang anda akan nampak butang biru besar **Publish repository** di bar atas. Tekan butang itu.
2.  Pastikan nama elok (contoh: `kad-jemputan-hayraz`).
3.  **PENTING**: Uncheck (buang tanda) kotak "Keep this code private" kalau nak mudahkan Cloudflare baca. Kalau nak Private pun boleh, tapi kena login akaun GitHub kat Cloudflare nanti.
4.  Tekan **Publish Repository**.

## 4. Sambung ke Cloudflare
1.  Buka laman web [Cloudflare Dashboard](https://dash.cloudflare.com).
2.  Pergi ke **Workers & Pages** -> **Create Application** -> **Pages** -> **Connect to Git**.
3.  Pilih repository `kad-jemputan-hayraz` yang baru di-upload tadi.
4.  Tekan **Begin setup** -> **Save and Deploy**.

Siap! Cloudflare akan bagi satu link (contoh: `kad-jemputan-hayraz.pages.dev`) yang boleh anda share kat WhatsApp.

## Soalan Lazim (FAQ)
### Boleh tak guna GitHub Desktop untuk lebih dari satu website?
**BOLEH!** GitHub Desktop memang direka untuk urus banyak projek serentak.
*   Setiap website adalah satu **Repository** yang berasingan.
*   Bila anda `Add local repository` untuk projek baru (macam Boboiboy ni), ia takkan kacau projek/website lama anda.
*   Anda boleh tukar-tukar antara projek dengan menekan nama repository di bucu kiri atas aplikasi (sebelah "Current Repository").

