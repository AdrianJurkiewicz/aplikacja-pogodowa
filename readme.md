# Aplikacja Pogodowa 🌌

Aplikacja internetowa wyświetlająca **aktualną pogodę**, wykres temperatury na najbliższe 24 godziny oraz 3‑dniową prognozę dla wybranego miasta.

---

## 📁 Zawartość repozytorium

| Plik                      | Opis                                               |
| ------------------------- | -------------------------------------------------- |
| `aplikacja_pogodowa.html` | Kompletny kod aplikacji (HTML + CSS + JavaScript)  |
| `README.md`               | Dokumentacja projektu oraz instrukcja uruchomienia |

---

## 🔍 Funkcje aplikacji

- 🔎 **Wyszukiwanie miasta** przez OpenStreetMap (Nominatim API)
- 🌡️ **Aktualna temperatura** wraz z ikoną emoji opisującą pogodę
- 📈 **Wykres temperatury** na kolejne 24 h (Chart.js)
- 📅 **Prognoza dzienna** na 3 nadchodzące dni
- ☁️ Dane pobierane z **Open‑Meteo API** (bez klucza – działa od razu)

---

## 🚀 Jak uruchomić aplikację

Nie trzeba instalować żadnych programów. Wystarczy przeglądarka internetowa (np. Chrome, Firefox).

### ✅ Uruchom online (rekomendowane)

Aplikacja działa w pełni online – wystarczy wejść pod ten link:

👉 [Kliknij tutaj, aby uruchomić aplikację](https://adrianjurkiewicz.github.io/aplikacja-pogodowa/aplikacja_pogodowa.html)

To otworzy gotową stronę z aktualną pogodą i prognozą. Nie wymaga pobierania ani instalacji.

---

## 💻 Jak uruchomić lokalnie (opcjonalnie)

### 1. Pobierz plik

- Wejdź do repozytorium: [https://github.com/adrianjurkiewicz/aplikacja-pogodowa](https://github.com/adrianjurkiewicz/aplikacja-pogodowa)
- Kliknij zielony przycisk **„Code” → „Download ZIP”**
- Rozpakuj pobrane archiwum ZIP

### 2. Uruchom plik

#### Opcja A – przez edytor (np. Visual Studio Code z Live Server):

- Zainstaluj rozszerzenie **Live Server**
- Kliknij prawym przyciskiem na `aplikacja_pogodowa.html` → **„Open with Live Server”**

#### Opcja B – przez serwer lokalny (Node.js):

```bash
npm install -g http-server
http-server -p 8080
```

Otwórz w przeglądarce:

```
http://localhost:8080/aplikacja_pogodowa.html
```

---

## 📚 Technologie

- **HTML / CSS / JavaScript** (Vanilla)
- **Chart.js** – wizualizacja danych
- **Open‑Meteo API** – dane pogodowe
- **Nominatim API** – geokodowanie miast

---

## 👤 Autor

|                      |                                                                        |
| -------------------- | ---------------------------------------------------------------------- |
| **Imię i nazwisko:** | Adrian Jurkiewicz                                                      |
| **Kontakt:**         | [adrianjurkiewicz007@gmail.com](mailto\:adrianjurkiewicz007@gmail.com) |

---

*Projekt przygotowany w ramach zajęć ****„Narzędzia procesu tworzenia oprogramowania”**** – semestralne zaliczenie*

