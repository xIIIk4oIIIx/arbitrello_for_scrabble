# 🔠 Arbitrello (Scrabble Referee & Word Optimizer)

<p align="center">
  <img src="https://img.shields.io/badge/Kotlin-Native_Android-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Jetpack_Compose-Modern_UI-4285F4?style=flat-square&logo=android&logoColor=white" alt="Jetpack Compose" />
  <img src="https://img.shields.io/badge/Room_DB-Offline_Cache-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Room DB" />
</p>

Natywna aplikacja mobilna na system Android pełniąca funkcję inteligentnego arbitra do gier słownych (m.in. Scrabble). Aplikacja łączy błyskawiczne, lokalne struktury danych z asynchronicznym pobieraniem informacji z zewnętrznych serwisów, zapewniając płynną rozgrywkę bez opóźnień.

## ✨ Główne funkcje

* **Błyskawiczna Weryfikacja:** Wykorzystanie silnie zoptymalizowanego, wbudowanego słownika dwu- i trzyliterówek, pozwalającego na matematycznie najszybsze potwierdzenie dopuszczalności słowa.
* **Zaawansowany Anagramator & Scraping:** Sprawdzanie dłuższych wyrazów oraz generowanie pełnych anagramów w czasie rzeczywistym poprzez integrację (scrapowanie) z oficjalnym serwisem Polskiej Federacji Scrabble (PFS).
* **Moduł Timera (Eco Mode):** Wbudowany, precyzyjny minutnik szachowy/scrabblowy dla graczy, wyposażony w tryb oszczędzania energii zapobiegający drenażowi baterii podczas długich partii.
* **Lokalna Historia (Room DB):** Automatyczne zapisywanie wyszukiwanych słów na urządzeniu, co ułatwia rozwiązywanie sporów w późniejszych etapach gry.

## 🛠️ Architektura & Tech Stack

Aplikacja została zbudowana w oparciu o czystą architekturę (Clean Architecture) i rekomendacje Google dla systemu Android:
* **Kotlin:** Główny język programowania, gwarantujący bezpieczeństwo typów i null-safety.
* **Jetpack Compose:** Deklaratywny framework UI pozwalający na tworzenie płynnych i responsywnych interfejsów przy mniejszej ilości kodu.
* **Dagger Hilt:** Framework do wstrzykiwania zależności (Dependency Injection), ułatwiający testowanie i skalowanie aplikacji.
* **Room Database:** Warstwa abstrakcji nad SQLite, pozwalająca na bezpieczne i wydajne zarządzanie lokalnymi danymi.
* **Jsoup:** Biblioteka do asynchronicznego scrapowania i parsowania struktury HTML z zewnętrznych stron WWW.

## 🚀 Uruchomienie lokalne

1. Pobierz środowisko [Android Studio](https://developer.android.com/studio).
2. Sklonuj to repozytorium:
   ```bash
   git clone [https://github.com/TwojNick/arbitrello-app.git](https://github.com/TwojNick/arbitrello-app.git)
3.  Otwórz projekt w Android Studio i poczekaj na zakończenie synchronizacji Gradle.
4.  Uruchom aplikację na podłączonym urządzeniu z Androidem lub za pomocą wbudowanego emulatora (AVD).

## 📸 Zrzuty ekranu / UI Showcase
| | | |
|:---:|:---:|:---:|
| <img height="400" alt="Image" src="https://github.com/user-attachments/assets/766ca899-91ce-4d87-9546-654cee9d7b45" /> | <img height="400" alt="Image" src="https://github.com/user-attachments/assets/e61fe1c3-809c-49e1-9d8f-3d9f8234e41d" /> | <img height="400" alt="Image" src="https://github.com/user-attachments/assets/4edc4ac8-b95a-4014-8160-12a8ffdaf8f6" /> |
| <img height="400" alt="Image" src="https://github.com/user-attachments/assets/840a01c9-4833-4626-add8-3ea8d2a6f4c6" /> | <img height="400" alt="Image" src="https://github.com/user-attachments/assets/a3cd591c-7ec9-40d3-be3d-057fb35bbc96" /> | <img height="400" alt="Image" src="https://github.com/user-attachments/assets/8d994739-c424-4a05-a6ee-a6434d127739" /> |
| <img height="400" alt="Image" src="https://github.com/user-attachments/assets/b3d78eee-cf85-4dcf-81b4-9a4bf639a06a" /> | <img height="400" alt="Image" src="https://github.com/user-attachments/assets/ca1fd9ff-a3ee-4602-bfe1-92e49836508a" /> | <img height="400" alt="image" src="https://github.com/user-attachments/assets/fe29e952-f7fc-4fc8-8996-0ec54b53713f" /> |
