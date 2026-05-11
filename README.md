# Automatic Doors — Website

## Qovluq strukturu

```
automatic-doors/
├── index.html          ← Əsas sayt faylı
├── logo.png            ← Şirkət logosu
├── images/             ← FOTOLAR bura atılır (jpg, png, webp, gif)
│   └── .gitkeep
└── videos/             ← VİDEOLAR bura atılır (mp4, webm, mov)
    └── .gitkeep
```

## GitHub Pages quraşdırması

### 1. GitHub konfiqurasiyası
`index.html` faylını açın, yuxarıda bu hissəni tapın:

```javascript
const GITHUB = {
  owner: 'YOUR_GITHUB_USERNAME', // ← öz GitHub istifadəçi adını yaz
  repo:  'YOUR_REPO_NAME',       // ← öz repo adını yaz
  branch: 'main'
};
```

Öz məlumatlarınızla əvəz edin. Məsələn:
```javascript
const GITHUB = {
  owner: 'johnsmith',
  repo:  'automatic-doors',
  branch: 'main'
};
```

### 2. GitHub Pages aktivləşdirmə
1. GitHub-da repo açın → Settings
2. Sol menüdən "Pages" seçin
3. Source: "Deploy from a branch"
4. Branch: `main` / `root`
5. Save edin

### 3. Şəkil və video əlavə etmə (avtomatik görünür!)
- `images/` qovluğuna şəkil atın → saytda foto bölməsindəyaranar
- `videos/` qovluğuna video atın → saytda video bölməsindəyaranar
- Dəstəklənən formatlar: **jpg, jpeg, png, webp, gif** / **mp4, webm, mov**
- Commit edib push etdikdən sonra sayt avtomatik yenilənir

### 4. Sosial media linklərini dəyişin
`index.html`-də `yourusername` yazan yerləri real hesab adlarınızla əvəz edin.

### 5. Google Maps əlavə etmə
Contact bölməsindəki map-frame-i tapın və Google Maps embed linkini əlavə edin.

### 6. VP Biznes Chat
`id="vpChat"` olan elementin `href="#"` hissəsini real VP link ilə əvəz edin.

---
© 2025 Automatic Doors | Bakı, Azərbaycan
