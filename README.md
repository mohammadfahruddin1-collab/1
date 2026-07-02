# 💻 Hacker Cyberpunk Database Interface

A simple, lightweight terminal-style web interface simulating a hacker database lookups. Built using raw HTML, CSS, and vanilla JavaScript.

## 🚀 Features
- **Cyberpunk / Hacker UI Theme**: Green neon glow with strict dark mode and monospace fonts.
- **Fake Breach Sequence**: Simulates bypass scripts and loading state before showing data.
- **Dynamic Photo Scanning**: Photo frames with a moving matrix-like scan bar filter.
- **Local JSON Data**: Easy to customize and append target data.

## 🛠️ How to Customize Data
Open `INDEX.html` and scroll down to the `<script>` section. Modify or add objects inside the `database` array:
```javascript
{
    nama: "panggilan",
    namaLengkap: "Nama Lengkap Target",
    status: "STATUS",
    lokasi: "Lokasi Rumah",
    ip: "127.0.0.1",
    keahlian: "Skill Target",
    catatan: "Catatan Rahasia",
    foto: "assets/foto-kamu.jpg" // Atur foto di folder assets
}
