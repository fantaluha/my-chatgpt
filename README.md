# My ChatGPT

Client web minimale per chattare con i modelli OpenAI direttamente dal browser.

## Funzionalità

- Chat con tutti i modelli OpenAI (GPT-4.1, GPT-4o, GPT-5 Nano, o3, ecc.)
- System prompt personalizzabile
- API key, modello e system prompt salvati nel browser (localStorage)
- Conteggio token per ogni risposta
- Nessuna dipendenza esterna — un singolo file HTML

## Come usarlo

1. Apri il file `index.html` nel browser
2. Clicca **Impostazioni** e inserisci la tua API key di OpenAI
3. Scegli il modello e scrivi un messaggio

La API key resta salvata nel tuo browser e non viene mai inviata a terzi (solo alle API di OpenAI).

## Sviluppo locale

```bash
git clone https://github.com/fantaluha/my-chatgpt.git
cd my-chatgpt
open index.html
```