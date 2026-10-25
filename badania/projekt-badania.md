# Projekt badania: „spacery AI” – mikro-planer spacerów miejskich

Dokument opisuje, jak zespół może zweryfikować temat projektu: czy problem istnieje, kogo dotyczy, czy grupa docelowa jest gotowa korzystać z planera opartego na AI i czy model B2B2C (darmowo dla spacerowiczów, płatne „sponsored pins” dla lokalnych biznesów) jest akceptowany przez spacerowiczów. Na badanie zespół ma najwyżej dwa tygodnie, dlatego jest to jedna anonimowa ankieta dla spacerowiczów, bez wywiadów i bez badania lokalnych biznesów. Punktem wyjścia są trzy dokumenty zespołu: karta zgłoszenia tematu, opis grupy docelowej (trzy persony) oraz analiza konkurencji z lukami rynkowymi 1–5.

Liczby podane w tym dokumencie dotyczą wyłącznie metodologii (np. liczebności prób w cytowanych badaniach). Dokument nie podaje żadnych danych o wielkości rynku, bo zespół takich danych nie zebrał. Hipotezy poniżej są do sprawdzenia, a nie przyjętymi faktami.

---

## 1. Cel badania, pytania badawcze i hipotezy

### 1.1. Cel główny

Celem badania jest sprawdzenie, czy osoby mające 1–2 godziny wolnego czasu w mieście rzeczywiście napotykają problemy opisane w analizie konkurencji, jak dziś sobie z nimi radzą i czy zaakceptowałyby trasę wygenerowaną przez AI, w tym trasę zawierającą oznaczone punkty sponsorowane. Wyniki posłużą do wyboru funkcji pierwszej wersji aplikacji. Lokalnych biznesów (płatników w modelu B2B2C) w tym badaniu nie pytamy. Sprawdzamy tylko, czy spacerowicze zaakceptują ich oferty na trasie.

### 1.2. Pytania badawcze

- **PB1.** Jak często i w jakich sytuacjach respondenci mają krótkie okno czasowe w mieście i co wtedy faktycznie robią?
- **PB2.** Jak dziś planują krótki spacer, z jakich narzędzi korzystają i ile czasu to zajmuje?
- **PB3.** Które z luk rynkowych 1–5 są realnym, doświadczanym problemem, a które istnieją głównie w naszej analizie?
- **PB4.** Na ile respondenci ufają rekomendacjom AI i co to zaufanie zwiększa lub obniża?
- **PB5.** Które funkcje są dla użytkowników oczekiwanym minimum, które są atrakcyjne, a które obojętne?
- **PB6.** Czy użytkownicy zaakceptują punkty sponsorowane i pod jakimi warunkami?
### 1.3. Hipotezy powiązane z lukami i personami

| Hipoteza | Treść | Luka | Persona | Pytania ankiety |
|---|---|---|---|---|
| **H1** | Osoby z oknem 1–2 h poza domem rezygnują ze spaceru lub go skracają z obawy, że nie zdążą wrócić na czas, albo dlatego, że ciekawe trasy zaczynają się daleko od miejsca, w którym są. | 1 | P1 (podróżny w tranzycie) | A3, B1, B4a, C1, C2, E-K1a, E-K1b |
| **H2** | Planowanie krótkiego spaceru w ogólnych mapach zajmuje odczuwalną część dostępnego czasu i kończy się wyborem czegoś znanego lub przypadkowego (paraliż wyboru). | 3 | P1, P2 | B2, B3, C3, C4 |
| **H3** | Osoby, które planowały wyjście z czatem AI, napotkały błędy przestrzenne lub czasowe (zamknięte miejsca, nierealne odległości), a ich zaufanie do AI jest warunkowe i rośnie, gdy rekomendację da się zweryfikować. | 2 | wszystkie | C5, C8a, C8, D2, D3, D5, E-K3 |
| **H4** | Świadomi turyści korzystają z forów, grup i blogów, a polecenia ręcznie przenoszą do nawigacji. | 5 | P3 | B2, C6 |
| **H5** | Mieszkańcy chcą odkrywać okolicę, ale robią to rzadko, a cisza, zieleń i unikanie tłumu są dla nich ważniejsze niż znane atrakcje. | – (cel społeczny) | P2, P3 | A4, B4, C7, E-K4 |
| **H6** | Użytkownicy akceptują punkt sponsorowany, jeśli jest wyraźnie oznaczony i pasuje do zapytania, a nieoznaczona promocja obniża zaufanie do całej trasy. | 4 | wszystkie | E-K6, F3, G1–G5 |
| **H7** | Większość spacerowiczów nie płaci dziś za narzędzia do planowania spacerów i nie zapłaciłaby za aplikację, co uzasadnia model B2B2C. | model | wszystkie | F2, F3 |

Wszystkie hipotezy sprawdza ankieta. Ich „dlaczego” częściowo pokażą pytania otwarte (B5, C9). Hipoteza o gotowości lokalnych biznesów do płacenia za mikro-oferty zostaje nieprzetestowana. Wymaga rozmów z lokalami, które są poza zakresem tego badania.

Część pytań nie weryfikuje żadnej hipotezy, ale ma inną, określoną rolę:

| Pytanie | Rola |
|---|---|
| A1, A2, A5, A6 | screening i kontrola struktury próby |
| D1 | zmienna kontrolna: doświadczenie z AI (filtr dla D2–D3) |
| D4, E-K2 | decyzja projektowa: opis słowami czy filtry jako główne wejście |
| D6 | warunek techniczny trasy „od drzwi do drzwi” |
| E-K5 | forma treści przy punktach trasy |
| F1 | orientacyjne zainteresowanie per persona (górna granica) |
| B5, C9 | odpowiedzi otwarte: cytaty i problemy spoza listy luk |

---

## 2. Projekt ankiety dla spacerowiczów

### 2.1. Założenia

