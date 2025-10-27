# 🎓 Kalkulator ocen
Prosty kalkulator online dla nauczycieli, który automatycznie przelicza punkty ze sprawdzianu na procenty i oceny według ustalonych progów.  
Działa całkowicie w przeglądarce oraz jako aplikacja **PWA** (można ją zainstalować na telefonie lub komputerze).

🔗 **Aplikacja dostępna tutaj:**  
👉 [https://riko-b.github.io/kalkulator-ocen/](https://riko-b.github.io/kalkulator-ocen/)

---

## ✨ Funkcje

- Ustalanie **maksymalnej liczby punktów** i **progów** (procentowych lub punktowych)  
- Obsługa **skali ocen 1–6** lub **1–5**  
- Możliwość zmiany **nazw ocen** (np. „dobry”, „zaliczony”)  
- **Auto-przeliczanie** – wynik oblicza się w trakcie wpisywania  
- Obsługa skrótów: **Enter** (przelicz) oraz **Ctrl+Enter** (globalne przeliczenie)  
- **Animowany wskaźnik (spinner)** przy automatycznym przeliczaniu  
- **Tabela wyników** dla wszystkich możliwych punktów  
- Zapis ustawień w **localStorage** (dane pozostają po odświeżeniu)  
- Działa jako **PWA (Progressive Web App)** – dostępna **offline** po pierwszym uruchomieniu  

---

## 📲 Instalacja jako aplikacja (PWA)

### 🔹 Android / Windows

1. Otwórz stronę kalkulatora:  
   👉 [https://riko-b.github.io/kalkulator-ocen/](https://riko-b.github.io/kalkulator-ocen/)
2. W menu przeglądarki (⋮) wybierz **„Zainstaluj aplikację”** lub **„Dodaj do ekranu głównego”**.

### 🔹 iPhone / iPad (Safari)

1. Otwórz stronę w Safari.  
2. Kliknij **Udostępnij → Do ekranu początkowego**.

---

## ⚙️ Jak edytować progi i ustawienia

1. W sekcji **„Progi dla ocen”** wpisz wartości progów (w % lub punktach).  
2. Zmień w razie potrzeby **nazwy ocen** (np. „zaliczony”, „niezaliczony”).  
3. Kliknij **„Zapisz ustawienia”** – wszystko zapisze się w Twojej przeglądarce.  
4. Aby przywrócić ustawienia domyślne, kliknij **„Przywróć domyślne”**.

---

## 💾 Zapis ustawień

Wszystkie dane (progi, skala, nazwy ocen, auto-przeliczanie itp.) przechowywane są lokalnie w przeglądarce (`localStorage`).  
Nie są wysyłane do Internetu.

---

## 🌐 Działanie offline (PWA)

Aplikacja posiada:

- `manifest.webmanifest` – deklarację PWA  
- `sw.js` – service worker do cache’owania offline  

Dzięki temu działa **nawet bez dostępu do Internetu** po pierwszym uruchomieniu.  
Użytkownik może otworzyć ją jak zwykłą aplikację mobilną.

---

## 🧩 Jak zaktualizować aplikację

1. Zmień plik `index.html` lub inne pliki w repozytorium.  
2. Zatwierdź zmiany (Commit changes).  
3. GitHub Pages automatycznie opublikuje nową wersję (zazwyczaj w ciągu 1–2 minut).  
4. Po odświeżeniu strony przeglądarka sama pobierze najnowszą wersję PWA.

---

## 📧 Autor i kontakt

Projekt stworzony dla:  
**mgr Agnieszka Makuła-Broda**

Repozytorium GitHub: [riko-b/kalkulator-ocen](https://github.com/riko-b/kalkulator-ocen)

---

_© 2025, projekt dydaktyczny. Można używać i modyfikować w celach edukacyjnych._
