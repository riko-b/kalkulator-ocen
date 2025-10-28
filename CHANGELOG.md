# 🧾 Changelog – Kalkulator ocen (mgr Agnieszka Makuła-Broda)

Wszystkie istotne zmiany i aktualizacje aplikacji będą opisane w tym pliku.

---

## [v1.0.1] – 2025-10-28

### ✅ Poprawki
- **Reset progów do domyślnych przy zmianie skali (1–6 ⇄ 1–5)** z zachowaniem **własnych nazw ocen**.
- Bezpieczny odczyt pól formularza po zmianach skali/trybu (brak błędów, jeśli pole jeszcze nie istnieje).
- Stabilniejsze przerysowywanie tabeli progów i zapisywanie stanu (`localStorage`).

### ℹ️ Uwagi
- Podmiana tylko `index.html` w repo wystarczy (PWA/manifest/ikony bez zmian).
- Po wdrożeniu zalecane twarde odświeżenie: **Ctrl+F5** / **Cmd+Shift+R**.

---

## [v1.0.0] – 2025-10-28

### ✨ Nowości
- Pierwsza publiczna wersja aplikacji
- Obsługa **skali 1–6** oraz **1–5**
- Wybór progów: **procentowe** lub **punktowe**
- **Nazwy ocen** edytowalne (np. „dobry”, „zaliczony”)
- **Auto-przeliczanie** na żywo po wpisaniu punktów
- Skróty: **Enter** (przelicz), **Ctrl+Enter** (globalne przeliczenie)
- **Animowany spinner** (widoczny tylko przy auto-przeliczaniu)
- **Tabela wyników** od 0 do maksymalnej liczby punktów
- Zapis ustawień w **localStorage**
- Tryb **offline (PWA)** – możliwość instalacji na telefonie lub komputerze
- **Pełnoekranowa** wersja po instalacji jako PWA
- Dokumentacja w dwóch językach: 🇵🇱 `README.md` i 🇬🇧 `README_EN.md`

### 🧰 Technologia
- HTML5, CSS3 (responsywny układ)
- JavaScript (czysty, bez bibliotek)
- Service Worker + Manifest (PWA)
- Kompatybilne z GitHub Pages i Netlify
