Loading Card by Fathir

Deskripsi

Ini adalah halaman web sederhana dengan efek loading card yang memiliki animasi progres, teks, dan efek jatuhnya emoji secara acak. Tampilan halaman dibuat dengan desain estetik menggunakan gradien warna, efek blur, dan animasi CSS.

Fitur Utama

Loading Text: Menampilkan teks "Loading Card..." dengan efek gradien warna.

Subtext: Pesan permintaan maaf yang tampak lebih menonjol dengan warna gelap.

Progress Bar: Animasi progres bar berjalan selama 3 detik.

Gambar Hati: Ikon hati dengan animasi heartbeat.

Tombol Next: Mengarahkan pengguna ke halaman "Card.html" setelah loading selesai.

Emoji Falling Effect: Efek jatuhnya emoji secara acak di layar.

Teknologi yang Digunakan

HTML: Struktur halaman web.

CSS: Styling dengan efek gradien, animasi, dan shadow.

JavaScript: Animasi emoji yang jatuh secara acak di layar.

Cara Menggunakan

Simpan file HTML ini dengan nama index.html.

Buka file di browser untuk melihat efek loading dan animasi.

Klik tombol "NEXT" untuk berpindah ke halaman Card.html (pastikan file tersebut ada).

Cuplikan Kode Penting

Animasi Progress Bar:

@keyframes load {
    0% { width: 0%; }
    100% { width: 100%; }
}

Progress bar akan terisi dalam 3 detik.

Animasi Emoji Jatuh:

function createEmoji() {
    const emojiArray = ['❤️', '💖', '🎉', '💕', '🥳', '🎉', '💗', '🥳'];
    const emoji = document.createElement('div');
    emoji.classList.add('emoji');
    emoji.innerText = emojiArray[Math.floor(Math.random() * emojiArray.length)];
    emoji.style.left = Math.random() * window.innerWidth + 'px';
    emoji.style.animationDuration = (Math.random() * 3 + 2) + 's';
    document.body.appendChild(emoji);
    setTimeout(() => emoji.remove(), 5000);
}
setInterval(createEmoji, 500);

Fungsi ini membuat emoji jatuh secara acak dengan kecepatan yang berbeda-beda.

Catatan

Pastikan file Card.html tersedia agar tombol "NEXT" dapat berfungsi dengan baik.

Bisa dikembangkan lebih lanjut dengan efek suara atau transisi halaman.

Lisensi

Proyek ini dibuat untuk keperluan pembelajaran dan dapat digunakan bebas sesuai kebutuhan.

