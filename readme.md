# 🎾 TennisBlog — Mobilne Kompendium Tenisa

Nowoczesna, lekka i w pełni responsywna aplikacja internetowa (Mobile-First), zaprojektowana dla pasjonatów tenisa. Projekt skupia się na dostarczaniu rzetelnej wiedzy o sprzęcie, technice oraz najważniejszych turniejach świata w przejrzystej formie.

---

## 🚀 O Projekcie

Strona została zbudowana z myślą o użytkownikach mobilnych. Dzięki zastosowaniu sztywnego kontenera `440px` na szerokich ekranach, projekt symuluje natywną aplikację na smartfony (PWA Style).

### **Kluczowe Sekcje:**
* **Equipment (Sprzęt):** Szczegółowe analizy rakiet, naciągów i technologii obuwia.
* **Technika i Trening:** Przewodnik krok po kroku po uderzeniach wraz z planami treningowymi.
* **Grand Slam:** Multimedialna baza wiedzy o turniejach wielkoszlemowych i rekordach GOAT.
* **Contact:** Sekcja kontaktowa z lokalizacją i godzinami pracy.

---

## 🛠️ Technologie i Metodologia

* **HTML5:** Semantyczna i czysta struktura.
* **CSS3 (Metodyka BEM):** Kod napisany w systemie *Block-Element-Modifier*, co zapewnia łatwą rozbudowę i brak konfliktów w stylach.
* **Google Fonts:** Wykorzystanie fontu **Montserrat** (400, 600, 700, 800) dla sportowego charakteru.
* **Mobile-First:** Projekt zoptymalizowany pod kątem ekranów dotykowych i pionowej nawigacji.

---

## 🎨 Kolorystyka (Branding)

| Kolor | Hex | Zastosowanie |
| :--- | :--- | :--- |
| **Dark Brown** | `#1D1716` | Tła sekcji, nagłówki, stopka |
| **Gold/Sand** | `#F3BC77` | Ikony, akcenty, przyciski, numery |
| **White** | `#FFFFFF` | Tekst główny, tła kart |
| **Soft Gray** | `#F4F4F4` | Tło zewnętrzne (desktop) |

---

## 📂 Struktura Projektu

```text
├── Css/
│   ├── Menu.css         # Style strony głównej
│   ├── Equipment.css    # Style sekcji sprzętowej
│   ├── Training.css     # Style sekcji technicznej
│   └── Tournaments.css  # Style sekcji Grand Slam
├── Navigation/
│   ├── Equipment.html   # Strona docelowa: Sprzęt
│   ├── Training.html    # Strona docelowa: Technika
│   └── Tournaments.html # Strona docelowa: Turnieje
├── index.html           # Menu główne (Home)
└── README.md            # Dokumentacja projektu