### **Dokumentacja Systemu StaffPulse 2.0 (Wersja MVP)**

*Dedykowany system zarządzania reputacją cyfrową i grywalizacją operacyjną dla obiektów hotelarskich klasy Premium – w 100% zgodny z europejską Dyrektywą Omnibus oraz Google Policy 2026\.*

#### **1\. Opis Marketingowy: Dlaczego Twój hotel musi to mieć?**

W branży hospitality premium o Twoich zyskach nie decyduje już tylko standard pokoi czy jakość jedzenia. Decydują bezlitosne algorytmy Google i TripAdvisor.  
Każdego dnia Twój hotel opuszczają dziesiątki zachwyconych gości. Problem w tym, że **zadowolony klient milczy**. Wraca do domu, ignoruje automatyczne maile z prośbą o opinię (które mają żałosne 2% konwersji) i zapomina o sprawie. W internecie zostajesz sam na sam z "głośną mniejszością" – gośćmi, którzy z powodu 10-minutowego opóźnienia lub zimnej zupy z determinacją wystawiają Ci 1 gwiazdkę.  
Spadek ogólnej oceny choćby o ułamek gwiazdki oznacza, że znikasz z pierwszych stron wyszukiwania. Tracisz najbardziej dochodowe rezerwacje bezpośrednie i stajesz się zakładnikiem platform OTA, płacąc im gigantyczne 15-22% prowizji, byle tylko zapełnić pokoje.  
**StaffPulse 2.0 to koniec tej asymetrii.** Rozwiązujemy problem dokładnie tam, gdzie powstają emocje – w hotelu, przy stoliku, w zaledwie 4 sekundy.  
**Jak to zmieni Twój biznes?**

* **Wzrost rezerwacji bezpośrednich (Direct Bookings):** Wykorzystując moment największego zachwytu gościa (np. po świetnej kolacji), zbierasz organiczne opinie na żywo. Algorytmy wypychają Twój hotel na szczyt wyników, a Ty odzyskujesz marżę zjadaną przez OTA.  
* **Koniec z pożarami w internecie (Tarcza Antykryzysowa):** Niezadowolony gość nie musi już wylewać frustracji w Google. System przechwytuje go w hotelu i natychmiast powiadamia Twojego managera zmiany, dając Wam szansę na zażegnanie kryzysu na miejscu.  
* **Pełne bezpieczeństwo prawne:** Przestarzałe systemy ukrywające negatywne opinie (review gating) są dziś nielegalne – grożą blokadą wizytówki Google i potężnymi karami finansowymi od krajowych organów ochrony konsumentów (zgodnie z Dyrektywą Omnibus). StaffPulse 2.0 opiera się na psychologii, a nie cenzurze, zapewniając 100% legalności.  
* **System, który pracuje sam (Grywalizacja):** Twój personel walczy o wewnętrzne punkty i premie, dlatego z własnej woli zachęca gości do skanowania kodów. Ty nie tracisz czasu na mikrozarządzanie.

#### **2\. Opis Funkcjonalny**

StaffPulse 2.0 w wersji MVP skupia się na błyskawicznym zbieraniu ocen, pełnej automatyzacji po stronie hotelu i braku skomplikowanych integracji IT:

* **Automatyczny Generator Nośników (Self-Service):** Po wprowadzeniu danych personelu przez managera, system natychmiast generuje gotowe do druku pliki PDF z unikalnymi kodami QR dla każdego pracownika. Hotel we własnym zakresie zleca ich wydruk w lokalnej drukarni, zachowując 100% kontroli nad rodzajem użytego papieru czy materiału.  
* **Silnik Dual-Path Feedback:** Niezależnie od oceny, system zawsze prezentuje link do publicznych platform (legalność). Dynamicznie dopasowuje jednak priorytetowe elementy interfejsu w zależności od nastroju gościa.  
* **Integracja z WhatsApp:** System wysyła natychmiastowe powiadomienia do kadry kierowniczej w przypadku zgłoszenia krytycznego.  
* **Panel Analityczny (Dashboard):** Dwuwarstwowy podgląd danych operacyjnych dla managerów i dyrekcji.

#### **3\. Profil Psychologiczny Odbiorcy (General Managera)**

