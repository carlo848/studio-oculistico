# 🚀 Guida al Deployment di www.oculistarapisarda.it

## Opzione 1: Netlify (CONSIGLIATO - Gratuito e Facile)

### Passaggi:

1. **Vai su https://www.netlify.com/**
2. **Clicca "Sign up" e connetti il tuo account GitHub**
3. **Seleziona il repository `studio-oculistico`**
4. **Netlify farà il deploy automaticamente**
   - Riceverai un'URL temporanea come: `https://xxxxx.netlify.app`
   - Ci vorranno 2-3 minuti

5. **Collega il dominio personalizzato:**
   - Nel pannello Netlify → Domain settings
   - Clicca "Add custom domain"
   - Digita: `www.oculistarapisarda.it`
   - Segui le istruzioni per aggiornare i DNS

### Costi:
- **Hosting:** GRATUITO
- **Dominio:** ~10-20€/anno (da registrare separatamente)
- **SSL:** INCLUSO GRATUITAMENTE

---

## Opzione 2: GitHub Pages (Gratuito ma con limitazioni)

### Passaggi:

1. **Vai su GitHub → Repository → Settings → Pages**
2. **Seleziona "main" come branch**
3. **Attendi il deployment (2-3 minuti)**
4. **Il sito sarà su:** `https://carlo848.github.io/studio-oculistico/`

### Per usare il dominio personalizzato:

1. **Registra il dominio** www.oculistarapisarda.it
2. **In Settings → Pages → Custom domain**
3. **Aggiungi:** www.oculistarapisarda.it
4. **Aggiorna i DNS del registrar del dominio:**
   - Punta gli A records a GitHub Pages
   - Punta il CNAME a `carlo848.github.io`

### Costi:
- **Hosting:** GRATUITO
- **Dominio:** ~10-20€/anno
- **SSL:** INCLUSO GRATUITAMENTE

---

## Opzione 3: Hosting Tradizionale (Aruba, Siteground, ecc.)

### Passaggi:

1. **Registra il dominio** www.oculistarapisarda.it
2. **Acquista un piano hosting**
3. **Accedi al pannello hosting**
4. **Carica i file via FTP:**
   - `index.html`
   - `style.css`
   - `script.js`
5. **Configura i DNS**

### Costi:
- **Dominio:** ~10-20€/anno
- **Hosting:** ~50-100€/anno
- **SSL:** Solitamente incluso

---

## 📋 Registrazione Dominio

Il dominio **NON è ancora registrato**. Devi registrarlo presso:

- **Aruba** (https://www.aruba.it/)
- **Snamhost** (https://www.snamhost.it/)
- **GoDaddy** (https://it.godaddy.com/)
- **NameSecure** (https://www.namesecure.com/)
- O qualsiasi altro registrar

**Costo:** 10-20€ all'anno

---

## ✅ Checklist di Deployment

### Prima del Deploy:
- [x] Sito completato con tutti i contenuti
- [x] Design responsive testato
- [x] Modulo contatti funzionante
- [x] Social media linkati
- [ ] Foto dello studio aggiunte (opzionale)

### Durante il Deploy:
- [ ] Registra il dominio www.oculistarapisarda.it
- [ ] Scegli un provider (Netlify consigliato)
- [ ] Connetti il repository
- [ ] Collega il dominio personalizzato
- [ ] Testa il sito da www.oculistarapisarda.it

### Dopo il Deploy:
- [ ] Verifica che il sito sia raggiungibile
- [ ] Testa su mobile, tablet, desktop
- [ ] Controlla tutti i link
- [ ] Test del modulo contatti
- [ ] Verifica HTTPS sia attivo

---

## 🔗 Link Utili

- **Netlify:** https://www.netlify.com/
- **GitHub Pages:** https://pages.github.com/
- **Registrar Dominio:** Aruba, Snamhost, GoDaddy
- **Google My Business:** https://www.google.com/business/

---

## 💡 Consigli Finali

1. **Usa Netlify** - È il più semplice e gratuito
2. **Registra il dominio subito** - Costa poco e ci vogliono 24-48h per propagarsi
3. **Testa tutto prima di andare live** - Usa l'URL gratuito di Netlify per testare
4. **Aggiungi il sito a Google My Business** - Aiuta i pazienti a trovarti
5. **Monitora il sito** - Netlify ha analytics gratuito

---

**Hai bisogno di aiuto? Contatta lo sviluppatore!**