Ankieta ma zająć około 10 minut. Pytania są ułożone tak, by najpierw pytać o fakty z przeszłości, potem o problemy, a dopiero na końcu o pomysł aplikacji. Kolejność jest celowa: gdy respondent pozna nasz pomysł zbyt wcześnie, zaczyna odpowiadać „pod niego”. Nielsen zwraca uwagę, że to, co użytkownicy mówią, i to, co robią, często się różni, a ludzie potrafią wytworzyć opinię na dowolny temat, gdy się ich o nią zapyta ([Nielsen, 2010](https://www.nngroup.com/articles/interviewing-users/)). Dlatego tam, gdzie to możliwe, pytamy o konkretne zdarzenia z ostatnich miesięcy, a nie o deklaracje na przyszłość. To ta sama zasada, którą Fitzpatrick formułuje dla rozmów z klientami: pytaj o życie rozmówcy i o konkretne sytuacje z przeszłości, a nie o opinie na temat swojego pomysłu ([Fitzpatrick, 2013](https://www.momtestbook.com/)).

Skale pięciopunktowe wywodzą się z techniki Likerta (Likert, 1932). W pytaniach o problemy zamiast skali zgody („zgadzam się”) używamy skali częstości odniesionej do ostatnich 12 miesięcy, bo pytanie o to, jak często coś się zdarzyło, mniej zachęca do bezrefleksyjnego potakiwania niż pytanie o zgodę ze stwierdzeniem.

Oznaczenia typów: **J** – jednokrotny wybór, **W** – wielokrotny wybór, **L5** – skala pięciopunktowa, **O** – pytanie otwarte, **K** – para pytań Kano. Gwiazdka (*) oznacza pytanie obowiązkowe. Pytania oznaczone jako „opcjonalne do cięcia” można usunąć, jeśli pilotaż pokaże czas wypełniania powyżej 12 minut.

**Skale używane wielokrotnie:**

- **Skala częstości (SC):** Nigdy / Raz / Kilka razy / Często / Prawie za każdym razem.
- **Skala zgody (SZ):** Zdecydowanie się nie zgadzam / Raczej się nie zgadzam / Ani się zgadzam, ani nie zgadzam / Raczej się zgadzam / Zdecydowanie się zgadzam.

### 2.2. Tekst wprowadzenia (do wklejenia)

> Dzień dobry! Jesteśmy zespołem studentów Politechniki Łódzkiej. Badamy, jak ludzie spędzają krótki wolny czas w mieście (1–2 godziny) i jak planują spacery. Ankieta jest anonimowa i zajmie około 10 minut. Nie ma dobrych ani złych odpowiedzi – interesują nas Twoje prawdziwe doświadczenia. Udział jest dobrowolny i możesz przerwać w dowolnym momencie. Wyniki wykorzystamy wyłącznie w zestawieniach zbiorczych w projekcie zaliczeniowym. Kontakt: [adres e-mail zespołu].

Wprowadzenie celowo nie wspomina o aplikacji ani o AI, żeby nie ukierunkować odpowiedzi w blokach B i C.

### 2.3. Blok A – screening i metryczka

**A1*. Ile masz lat?** (J)
Poniżej 18 / 18–24 / 25–34 / 35–44 / 45–50 / 51 lub więcej
*Cel:* screening (osoby poniżej 18 lat kończą ankietę, bo badanie małoletnich wymaga zgody opiekuna) i porównanie z przedziałami wieku person (20–50 lat). Granica 50/51 pozwala oddzielić osoby spoza przedziału person.

**A2*. Czy w ciągu ostatnich 12 miesięcy zdarzyło Ci się mieć około 1–2 godzin wolnego czasu w mieście, który można było przeznaczyć na spacer?** (J)
Tak / Nie / Nie pamiętam
*Cel:* screening. Odpowiedzi „Nie” i „Nie pamiętam” kierują do bloku D (stosunek do AI), a potem do końca ankiety, z pominięciem bloków A3–C oraz E–G i Z. Dzięki temu nie tracimy informacji o osobach spoza grupy docelowej, ale nie mieszamy ich z odpowiedziami o problemach i funkcjach. Odpowiedzi z bloku D tej grupy analizujemy osobno.

**A3*. Pomyśl o ostatniej takiej sytuacji. Która odpowiedź najlepiej ją opisuje?** (J)
- Czekałem/-am na przesiadkę lub odjazd (pociąg, autobus, samolot) w innym mieście
- Byłem/-am w innym mieście w delegacji lub na spotkaniu
- Miałem/-am przerwę lub wolny czas w mieście, w którym mieszkam lub pracuję
- Byłem/-am turystycznie w mieście, które już wcześniej odwiedzałem/-am
- Byłem/-am turystycznie w mieście, w którym byłem/-am pierwszy raz
- Inna sytuacja (jaka?)

*Cel:* przypisanie respondenta do persony (P1: dwie pierwsze odpowiedzi, P2: trzecia, P3: czwarta; piąta to turysta „klasyczny”, raczej poza grupą docelową). Zmienna kluczowa dla tabel krzyżowych. Hipotezy: H1, H4, H5.

Zasady przypisania:
- **Delegacja w P1 jest założeniem do sprawdzenia** z opisem persony P1 (podróżny w tranzycie). W tabelach krzyżowych raportujemy przesiadkę i delegację także osobno. Jeśli wyniki obu grup wyraźnie się różnią, delegację przenosimy do osobnej kategorii.
- **„Inna sytuacja”** koduje ręcznie jedna osoba z zespołu, a druga sprawdza kodowanie. Odpowiedź, której nie da się przypisać, trafia do kategorii „bez persony” i liczy się tylko w wynikach dla całej próby.
- **Persona opisuje sytuację, nie człowieka.** Ta sama osoba może być raz P1, a raz P2, więc przypisanie dotyczy ostatniej sytuacji. To ograniczenie opisujemy w raporcie.

**A4*. Ile razy w ciągu ostatnich 3 miesięcy poszedłeś/-aś na co najmniej 30-minutowy spacer po mieście tylko dla przyjemności (nie do pracy, sklepu itp.)?** (J)
Ani razu / 1–2 razy / 3–5 razy / 6–10 razy / Więcej niż 10 razy
*Cel:* faktyczna częstość zachowania (H5).

**A5. Ile razy w ciągu ostatnich 12 miesięcy byłeś/-aś w innym mieście (prywatnie lub służbowo)?** (J)
Ani razu / 1–2 razy / 3–5 razy / 6 lub więcej razy
*Cel:* charakterystyka P1 i P3. Opcjonalne do cięcia.

**A6*. Jak duże jest miasto, w którym mieszkasz?** (J)
Wieś / Miasto do 100 tys. mieszkańców / 100–500 tys. / Powyżej 500 tys.
*Cel:* metryczka, kontrola struktury próby.

### 2.4. Blok B – obecne zachowania i planowanie

**B1*. Co faktycznie zrobiłeś/-aś w tej ostatniej sytuacji (z pytania A3)?** (J)
- Poszedłem/-am na spacer bez planu, „przed siebie”
- Poszedłem/-am w jedno konkretne miejsce, które już znałem/-am
- Przed wyjściem zaplanowałem/-am trasę z kilkoma punktami
- Zostałem/-am na miejscu (dworzec, hotel, biuro, kawiarnia obok)
- Inaczej (jak?)

*Cel:* zachowanie bazowe, z którym konkuruje aplikacja (H1, H2). Odpowiedź „Zostałem/-am na miejscu” u P1 jest ważnym sygnałem dla H1. Osoby, które ją wybiorą, dostają w B2 i B3 te same pytania (mogły szukać miejsc, zanim zrezygnowały), a zamiast B4 pytanie B4a.

**B2*. Z jakich źródeł skorzystałeś/-aś, szukając miejsc lub planując wyjście w tej sytuacji?** (W)
- Google Maps lub Apple Maps
- TripAdvisor lub podobny serwis z opiniami
- Czat AI (np. ChatGPT, Gemini, Copilot)
- Aplikacja z gotowymi trasami (np. VoiceMap, Go Jauntly, Questo)
- Grupy na Facebooku, Reddit, fora
- Blogi, Instagram, TikTok, YouTube
- Rady znajomych lub rodziny
- Punkt informacji turystycznej lub papierowa mapa
- Z żadnego
- Inne (jakie?)

*Cel:* mapa obecnych rozwiązań (H2, H3, H4). Lista zawiera konkurentów z analizy, ale też opcje „żadne” i „inne”, żeby nie sugerować, że korzystanie z narzędzia jest normą.

**B3*. Ile mniej więcej czasu zajęło Ci szukanie miejsc i planowanie?** (J)
Nie planowałem/-am / Mniej niż 5 minut / 5–15 minut / 15–30 minut / Ponad 30 minut / Nie pamiętam
*Cel:* H2. Analiza konkurencji zakłada, że planowanie zjada sporą część okna czasowego. To pytanie pozwala to sprawdzić zamiast przyjmować.

**B4*. Co było dla Ciebie najważniejsze podczas tego spaceru? Wybierz maksymalnie 3.** (W, limit 3; tylko gdy w B1 nie wybrano „Zostałem/-am na miejscu”)
Zobaczyć znane atrakcje / Odkryć mniej znane miejsca / Spokój i cisza / Zieleń / Dobra kawa lub jedzenie / Ruch i zdrowie / Zdjęcia / Zakupy / Zdążyć wrócić na czas / Inne (jakie?)
*Cel:* motywacje per persona (H5), dane do priorytetów kategorii POI.

**B4a*. Co sprawiło, że zostałeś/-aś na miejscu? Wybierz maksymalnie 3.** (W, limit 3; tylko gdy w B1 wybrano „Zostałem/-am na miejscu”)
Za mało czasu / Obawa, że nie zdążę wrócić / Nie wiedziałem/-am, dokąd pójść / Ciekawe miejsca były za daleko / Pogoda / Zmęczenie lub bagaż / Nie miałem/-am ochoty / Inne (jakie?)
*Cel:* H1. Pokazuje, ile rezygnacji wynika z obawy o czas i z odległości (luka 1), a ile z przyczyn, na które aplikacja nie ma wpływu (pogoda, zmęczenie).

**B5. Opisz krótko ostatni spacer po mieście, który był dla Ciebie szczególnie udany albo nieudany. Co o tym zdecydowało?** (O, nieobowiązkowe)
*Cel:* cytaty i nieprzewidziane problemy. Bez wywiadów to jedno z dwóch źródeł odpowiedzi na pytanie „dlaczego” (obok C9), więc warto go nie wycinać, chyba że pilotaż pokaże zbyt długi czas wypełniania.

### 2.5. Blok C – problemy (luki 1–5)

**C1–C7. Jak często w ciągu ostatnich 12 miesięcy zdarzyły Ci się poniższe sytuacje?** (macierz, skala SC, odpowiedź „Nie dotyczy” dostępna w każdym wierszu)

| Nr | Stwierdzenie | Luka / hipoteza |
|---|---|---|
| C1 | Zrezygnowałem/-am ze spaceru albo go skróciłem/-am, bo bałem/-am się, że nie zdążę wrócić na czas (np. na pociąg lub spotkanie). | 1 / H1 |
| C2 | Ciekawa trasa lub atrakcja okazała się zbyt daleko od miejsca, w którym byłem/-am, żeby z niej skorzystać. | 1 / H1 |
| C3 | Spędziłem/-am na przeglądaniu map i opinii więcej czasu, niż chciałem/-am. | 3 / H2 |
| C4 | Nie mogłem/-am się zdecydować, dokąd pójść, i wybrałem/-am coś przypadkowego lub dobrze znanego. | 3 / H2 |
| C5 | Dotarłem/-am do miejsca, które okazało się zamknięte, choć źródło sugerowało, że będzie otwarte. | 2 / H3 |
| C6 | Przepisywałem/-am ręcznie miejsca z listy (forum, blog, czat AI) do aplikacji z mapą. | 5 / H4 |
| C7 | Trafiłem/-am w zatłoczone miejsce, którego wolałbym/wolałabym uniknąć. | – / H5 |

Każdy wiersz dotyczy jednej sytuacji. Celowo nie łączymy np. „szukanie trwało długo i wybrałem coś przypadkowego” w jednym zdaniu, bo pytanie o dwie rzeczy naraz (tzw. pytanie dwulufowe) nie pozwala ustalić, której części dotyczy odpowiedź.

**C8a. Czy w ciągu ostatnich 12 miesięcy korzystałeś/-aś z czatu AI (np. ChatGPT, Gemini, Copilot), szukając miejsc lub planując wyjście w mieście?** (J)
Tak / Nie / Nie pamiętam
*Cel:* filtr do C8. Obejmuje ten sam okres co C1–C7, a nie tylko ostatnią sytuację z B2, więc nie pomija osób, które użyły AI przy innej okazji.

**C8. Pytanie warunkowe (tylko gdy w C8a odpowiedziano „Tak”): Czy plan albo polecenia od czatu AI zawierały któryś z poniższych błędów?** (W)
Miejsce było zamknięte / Odległości lub czas przejścia były nierealne / Miejsce nie istniało lub było pod innym adresem / Kolejność punktów nie miała sensu na mapie / Nie zauważyłem/-am błędów / Nie sprawdzałem/-am
*Cel:* H3, bezpośrednia weryfikacja luki 2.

**C9. Co najbardziej przeszkadza Ci w planowaniu krótkiego spaceru po mieście?** (O, nieobowiązkowe)
*Cel:* wychwycenie problemów spoza listy luk. To pytanie warto zadać przed blokiem D, póki respondent nie myśli jeszcze o AI.

### 2.6. Blok D – stosunek do AI i zaufanie do rekomendacji

Pytania D2–D4 są luźno inspirowane konstruktami modelu akceptacji technologii TAM, czyli postrzeganą użytecznością i postrzeganą łatwością użycia ([Davis, 1989](https://doi.org/10.2307/249008)). Nie są to jednak zwalidowane skale Davisa (te mają po sześć pozycji na konstrukt), tylko pojedyncze pytania. Nie należy więc liczyć z nich wskaźników TAM ani porównywać ich z literaturą.

**D1*. Jak często w ciągu ostatniego miesiąca korzystałeś/-aś z czatu AI (np. ChatGPT, Gemini, Copilot) w dowolnym celu?** (J)
Ani razu / Raz lub dwa razy / Kilka razy w miesiącu / Co tydzień / Codziennie lub prawie codziennie
*Cel:* faktyczne doświadczenie z AI, zmienna kontrolna do D2–D5.

**D2–D4. Na ile zgadzasz się z poniższymi zdaniami?** (macierz, skala SZ; D2 i D3 tylko gdy w D1 nie wybrano „Ani razu”, bo bez doświadczenia z AI odpowiedź byłaby zgadywaniem; D4 widzą wszyscy)
- **D2.** Polecenia miejsc wygenerowane przez AI są zazwyczaj trafne. *(H3, postrzegana użyteczność)*
- **D3.** Zanim pójdę w miejsce polecone przez AI, sprawdzam je w innym źródle. *(H3, zachowanie weryfikacyjne)*
- **D4.** Opisanie własnymi słowami, czego szukam (np. „mam godzinę, chcę ciszy i dobrej kawy”), jest dla mnie wygodniejsze niż ustawianie filtrów w aplikacji. *(postrzegana łatwość użycia, E-K2)*

D2 jest sformułowane neutralnie: nie pisze „AI świetnie poleca miejsca”, tylko pyta o trafność, a skala ma symetryczne odpowiedzi negatywne i pozytywne.

**D5*. Co zwiększyłoby Twoje zaufanie do trasy zaproponowanej przez AI? Wybierz maksymalnie 3.** (W, limit 3)
- Godziny otwarcia sprawdzone w momencie planowania
- Podany czas przejścia i pewność powrotu na czas
- Oceny i opinie innych osób
- Informacja, skąd pochodzi dana rekomendacja
- Możliwość samodzielnej zmiany trasy
- Polecenia od mieszkańców
- Nic, nie ufam trasom od AI
- Inne (jakie?)

*Cel:* H3. Wynik bezpośrednio priorytetyzuje funkcje budujące zaufanie (RAG z danymi czasu rzeczywistego, silnik budżetu czasowego).

**D6*. Czy udostępniasz aplikacjom lokalizację w telefonie?** (J)
Zawsze, gdy aplikacja prosi / Tylko podczas korzystania z aplikacji / Tylko wybranym aplikacjom / Nigdy
*Cel:* warunek techniczny działania „od drzwi do drzwi”. Pytanie dotyczy obecnej praktyki, nie deklaracji wobec naszej aplikacji.

### 2.7. Blok E – preferencje funkcji (kwestionariusz Kano)

Model Kano klasyfikuje cechy produktu według tego, jak ich obecność i brak wpływają na zadowolenie: cechy oczekiwane (must-be), jednowymiarowe (one-dimensional), atrakcyjne (attractive) i obojętne (indifferent) (Kano i in., 1984). Standardowy kwestionariusz zadaje o każdą cechę parę pytań: funkcjonalne („co czujesz, gdy cecha jest obecna?”) i dysfunkcjonalne („co czujesz, gdy jej nie ma?”), z pięcioma odpowiedziami. Odpowiedzi klasyfikuje się według tabeli oceny opisanej przez Bergera i współautorów ([Berger i in., 1993](https://www.walden-family.com/public/cqm-journal/2-4-Whole-Issue.pdf)).

**Wprowadzenie do bloku (do wklejenia):**
> Teraz opiszemy kilka funkcji, które mogłaby mieć aplikacja do planowania krótkich spacerów. Przy każdej odpowiedz na dwa pytania: co czujesz, gdy aplikacja ma tę funkcję, i co czujesz, gdy jej nie ma.

**Odpowiedzi do każdego pytania (J):**
1. Podoba mi się to
2. Oczekuję tego, to oczywiste
3. Jest mi to obojętne
4. Mogę się z tym pogodzić
5. Nie podoba mi się to

| Nr | Pytanie funkcjonalne (cecha obecna) | Pytanie dysfunkcjonalne (cecha nieobecna) | Luka / hipoteza |
|---|---|---|---|
| K1a | Aplikacja pilnuje podanego przez Ciebie czasu i gwarantuje, że zdążysz wrócić (np. na dworzec). | Aplikacja nie pilnuje czasu powrotu: sam(a) musisz sprawdzać, czy zdążysz. | 1 / H1 |
| K1b | Trasa zaczyna się dokładnie tam, gdzie jesteś. | Trasy zaczynają się w stałych miejscach i na start trzeba dojść samodzielnie. | 1 / H1 |
| K2 | Możesz opisać swoimi słowami, czego szukasz („mam godzinę, chcę ciszy i dobrej kawy”). | Aplikacja nie rozumie opisu słowami: możesz tylko wybierać z gotowych filtrów i kategorii. | – / D4 |
| K3 | Aplikacja sprawdza godziny otwarcia i pogodę w chwili planowania i pomija zamknięte miejsca. | Aplikacja nie sprawdza godzin otwarcia ani pogody. | 2 / H3 |
| K4 | Możesz włączyć tryb „anty-tłum”, który prowadzi cichszymi uliczkami. | Aplikacja nie ma trybu „anty-tłum”. | – / H5 |
| K5 | Przy każdym punkcie dostajesz krótką, trzyzdaniową wskazówkę, na co spojrzeć. | Przy punktach nie ma żadnego opisu. | – / persony |
| K6 | Trasa może zawierać oznaczoną ofertę lokalnego lokalu na Twojej drodze (np. „rogalik do kawy do 14:00”). | Trasa nigdy nie zawiera ofert lokali. | 4 / H6 |

Każda para dotyczy jednej funkcji, a pytanie dysfunkcjonalne opisuje brak tej samej funkcji, a nie inne rozwiązanie. Dlatego dawne K1 (start w miejscu użytkownika i gwarancja powrotu w jednym zdaniu) rozdzielono na K1a i K1b, a w K5 usunięto wariant „długie nagranie audio”.

**Tabela oceny (wiersz: odpowiedź funkcjonalna, kolumna: dysfunkcjonalna)** według Bergera i in. (1993):

| Funkcjonalne \ Dysfunkcjonalne | Podoba mi się | Oczekuję | Obojętne | Mogę się pogodzić | Nie podoba mi się |
|---|---|---|---|---|---|
| **Podoba mi się** | Q | A | A | A | O |
| **Oczekuję** | R | I | I | I | M |
| **Obojętne** | R | I | I | I | M |
| **Mogę się pogodzić** | R | I | I | I | M |
| **Nie podoba mi się** | R | R | R | R | Q |

A – atrakcyjna, O – jednowymiarowa, M – oczekiwana, I – obojętna, R – odwrotna (respondent woli brak cechy), Q – odpowiedź wątpliwa (sprzeczna, do odrzucenia).

Każdą cechę przypisuje się do kategorii wskazywanej najczęściej. Dodatkowo można policzyć współczynniki zadowolenia i niezadowolenia (Berger i in., 1993): *Better* = (A + O) / (A + O + M + I) oraz *Worse* = −(O + M) / (A + O + M + I), i przedstawić cechy na wykresie Better–Worse. Kategorie warto liczyć osobno dla każdej persony, bo np. K1a może być cechą oczekiwaną dla P1, a obojętną dla P2. Dla K6 szczególnie ważny jest odsetek odpowiedzi R: wysoki oznacza, że punkty sponsorowane aktywnie zniechęcają.

### 2.8. Blok F – gotowość do korzystania i płacenia

Deklaracje „skorzystałbym” i „zapłaciłbym” są systematycznie zawyżone. Metaanaliza 28 badań porównujących hipotetyczną i rzeczywistą gotowość do zapłaty wykazała medianę stosunku wartości hipotetycznej do rzeczywistej równą 1,35, a mechanizmy oparte na wyborze zmniejszały to zawyżenie ([Murphy i in., 2005](https://doi.org/10.1007/s10640-004-3332-z)). Dlatego blok F nie pyta „ile zapłacisz”, tylko o dotychczasowe wydatki (F2) i o wybór spośród modeli (F3). Wynik F1 należy traktować jako górną granicę zainteresowania, a nie prognozę.

**F1*. Gdyby aplikacja z opisanymi funkcjami była dostępna, jak prawdopodobne jest, że użyłbyś/użyłabyś jej przy najbliższej okazji, gdy będziesz mieć 1–2 godziny wolnego w mieście?** (L5)
Zdecydowanie nie / Raczej nie / Trudno powiedzieć / Raczej tak / Zdecydowanie tak
*Cel:* orientacyjny poziom zainteresowania per persona. Interpretować ostrożnie (zob. wyżej).

**F2*. Za które z poniższych zapłaciłeś/-aś w ciągu ostatnich 12 miesięcy?** (W)
- Płatna aplikacja z trasami lub audioprzewodnikiem
- Przewodnik książkowy lub e-book
- Wycieczka z przewodnikiem (także „free walking tour” z napiwkiem)
- Płatna subskrypcja czatu AI
- Żadne z powyższych

*Cel:* H7. Rzeczywiste wydatki są lepszym sygnałem gotowości do płacenia niż deklaracja.

**F3*. Który model takiej aplikacji wybrałbyś/wybrałabyś?** (J)
- Darmowa, z wyraźnie oznaczonymi ofertami lokalnych lokali
- Darmowa, z klasycznymi reklamami
- Jednorazowa opłata, bez ofert i reklam
- Miesięczna subskrypcja, bez ofert i reklam
- Nie korzystałbym/korzystałabym z żadnej wersji

*Cel:* H6, H7. Pytanie wyboru zamiast pytania o kwotę.

### 2.9. Blok G – akceptacja punktów sponsorowanych

**G1–G2. Na ile zgadzasz się z poniższymi zdaniami?** (macierz, skala SZ)
- **G1.** Przeszkadza mi punkt sponsorowany na trasie, nawet jeśli jest wyraźnie oznaczony jako sponsorowany. *(H6, transparentność; pytanie odwrócone)*
- **G2.** Nie przeszkadza mi punkt sponsorowany na trasie, jeśli pasuje do tego, o co prosiłem/-am (np. kawiarnia, gdy pytałem/-am o kawę). *(H6, trafność)*

Oznaczenie i trafność są celowo rozdzielone na dwa pytania, żeby uniknąć pytania dwulufowego. G1 jest sformułowane w przeciwnym kierunku niż G2, żeby ograniczyć bezrefleksyjne potakiwanie. Przy analizie skalę G1 odwracamy. Respondent, który zgadza się jednocześnie z G1 i G2, mógł odpowiadać bez czytania. Taką parę odpowiedzi warto sprawdzić przy czyszczeniu danych.

**G3. Czy w ciągu ostatnich 3 miesięcy skorzystałeś/-aś z oferty lub rabatu lokalu, o którym dowiedziałeś/-aś się z aplikacji lub mediów społecznościowych?** (J)
Tak / Nie / Nie pamiętam
*Cel:* H6, faktyczne zachowanie wobec ofert lokalnych.

**G4*. Wyobraź sobie, że dowiadujesz się, iż miejsce polecone przez aplikację zapłaciło za to, a nie było to oznaczone. Jak by to wpłynęło na Twoje zaufanie do aplikacji?** (J)
Bardzo by je obniżyło / Trochę by je obniżyło / Bez wpływu, jeśli miejsce było dobre / Nie wiem
*Cel:* H6, koszt braku transparentności. G4 jest świadomym wyjątkiem od zasady pytania o przeszłość (punkt 2.1), bo nie da się zapytać o doświadczenie, którego respondent zwykle nie zauważa. Wynik traktujemy jako deklarację i zestawiamy z G1, G2 oraz z odsetkiem odpowiedzi R dla K6.

**G5. Ile oznaczonych punktów sponsorowanych na jednej trasie (1–2 h) uznałbyś/uznałabyś za akceptowalne?** (J)
Żadnego / 1 / 2 / 3 lub więcej
*Cel:* górny limit sponsorowanych pinów w algorytmie. Opcjonalne do cięcia.

### 2.10. Szacunek czasu i pułapki

Ankieta ma 6 pytań metryczkowych, 5 o zachowaniach (każdy respondent widzi B4 albo B4a), 10 o problemach (w tym macierz 7 wierszy i filtr C8a), 6 o AI, 14 odpowiedzi Kano, 3 o gotowości, 5 o punktach sponsorowanych. Pytania zamknięte w macierzy wypełnia się szybko, a najwięcej czasu zajmują pytania otwarte i blok Kano. Wstępnie szacujemy 9–12 minut, ale jedyną wiarygodną miarą jest pomiar w pilotażu (punkt 3.3). Jeśli przekroczy 12 minut, w pierwszej kolejności wycinamy pytania oznaczone jako opcjonalne (A5, G5, a w ostateczności B5).

Najważniejsze pułapki, na które ankieta jest przygotowana:

1. **Pytania sugerujące.** Pytanie „Czy nie denerwuje Cię, że Google Maps wymaga tyle pracy?” podpowiada odpowiedź. Zamiast tego pytamy o częstość konkretnej sytuacji (C3) i o czas planowania (B3).
2. **Pytania dwulufowe.** Każde pytanie dotyczy jednej rzeczy (C1–C7, G1–G2, pary Kano K1a–K6).
3. **Zawyżona deklarowana gotowość do korzystania i płacenia.** Pytamy o przeszłe wydatki i każemy wybierać między modelami, a F1 interpretujemy jako górną granicę (Murphy i in., 2005).
4. **Efekt ujawnienia pomysłu.** Aplikację opisujemy dopiero w bloku E, po pytaniach o zachowania i problemy.
5. **Efekt zapytania.** Ludzie tworzą opinię na każdy temat, o który się ich zapyta (Nielsen, 2010). Wyniki dotyczące funkcji (blok E) zestawiamy z odpowiedziami o faktycznych zachowaniach (bloki B i C). Funkcję uznajemy za ważną dopiero wtedy, gdy wskazują na nią oba źródła. Docelowo warto je potwierdzić w testach prototypu, które są poza zakresem tego badania.
6. **Pamięć.** Okno 12 miesięcy dla rzadkich zdarzeń i 3 miesięcy dla częstych to kompromis. Odpowiedzi „Nie pamiętam” są dostępne, żeby nie zmuszać do zgadywania.

---

## 3. Plan realizacji

Na badanie mamy najwyżej dwa tygodnie, dlatego ograniczamy się do jednej ankiety dla spacerowiczów. Nie prowadzimy wywiadów, obserwacji w terenie ani badania lokalnych biznesów. Pytania otwarte w ankiecie (B5, C9) częściowo zastępują wywiady, bo zbierają problemy spoza naszej listy.

### 3.1. Dobór próby i kanały rekrutacji

Próba będzie **nieprobabilistyczna** (dobór dostępnościowy i kula śnieżna). Kanały:

- **Uczelnia:** grupy roczników i kół naukowych PŁ, Uniwersytetu Łódzkiego i innych uczelni, w tym studenci dojeżdżający (naturalni kandydaci do P1).
- **Grupy na Facebooku i Reddit:** grupy miejskie (np. łódzkie grupy mieszkańców), grupy podróżnicze i wymiany polecanych miejsc (P2, P3). Przed publikacją trzeba sprawdzić regulamin grupy i poprosić administratora o zgodę.
- **Dworce i węzły przesiadkowe (opcjonalnie):** kod QR na kartce przy poczekalniach (np. Łódź Fabryczna, Łódź Kaliska). Najbliżej P1, ale wymaga zgody zarządcy obiektu, więc warto o nią wystąpić od razu pierwszego dnia.
- **Sieci kontaktów zespołu:** udostępnianie dalej (kula śnieżna), z prośbą o przekazanie osobom spoza uczelni, żeby zmniejszyć nadreprezentację studentów.

### 3.2. Narzędzie

| Narzędzie | Zalety | Wady |
|---|---|---|
| **Google Forms** | Darmowe, znane, logika przejść między sekcjami, eksport do Arkuszy | Brak limitu „maksymalnie 3” w pytaniach wielokrotnego wyboru bez obejścia (walidacja odpowiedzi), dane na serwerach Google |
| **Microsoft Forms** | Dostępne w ramach konta uczelnianego M365, logika rozgałęzień, dane w środowisku uczelni | Mniej elastyczne macierze |

Rekomendacja: **Microsoft Forms z konta uczelnianego** (dane zostają w środowisku uczelni, co upraszcza kwestie RODO) albo Google Forms, jeśli zespół woli to narzędzie. W obu przypadkach trzeba **wyłączyć zbieranie adresów e-mail i logowanie**.

### 3.3. Pilotaż

Przed publikacją ankietę wypełnia 3–5 osób z grupy docelowej (spoza zespołu). Zespół mierzy czas wypełniania, a po wypełnieniu prosi o powiedzenie własnymi słowami, jak rozumieją pytania C1–C7 i pary Kano oraz czy jakiejś odpowiedzi brakowało. Sprawdza też poprawność logiki przejść (A1, A2, B1, C8a, D1) i eksport danych. Pilotaż mieści się w jednym dniu. Odpowiedzi z pilotażu nie wchodzą do analizy końcowej.

### 3.4. Liczebność próby i jej ograniczenia

Ponieważ próba jest nieprobabilistyczna, **nie można obliczyć błędu statystycznego ani uogólniać wyników na populację** („X% Polaków…”). Wzory na wielkość próby dla zadanego marginesu błędu zakładają losowy dobór i tutaj nie mają zastosowania. Wyniki opisują wyłącznie osoby, które odpowiedziały, i służą do porównania person oraz wskazania kierunków, a nie do szacowania rynku.

Cel praktyczny: **około 100 pełnych odpowiedzi i, jeśli się uda, około 30 na każdą z trzech person.** To robocza reguła zespołu, a nie wymóg statystyczny wynikający z cytowanej literatury. Chodzi o to, żeby odsetki w tabelach krzyżowych nie opierały się na pojedynczych osobach. Jeśli któraś persona będzie miała mniej niż około 20 odpowiedzi, jej wyniki opisujemy liczbami bezwzględnymi i traktujemy jako wskazówkę, a nie wniosek.

Spodziewane zniekształcenia, które trzeba opisać w raporcie:
- **Nadreprezentacja studentów i osób młodych** (kanały uczelniane).
- **Samoselekcja:** ankietę chętniej wypełnią osoby zainteresowane spacerami i technologią, więc zainteresowanie aplikacją (F1) będzie prawdopodobnie zawyżone.
- **Jedno miasto:** większość odpowiedzi będzie z Łodzi, a wyniki mogą się różnić w miastach bardziej turystycznych.
- **Sezon:** przy zbieraniu odpowiedzi jesienią pytania o ostatnie 3 miesiące (A4, G3) obejmą późne lato i jesień, a pogoda wpływa na częstość spacerów. W raporcie podajemy daty zbierania odpowiedzi.
- **Krótki czas zbierania:** dwa tygodnie mogą nie wystarczyć, żeby każda persona miała około 30 odpowiedzi. Strukturę próby sprawdzamy w połowie zbierania i w razie potrzeby dosyłamy ankietę do kanałów, w których brakuje danej persony.

### 3.5. Analiza danych

1. **Czyszczenie:** usunięcie odpowiedzi niepełnych, osób poniżej 18 lat i odpowiedzi „na jedno kliknięcie” (np. ta sama odpowiedź we wszystkich wierszach macierzy przy bardzo krótkim czasie, jeśli narzędzie go rejestruje, albo zgoda jednocześnie z G1 i G2).
2. **Statystyki opisowe:** liczebności i odsetki dla pytań zamkniętych. Dla skal pięciopunktowych: rozkład odpowiedzi i mediana, a średnią podajemy tylko pomocniczo, bo skala jest porządkowa.
3. **Tabele krzyżowe per persona (A3)** dla kluczowych pytań: B1, B3, B4a, C1–C7, D2–D5, F1, F3, G1–G4. To główny wynik badania: czy problemy i postawy różnią się między personami zgodnie z założeniami.
4. **Analiza Kano** według tabeli z punktu 2.7, osobno dla całej próby i dla każdej persony, z wykresem Better–Worse.
5. **Testy statystyczne (np. chi-kwadrat)** można policzyć pomocniczo dla różnic między personami, ale przy próbie nieprobabilistycznej wynik testu nie uprawnia do wniosków o populacji. Należy go opisać jako różnicę zaobserwowaną w próbie.
6. **Pytania otwarte (B5, C9):** jedna osoba z zespołu grupuje odpowiedzi w tematy, a druga sprawdza to grupowanie (uproszczona analiza tematyczna, Braun i Clarke, 2006). Tematy, których nie ma na liście luk 1–5, trafiają do listy wymagań do rozważenia.
7. **Weryfikacja hipotez:** dla każdej hipotezy H1–H7 krótka ocena (wspiera / częściowo wspiera / nie wspiera) z odwołaniem do konkretnych pytań. Kryteria oceny zespół zapisuje **przed publikacją ankiety** (dzień 1–2), żeby nie dopasować interpretacji do wyniku. Progi oznaczone [__] zespół ustala sam. Nie wynikają z literatury.

| Hipoteza | Wspiera, gdy… | Nie wspiera, gdy… |
|---|---|---|
| H1 | co najmniej [__]% osób z P1 odpowiada w C1 lub C2 „Kilka razy” lub częściej, a K1a jest dla P1 cechą M lub O | poniżej [__]% osób z P1 odpowiada tak w C1 i C2, a K1a jest dla P1 cechą I |
| H2 | co najmniej [__]% osób z P1 i P2 planowało dłużej niż 5 minut (B3), a C3 lub C4 ma „Kilka razy” lub częściej u [__]% | większość nie planuje albo planuje krócej niż 5 minut, a C3 i C4 są rzadkie |
| H3 | co najmniej [__]% osób z C8a = „Tak” wskazuje w C8 co najmniej jeden błąd, a D3 ma zgodę u [__]% | większość nie zauważa błędów w C8, a D2 ma wysoką zgodę przy niskiej D3 |
| H4 | co najmniej [__]% osób z P3 wskazuje w B2 fora lub blogi, a C6 jest u nich „Kilka razy” lub częściej | C6 jest rzadkie także u P3 |
| H5 | w B4 u P2 i P3 cisza, zieleń lub mniej znane miejsca są wybierane częściej niż znane atrakcje | znane atrakcje dominują w B4, a K4 jest cechą I |
| H6 | G1 (po odwróceniu skali) i G2 mają zgodę u [__]%, odsetek R dla K6 jest poniżej [__]%, a G4 „Bardzo by je obniżyło” u [__]% | odsetek R dla K6 przekracza [__]% albo G1 i G2 mają przewagę niezgody |
| H7 | co najmniej [__]% zaznacza w F2 „Żadne z powyższych”, a w F3 wersje płatne wybiera mniej niż [__]% | wersje płatne w F3 wybiera co najmniej [__]% |

Wynik pomiędzy kolumnami oznacza „częściowo wspiera”.

Do analizy wystarczy arkusz kalkulacyjny (tabele przestawne). Jeśli ktoś z zespołu zna Pythona (pandas) lub R, warto go użyć do tabel krzyżowych i Kano, żeby analizę dało się powtórzyć.

### 3.6. RODO i etyka

- **Ankieta bez danych osobowych.** RODO nie ma zastosowania do informacji anonimowych, czyli takich, które nie pozwalają zidentyfikować osoby (motyw 26 RODO, [Rozporządzenie (UE) 2016/679](https://eur-lex.europa.eu/legal-content/PL/TXT/?uri=CELEX:32016R0679)). Dlatego w ankiecie nie zbieramy e-maili, imion ani dokładnych lokalizacji, wyłączamy logowanie i rejestrację adresów e-mail w narzędziu, a wiek i wielkość miasta zbieramy w przedziałach. Trzeba pamiętać, że kombinacja kilku szczegółowych odpowiedzi w małej grupie może pozwolić kogoś rozpoznać, więc wyniki raportujemy zbiorczo.
- **Pytania otwarte.** We wprowadzeniu do B5 i C9 prosimy, żeby nie podawać imion, adresów ani innych danych pozwalających kogoś rozpoznać. Odpowiedzi, które je zawierają, anonimizujemy przed analizą.
- **Uczelnia.** Przed startem warto zapytać prowadzącego, czy PŁ wymaga zgłoszenia anonimowej ankiety do komisji etycznej lub inspektora ochrony danych. Nie sprawdziliśmy wewnętrznych przepisów PŁ w tym zakresie.

Powyższe punkty nie są poradą prawną, tylko podsumowaniem przepisów, które trzeba uwzględnić.

### 3.7. Harmonogram (2 tygodnie)

| Termin | Działania | Wynik |
|---|---|---|
| Dzień 1–2 | Przeniesienie ankiety do Microsoft Forms, spisanie kryteriów oceny H1–H7 (punkt 3.5), pilotaż na 3–5 osobach, poprawki, prośby o zgodę do administratorów grup | Ostateczna wersja ankiety, zapisane kryteria |
| Dzień 3–10 | Zbieranie odpowiedzi (kanały z 3.1); w połowie sprawdzenie liczby odpowiedzi per persona i dosyłanie ankiety tam, gdzie brakuje | Około 100 pełnych odpowiedzi |
| Dzień 11–14 | Czyszczenie danych, tabele krzyżowe, analiza Kano, grupowanie odpowiedzi otwartych, ocena H1–H7 | Raport z badania i lista funkcji pierwszej wersji aplikacji |

Wywiady, badanie lokalnych biznesów i testy użyteczności prototypu są poza zakresem tego badania. Jeśli projekt będzie kontynuowany, warto do nich wrócić na późniejszym etapie.

---

## 4. Źródła

**Metodologia ankiet i skal**
- Likert, R. (1932). A technique for the measurement of attitudes. *Archives of Psychology*, 22(140), 1–55.
- Murphy, J. J., Allen, P. G., Stevens, T. H., Weatherhead, D. (2005). A meta-analysis of hypothetical bias in stated preference valuation. *Environmental and Resource Economics*, 30(3), 313–325. https://doi.org/10.1007/s10640-004-3332-z
- Nielsen, J. (2010). Interviewing users. Nielsen Norman Group. https://www.nngroup.com/articles/interviewing-users/
- Fitzpatrick, R. (2013). *The Mom Test: How to talk to customers and learn if your business is a good idea when everyone is lying to you*. https://www.momtestbook.com/

**Model Kano**
- Kano, N., Seraku, N., Takahashi, F., Tsuji, S. (1984). Attractive quality and must-be quality. *Hinshitsu (Journal of the Japanese Society for Quality Control)*, 14(2), 39–48.
- Berger, C., Blauth, R., Boger, D., Bolster, C., Burchill, G., DuMouchel, W., Pouliot, F., Richter, R., Rubinoff, A., Shen, D., Timko, M., Walden, D. (1993). Kano's methods for understanding customer-defined quality. *Center for Quality of Management Journal*, 2(4), 3–36. https://www.walden-family.com/public/cqm-journal/2-4-Whole-Issue.pdf

**Akceptacja technologii**
- Davis, F. D. (1989). Perceived usefulness, perceived ease of use, and user acceptance of information technology. *MIS Quarterly*, 13(3), 319–340. https://doi.org/10.2307/249008

**Analiza odpowiedzi otwartych**
- Braun, V., Clarke, V. (2006). Using thematic analysis in psychology. *Qualitative Research in Psychology*, 3(2), 77–101. https://doi.org/10.1191/1478088706qp063oa

**Prawo**
- Rozporządzenie Parlamentu Europejskiego i Rady (UE) 2016/679 z dnia 27 kwietnia 2016 r. (RODO), w szczególności motyw 26. https://eur-lex.europa.eu/legal-content/PL/TXT/?uri=CELEX:32016R0679

### Uwagi o weryfikacji źródeł

- Treść artykułu Nielsen (2010) sprawdzono bezpośrednio na stronie nngroup.com.
- Dane bibliograficzne i główne wnioski Braun i Clarke (2006), Davis (1989), Murphy i in. (2005), Kano i in. (1984), Berger i in. (1993) oraz Likert (1932) potwierdzono w wynikach wyszukiwania i opisach repozytoriów, bez lektury pełnych tekstów. Numery DOI podano na podstawie wiedzy zespołu i warto je kliknąć przed oddaniem pracy.
- Tabelę oceny Kano i wzory Better–Worse przytoczono w standardowej postaci przypisywanej Bergerowi i in. (1993). Ich treści nie porównano z oryginalnym PDF strona po stronie.
- Zasady „The Mom Test” potwierdzono w omówieniach książki, nie w samej książce. Rok wydania (2013) i adres strony warto sprawdzić.
- Dla Likerta (1932) i Kano i in. (1984) nie podano linków, bo nie znaleziono stabilnego adresu u wydawcy.
- Nie zweryfikowano wewnętrznych procedur etycznych Politechniki Łódzkiej.
- Próg około 100 odpowiedzi i około 30 na personę to robocza reguła zespołu, a nie wartość wzięta z cytowanej literatury.