* **Cechy kluczowe:** Zorientowany na twarde wskaźniki (RevPAR, marża), obsesyjnie dbający o wizerunek marki w sieci, wyczulony na punkcie prawa, nienawidzi skomplikowanych wdrożeń informatycznych.  
* **Główne obawy:** Bunt i bierność personelu przy wdrażaniu nowych procedur, ryzyko otrzymania kar finansowych od organów nadzorczych lub bana od Google za nielegalne manipulowanie opiniami, rosnące koszty prowizji dla pośredników.  
* **Jak sprzedawać:** Skup się na błyskawicznym ROI i odzyskaniu marży. Udowodnij, że system napędza się sam (dzięki ambicjom personelu), a wdrożenie nie wymaga angażowania hotelowego działu IT.

#### **4\. Szczegółowy Scenariusz Użycia (UX & Architektura Interfejsu)**

**Krok 1: Fizyczny punkt styku (Wizytówka / Stojak)** W momencie finalizacji usługi (przy płaceniu rachunku w restauracji lub podczas check-outu na recepcji) pracownik prezentuje gościowi fizyczny nośnik z kodem QR.

* **Wydruk po stronie hotelu:** Ponieważ StaffPulse generuje zautomatyzowane pliki PDF, rekomendujemy hotelom wydruk na materiałach premium (np. czarny mat, złote tłoczenie), aby idealnie dopasować się do standardu obiektu.  
* **Co znajduje się na nośniku:** Logo hotelu, personalizacja: *"Obsługiwał Cię dzisiaj: \[Imię Pracownika\]"*, wyraźne wezwanie do działania: *"Oceń naszą pracę w 4 sekundy. Zeskanuj kod QR"*.  
* **Psychologia:** Wręczenie wizytówki twarzą w twarz drastycznie zwiększa presję społeczną na wykonanie interakcji, w przeciwieństwie do ignorowanych wiadomości e-mail.

**Krok 2: Skan i Ekran Startowy (Widok 1\)** Gość skanuje QR. W ułamku sekundy, bez konieczności logowania, ładuje się minimalistyczna, luksusowa strona w dark mode.  
**WIDOK 1: Ocena Wstępna (Wszystkie oceny zaczynają się tutaj)**  
\[ LOGO HOTELU \]  
Jak oceniasz pracę, którą wykonał dzisiaj **\[Imię Pracownika\]**?  
⭐ ⭐ ⭐ ⭐ ⭐  
*Jedno kliknięcie. Zależy nam na Twojej opinii.*  
**Krok 3: Dynamiczne przekierowanie (Dual-Path)**  
Po kliknięciu w wybraną gwiazdkę interfejs natychmiast dostosowuje się do wybranej ścieżki.  
**Ścieżka A: Pozytywna (Gość zaznacza 4 lub 5 gwiazdek)**  
System wykorzystuje stan entuzjazmu klienta, ułatwiając mu maksymalnie dodanie publicznej recenzji.  
**WIDOK 2A: Podziękowanie i Eskalacja Sukcesu**  
🎉 Dziękujemy za docenienie naszej pracy\!  
Twoja opinia pomaga nam rosnąć. Podziel się nią ze światem na wybranym portalu:  
\[ 🔵 Opublikuj opinię w Google Maps \] *(Główny, duży przycisk)*  
\[ 🟢 Opublikuj opinię na TripAdvisor \] *(Główny, duży przycisk)*  
**Ścieżka B: Negatywna / Reklamacyjna (Gość zaznacza 1, 2 lub 3 gwiazdki)** Zgodnie z wymogami prawnymi (Omnibus) i polityką platform, **linki do publicznych recenzji muszą być widoczne**. Jednak na pierwszym planie stosujemy psychologiczny "bezpiecznik" – priorytetowe rozwiązanie problemu tu i teraz.  
**WIDOK 2B: Tarcza Antykryzysowa**  
⚠️ Przepraszamy, że nie spełniliśmy Twoich oczekiwań.  
Zależy nam na perfekcji. Pozwól nam naprawić ten błąd natychmiast. Wyślij pilne zgłoszenie bezpośrednio do Managera Zmiany:  
\[ Textarea: Co poszło nie tak? (np. zimne danie, hałas w pokoju...) \]  
\[ Input: Twój numer pokoju lub stolika (opcjonalnie) \]  
\[ 🚨 WEZWIJ MANAGERA ZMIANY (Pilny Alert) \] *(Duży, czerwony przycisk akcji)*  
*Chcesz pominąć kontakt z managerem? Możesz również opublikować publiczną recenzję:*  
\[ Przejdź do opinii w Google Maps \] *(Szary, mniej rzucający się w oczy przycisk pod spodem)*  
\[ Przejdź do opinii na TripAdvisor \] *(Szary, mniej rzucający się w oczy przycisk pod spodem)*

