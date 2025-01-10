# LLM Historie

<div class="width_img_wrapper_100">
  ![Historie](images/673b146a192243b5db18eb3e_673b1314936505e1980f4ca2_LLMs_Fig.png)
</div>

---
<!-- .slide: data-background="images/backgrounds/shutterstock_200991887_B.jpg" data-state="inverted" -->

# Erste Schritte

---

# 1906 - Andrey Markov


- Einführung der Markov-Ketten.
- („Bull Market“-Strategie basierte auf Wahrscheinlichkeitsmodellen.)

<div class="width_img_wrapper_60">
  ![Markov Chains](images/Markov_Chains.png)
</div>

https://de.wikipedia.org/wiki/Andrei_Andrejewitsch_Markow_(Mathematiker,_1856)


---

- Erforschte zufällige Prozesse und Gedichtstrukturen.

<div class="width_img_wrapper_20">
  ![Markov Chains](images/first_language_model.png)
</div>

---
<!-- .slide: data-background="images/backgrounds/shutterstock_200991887_B.jpg" data-state="inverted" -->

# Die Geburt der Neuronenmodelle

---

# 1943 - McCulloch & Pitts

- Entwickelten das erste Modell eines künstlichen Neurons.
- Inspiriert von der Funktionsweise des Gehirns.

https://de.wikipedia.org/wiki/McCulloch-Pitts-Zelle

---

# 1948 - Claude Shannon

- Vater der Informationstheorie.
- Wollte mit Algorithmen im Kasino gewinnen.

<div class="width_img_wrapper_30">
  ![Shannon](images/shannon.png)
</div>

https://de.wikipedia.org/wiki/Claude_Shannon

---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" -->

# Fortschritte im Machine Learning

---

# 1957 - Frank Rosenblatt

- Entwickelte das Perzeptron, ein frühes neuronales Netzwerk. [https://de.wikipedia.org/wiki/Perzeptron]
- Ziel: Maschinen sollen lernen wie das menschliche Gehirn.

Mathe!: Lineare Algebra (Vektoren, Matrizen, Skalarprodukt, ...)

[https://media.ccc.de/v/froscon2024-3054-wie_funktioniert_chatgpt_ganz_genau#t=360]

---

# 1986 - Geoffrey Hinton

- „Godfather of AI“ – seine Ideen revolutionierten die KI-Forschung.
- Backpropagation-Algorithmus (1986): Lernmechanismus für neuronale Netze.
- Autoencoder (1993): Abstraktion durch engstellen in neuronale Netzen.

<div class="width_img_wrapper_20">
  ![Hinton](images/hinton_neural.png)
</div>

https://de.wikipedia.org/wiki/Geoffrey_Hinton

---

# 1997 - Schmidhuber & Hochreiter

- Einführung von Long Short-Term Memory (LSTM).
  - Schleife in neuronalen Netzen
- Fokus: Zeitabhängige Daten wie Sprache und Musik.

https://de.wikipedia.org/wiki/Long_short-term_memory

---
<!-- .slide: data-background="images/backgrounds/shutterstock_195671744.jpg" -->

# Das Zeitalter von Deep Learning

---

# 2002 - Bengio, Hinton & LeCun

- Pioniere des modernen Machine Learning.

z.B.: Embeddings
3 Dimensionen (3 Zahlen) → 11.000 ChatGPT 3 (von 2020)
<div class="width_img_wrapper_30">
  ![Embeddings](images/embeddings.png)
</div>

---

# 2014 - Attention

- Übersetzung von einer Sprache in eine andere
- Verschränkung von Sprache

<div class="width_img_wrapper_60">
  ![Attention](images/attention.png)
</div>

---

# 2017 - Transformer-Modell (Google)

"Attention is all you need"

- Einführung des Transformer-Frameworks.
- Grundlage für heutige Sprachmodelle wie GPT.

---
<!-- .slide: data-background="images/reactions/tumblr_mej27iJ3rC1qdpvjdo1_500.gif" data-state="inverted faded" -->

# Moderne Sprachmodelle

---

# 2018 - GPT-1 (OpenAI)

- Transformer-Modell für Texte nicht Übersetzungen
- Ähnlich wie bei Andrey Markov von 1906

---

# 2020 - GPT-3 (OpenAI)

- Leistungsfähig genug, um menschenähnliche Texte zu generieren.

---

# 2023 - Open Source LLMs

- Meta veröffentlicht Llama 2.
- Hugging Face treibt Open-Source-KI voran.

llama.cpp: first commit
https://github.com/ggerganov/llama.cpp/blob/26c084662903ddaca19bef982831bfb0856e8257/main.cpp#L387

ollama: local LLM
https://github.com/ollama/ollama

---

# 2024 - GPT-4o und Gemini

- Multimodale KI-Modelle.
- Text, Bild, Audio, Video

---

# Zusammenfassung

- Vom Perzeptron zu GPT-4: Eine Reise voller Innovationen.
- Jedes Modell brachte neue Fähigkeiten, von Sprachverstehen bis Kreativität.

"The evolutionary tree of modern LLMs"
https://arxiv.org/pdf/2304.13712

---

<!-- .slide: data-background="images/reactions/tumblr_n7vqltNUdZ1qequb0o6_250.gif" data-state="inverted faded" -->

# Herausforderungen von LLMs

---

# Ressourcenverbrauch

### Energie und Hardware

- GPT-3 Training ~ 1287 Megawattstunden → ~ Atomkraftwerk in einer Stunde
- Erhebliche Kosten für Hardware (GPU, Kühlung, Rechenzentrum, ...)
- ChatGPT benötigt ~ 10x mehr Rechenleistung als 1x Google Suche

---

# Jobs und Automatisierung

### Arbeitsplatzunsicherheit

- LLMs können repetitive Aufgaben übernehmen (z. B. Datenzusammenfassungen, Vertragsprüfung).
- Automatisierung in Kundenservice, Recht und sogar kreativen Berufen.
- Junior Entwickler kann man schon heute durch LLMs ersetzten :/

---

# Sicherheit und Ethik

### Deepfakes und Desinformation

- Erstellung von realistisch wirkenden Fake-Inhalten
- Manipulation von Medien und Wahlkampfstrategien


### Bias und Fairness

- Trainingsdaten enthalten Vorurteile, die sich auf Antworten auswirken.
- OpenAI: Exklusive kooperationen mit Welt.de / Bild.de
- DeepSeek: aus China + mit Zensur
