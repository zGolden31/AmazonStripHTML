# 🧹 HTML Cleaner per Amazon

**HTML Cleaner per Amazon** è uno strumento gratuito che pulisce automaticamente il codice HTML, rimuovendo tutti i tag e gli attributi non consentiti da **Amazon** (ad esempio per descrizioni prodotto o contenuti A+).

👉 [Provalo online su GitHub Pages](https://tuo-username.github.io/html-cleaner-amazon/](https://zgolden31.github.io/AmazonStripHTML/))  

---

## 🚀 Funzionalità principali

- 🔸 Rimuove automaticamente i tag HTML non permessi da Amazon.  
- 🔸 Mantiene solo i tag **consentiti**, come:  
  `<p>`, `<br>`, `<b>`, `<i>`, `<strong>`, `<em>`, `<ul>`, `<ol>`, `<li>`.
- 🔸 Elimina tutti gli **attributi** (es. `style`, `class`, `id`, ecc.).
- 🔸 Include due aree di testo affiancate:
  - ✏️ **Input HTML**: dove incollare il codice da pulire.  
  - ✅ **Output Pulito**: dove visualizzare il risultato.  
- 🔸 Pulsanti per **pulire** e **copiare** il codice.  
- 🎨 Interfaccia semplice e responsiva, pronta per l’uso immediato.

---

## 💡 Come funziona

Il codice usa il parser HTML del browser (`DOMParser`) per leggere il contenuto e lo attraversa nodo per nodo:  
- Se un elemento è **testo**, lo mantiene.  
- Se un elemento HTML **non è nella lista dei tag consentiti**, lo rimuove ma mantiene il contenuto interno.  
- Tutti gli attributi HTML vengono eliminati.  

Il risultato è un **HTML sicuro e compatibile con Amazon**, pronto da incollare nell’editor del prodotto.

---

## 🧩 Installazione e utilizzo locale

Puoi usare il progetto anche offline, senza bisogno di server.

1. Scarica o clona il repository:
   ```bash
   git clone https://github.com/tuo-username/html-cleaner-amazon.git