#### **5\. Co widzi kadra zarządzająca? (Backend & Alerty)**

**A. Co dokładnie widzi Manager Zmiany (Duty Manager)?** Informacje o kryzysie otrzymuje w formie **natychmiastowego powiadomienia na aplikację WhatsApp**, gdy gość wyśle formularz z widoku 2B:  
🚨 ALERT STAFFPULSE — \[Nazwa Hotelu\]  
Status: PILNA INTERWENCJA (Service Recovery)  
Ocena: 2/5 ⭐  
Lokalizacja: Lobby Bar  
Obsługujący pracownik: Mateusz Kowalski  
Wiadomość od gościa:  
"Czekam na zamówienie już 35 minut, barman obsługuje osoby, które przyszły po mnie."  
Pokój / Stolik: Stolik nr 8  
\[Akcja sugerowana\]: Podejdź do stolika nr 8, zaoferuj rekompensatę i rozwiąż problem przed wyjazdem gościa.  
**B. Co dokładnie widzi Dyrektor Generalny (GM)?**  
Widzi analitykę nastawioną na kontrolę operacyjną i wyniki finansowe:

> 1. **Wskaźnik Aktywności (Skanowania):** Całkowita liczba unikalnych skanów kodów. Pozwala to ocenić, czy zespół faktycznie korzysta z systemu.  
> 2. **Tablica Grywalizacji (Leaderboard):** Ranking pracowników uporządkowany według *liczby zebranych unikalnych skanów* (aktywności), a nie wysokości ocen. Chroni to system przed patologiami ("cherry-picking") oraz filtrami antyspamowymi.  
> 3. **Licznik Crisis Averted (Uratowane recenzje):** Statystyka pokazująca, ile razy gość kliknął 1-3 gwiazdki, ale zamiast napisać negatywną recenzję w sieci, wysłał alert do Managera.

**⚙️ Ważna Logika Grywalizacji:** Punkty w rankingu przyznawane są za **fakt zaangażowania gościa (unikalny skan)**. Dzięki temu pracownicy nie boją się podawać wizytówek osobom niezadowolonym, co gwarantuje pełną efektywność tarczy antykryzysowej. Backend filtruje próby oszustw poprzez analizę unikalności urządzeń (IP, geolokalizacja).

#### **6\. Cennik Usług (Model SaaS)**

Rozliczenie w euro, bez ukrytych kosztów integracyjnych. Pakiety dostosowane do skali działalności obiektu.

| Wielkość Obiektu | Umowa na 1 miesiąc | Umowa na 6 miesięcy (-10%) | Umowa na 12 miesięcy (-20%) |
| :---- | :---- | :---- | :---- |
| **Boutique** (do 100 pokoi) | 199 € / mc | 1,074 € *(179 € / mc)* | 1,910 € *(159 € / mc)* |
| **Resort** (101 \- 250 pokoi) | 299 € / mc | 1,614 € *(269 € / mc)* | 2,870 € *(239 € / mc)* |
| **Enterprise** (powyżej 250 pokoi) | 449 € / mc | 2,424 € *(404 € / mc)* | 4,310 € *(359 € / mc)* |

*\* Przy wyborze umowy na 1 miesiąc doliczana jest jednorazowa opłata za początkową konfigurację systemu i onboarding (Setup Fee): 250 EUR. W pakietach 6m i 12m wdrożenie jest bezpłatne.*

#### **7\. Materiały Promocyjne & Przewagi Rynkowe**

**Główne przewagi nad tradycyjnymi systemami:**

* **20-40% konwersji zamiast 2%:** Zbieranie opinii na żywo w hotelu w 4 sekundy całkowicie deklasuje ignorowane i spóźnione ankiety mailowe.  
* **Pełne bezpieczeństwo prawne:** W przeciwieństwie do systemów filtrujących konkurencji (tzw. review gating), StaffPulse 2.0 jest w 100% legalny w świetle europejskiej Dyrektywy Omnibus i wytycznych Google. Zamiast blokować krytykę, dajemy klientowi szybszą i wygodniejszą alternatywę w postaci bezpośredniego wezwania managera.  
* **Wdrożenie bez obciążenia dla IT:** System typu Standalone. Brak konieczności integracji z systemami hotelowymi (PMS), brak konfiguracji serwerowych. Działa niezależnie od momentu uruchomienia. Wystarczy wydrukować gotowe pliki PDF dostarczone przez platformę.