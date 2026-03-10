# 🧟 ZOMBIE SURVIVAL
> Terinspirasi dari Garry's Mod Zombie Survival

---

## 📁 Struktur Project

```
zombie-survival/
├── index.html          ← File utama, buka ini di browser
├── css/
│   └── style.css       ← Semua styling & animasi UI
├── js/
│   ├── config.js       ← Konstanta senjata, zombie, shared state
│   ├── map.js          ← Generate map & collision
│   ├── player.js       ← Gerakan & damage player
│   ├── weapons.js      ← Tembak, reload, bullet logic
│   ├── zombies.js      ← AI zombie & wave system
│   ├── pickups.js      ← Drop item & koleksi
│   ├── particles.js    ← Partikel & efek darah
│   ├── hud.js          ← Update HUD, kill feed, pesan
│   ├── draw.js         ← Semua fungsi render canvas
│   ├── input.js        ← Keyboard & mouse input
│   └── game.js         ← Game loop, start, game over
└── README.md
```

---

## 🚀 Cara Menjalankan di VS Code

### Cara 1 — Live Server (Rekomendasi)
1. Install extension **Live Server** di VS Code  
   (Cari "Live Server" oleh Ritwick Dey di Extensions)
2. Klik kanan `index.html` → **Open with Live Server**
3. Browser akan otomatis terbuka

### Cara 2 — Langsung buka file
1. Double-click `index.html`
2. Buka di browser (Chrome/Firefox/Edge)

> ⚠️ **Catatan:** Jangan buka langsung via `file://` protocol jika ada masalah font.  
> Gunakan Live Server untuk hasil terbaik.

---

## 🎮 Kontrol

| Tombol | Aksi |
|--------|------|
| `WASD` / `Arrow Keys` | Gerak |
| `Mouse` | Arahkan bidikan |
| `Left Click` | Tembak |
| `R` | Reload |
| `1` | Pistol |
| `2` | Shotgun |
| `3` | Rifle (Auto) |
| `Shift` | Sprint |

---

## 🔫 Senjata

| Senjata | DMG | Ammo | Fire Rate | Mode |
|---------|-----|------|-----------|------|
| Pistol  | 25  | 12   | Normal    | Semi-Auto |
| Shotgun | 18×7 pellets | 6 | Lambat | Semi-Auto |
| Rifle   | 35  | 30   | Cepat     | Full-Auto |

---

## 🧟 Tipe Zombie

| Nama    | HP  | Speed | Bahaya |
|---------|-----|-------|--------|
| Walker  | 80  | Lambat | Normal |
| Runner  | 50  | Cepat  | Sulit dihindari |
| Tank    | 300 | Sangat lambat | High damage |
| Spitter | 60  | Sedang | Bisa menyerang dari jauh |

---

## ✨ Fitur

- ✅ 3 Senjata dengan karakteristik berbeda
- ✅ 4 Tipe zombie dengan AI berbeda
- ✅ Wave system — makin tinggi makin sulit
- ✅ Fog of war
- ✅ Blood & particle effects
- ✅ Pickup drops (Health, Armor, Ammo)
- ✅ HUD lengkap (HP, Armor, Ammo, Kill feed)
- ✅ Cover / obstacle system
- ✅ Spitter zombie ranged attack

---

## 🛠️ Pengembangan Lanjutan (Ideas)

- [ ] Tambah suara tembakan & zombie
- [ ] Multiplayer (WebSocket)
- [ ] Lebih banyak senjata (SMG, Sniper, dll)
- [ ] Boss zombie tiap 5 wave
- [ ] High score leaderboard (localStorage)
- [ ] Mobile touch controls
