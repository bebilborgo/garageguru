# 🔧 GarageGuru

Webapp mobile-first per consultare in modo intelligente 
il PDF del manuale di officina della moto.

## ✨ Funzionalità
- Ricerca intelligente con sinonimi e fuzzy matching
- Assistente AI con Groq (gratis)
- Sommario automatico del manuale
- Salvataggio PDF nel browser (IndexedDB)
- Funziona offline dopo il primo caricamento

## 🚀 Come usarla
1. Apri [garageguru](https://tuonomeutente.github.io/garageguru/)
2. Registrati gratis su [console.groq.com](https://console.groq.com)
3. Crea una API key e incollala in Impostazioni
4. Carica il PDF del manuale
5. Inizia a cercare!

## 📱 Mobile
Su iPhone: aggiungi alla schermata Home per prestazioni ottimali.

## 🔒 Privacy
- La API key resta solo nel tuo browser (localStorage)
- Il PDF resta solo sul tuo dispositivo (IndexedDB)
- Nessun dato viene inviato a server terzi (eccetto le domande a Groq)

## 🛠️ Tecnologie
- HTML/CSS/JS vanilla (single-file)
- PDF.js per il rendering
- Groq API (Llama 3.3 70B) per l'assistente AI
- IndexedDB per la cache
