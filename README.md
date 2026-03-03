# 🌍 GlobalThreatMap — Ghid de Instalare

>  **Notă:** Acesta nu este proiectul meu. Proiectul original poate fi găsit la:
> 👉 [https://github.com/unicodeveloper/globalthreatmap](https://github.com/unicodeveloper/globalthreatmap)

---

## 📋 Cerințe preliminare

- **Node.js 18+**
- **Cont Mapbox și token API**
- **Cheie API Valyu**

---

## 🚀 Instalare

### 1. Clonează repository-ul

```bash
git clone https://github.com/unicodeveloper/globalthreatmap
cd globalthreatmap
```

### 2. Instalează dependențele

```bash
npm install
```

### 3. Configurează variabilele de mediu

Creează un fișier `.env.local` în directorul rădăcină al proiectului:

```env
NEXT_PUBLIC_MAPBOX_TOKEN=adaugă_aici_Mapbox_Api_key
VALYU_API_KEY=adaugă_aici_Valyu_Api_key
NEXT_PUBLIC_APP_MODE=self-hosted

# Opțional: Activează extragerea locațiilor prin AI pentru o precizie mai bună
OPENAI_API_KEY=adaugă_aici_OpenAI_Api_key
```


### 4. Pornește serverul de dezvoltare

```bash
npm run dev
```

### 5. Deschide în browser

Navighează la [http://localhost:3000](http://localhost:3000)

---

## 🔑 Obține cheile API

- **Mapbox** — [account.mapbox.com](https://account.mapbox.com/)
- **Valyu** — [valyu.ai](https://valyu.ai)
- **OpenAI** *(opțional)* — [platform.openai.com](https://platform.openai.com/)
