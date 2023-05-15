# Wstęp

## 1. Szczegółowe informacje o produkcie
* Nazwa: Frezarka CNCFrog 2639/3144/3649/4055
* Kompatybilne urządzenia (opcjonalnie): PROXXON IBS/E, Dremel 3000/4000
* Producent: Karambola, Zacisze 112, 32-650 Kęty Polska
* Kontakt: telefon +48662772277, e-mail: ​info@cncfrog.pl
* Grupa EEE: 3 (sprzęt IT i/lub telekomunikacyjny), 
* Użycie urządzenia: tylko wewnątrz
* Zasilanie: 85-264 VAC, 3,6 A / 120-370 VAC, 1,8 A (50-60 Hz)
* Zakres temperatury pracy: 18 ° C—38 ° C, tylko do użytku w pomieszczeniach
* Wilgotność podczas pracy: 85% lub mniej
* Waga zestawu do samodzielnego złożenia (brutto / netto): 9,8 kg / 6,3 kg, 
* Waga zmontowanej frezarki (brutto / netto): 12 kg / 6,3 kg. 
* Numer seryjny znajduje się na ramie frezarki.

<figure markdown>
![Nie wyrzucaj](/MkDocsTest/resources/WEEE_symbol_vectors.svg){ width="100", align=left }
![Znak CE](/MkDocsTest/resources/CEmarking.svg){ width="200", align=right }
</figure>

## 2. Wyłączenie odpowiedzialności

!!! Danger "Przeczytaj instrukcję!"
    Nie przeczytanie instrukcji może spowodować obrażeniami ciała, utratę jakości podczas frezowania lub uszkodzenie frezarki. Zawsze upewnij się, że __każdy, kto obsługuje frezarkę, zna i rozumie obsługę frezarki.__ Nie możemy kontrolować warunków, w których montujesz frezarkę.  Dlatego zachowaj najwyższą staranność i dokładność podczas montażu.

__Z tego i innych powodów zaznaczamy wyraźnie, że nie ponosimy odpowiedzialności i nie uznajemy roszczeń za straty, obrażenia, szkody lub wydatki wynikające z lub w jakikolwiek sposób związane z montażem, obsługą, przechowywaniem, użytkowaniem  lub zbyciem produktu oraz użytkowaniem jej nie zgodnie z przeznaczeniem.__ Informacje zawarte w niniejszej instrukcji są dostarczane bez jakiejkolwiek gwarancji, wyraźnej lub dorozumianej, dotyczącej jej poprawności.

## 3. Instrukcja bezpieczeństwa

!!! Danger "Uwaga!"
    ![Uwaga](/MkDocsTest/resources/warningOutline.svg){ width="120", align=right }
    <font size=5 color=red> Zachowaj szczególną ostrożność podczas pracy z frezarkę. Frezarka jest urządzeniem elektrycznym z ruchomymi częściami.</font>

1. Urządzenie jest przeznaczone wyłącznie do użytku w pomieszczeniach. Nie wystawiaj frezarki na działanie warunków atmosferycznych takich jak deszcz czy śnieg. Zawsze przechowuj frezarkę w suchym otoczeniu, w odległości co najmniej 30 cm od innych przedmiotów.
2. Zawsze umieszczaj frezarkę na stabilnym podłożu, aby zapobiec jej upadkowi lub przewróceniu się.
3. Zasilanie frezarki to domowe gniazdko 230 VAC, 50 Hz lub 110 VAC / 60 Hz; nigdy nie podłączaj frezarki do innego źródła zasilania, ponieważ może to spowodować nieprawidłowe działanie lub uszkodzenie frezarki.
4. Przewód zasilający umieść tak, aby nie potknąć się o niego, nie nadepnąć i nie narazić na żadne inne uszkodzenia. Upewnij się, że przewód zasilający nie jest uszkodzony mechanicznie ani w żaden inny sposób. W razie uszkodzenia kabla natychmiast go wymień!
5. Przy odłączaniu przewodu zasilającego od gniazdka należy ciągnąć za wtyczkę, a nie za przewód. Zmniejszy to ryzyko uszkodzenia wtyczki lub gniazdka sieciowego.
6. Nigdy nie należy demontować zasilacza frezarki, nie zawiera on żadnych części, które mogłyby zostać naprawione przez niewykwalifikowanego pracownika. Wszelkie naprawy muszą być wykonywane przez wykwalifikowanego technika.
7. Nie dotykaj frezu kiedy frezarka pracuje. Należy pamiętać, że ruchome części mogą spowodować skaleczenie.
8. __Nigdy nie zostawiaj osoby niepełnoletniej w pobliżu urządzenia bez nadzoru, nawet gdy frezarka nie pracuje. Osoby niepełnoletnie mogą pracować tylko pod nadzorem osób pełnoletnich!__
9. __Nie pozostawiaj frezarki bez nadzoru gdy jest włączona!__
10. Podczas frezowania powstają wióry i pyły, dlatego zadbaj o czystość otoczenia frezarki i stosuj do usuwania zanieczyszczeń odkurzacz, tak by zminimalizować osiadanie nieczystości na elementach ruchomych frezarki co może spowodować jej uszkodzenia.

## 4. Kompatybilne urządzenia wielofunkcyjne z frezarką CNCFrog

Frezarka CNCFrog jest kompatybilna z następującymi urządzeniami:

* Wiertarko-frezarka Proxxon IBS/E
* Wiertarko-frezarka Proxxon IBS/A
* Narzędzie wielofunkcyjne DREMEL® 3000 (3000-15)
* Narzędzie wielofunkcyjne DREMEL® 4000
* Wrzeciono chłodzone powietrzem o maksymalnej mocy 500w i średnicy uchwytu 52mm 
* Parametry możliwych do zastosowania frezów, kamieni szlifierskich, wierteł, etc znajdziesz w instrukcji obsługi narzędzia wielofunkcyjnego.

## 5. Zastosowanie frezarki CNCFrog

CNCFrog pomoże ci stworzyć realny detal na podstawie modelu komputerowego. Zastosowanie odpowiedniego programu do rysowania np. oprogramowania open source Inkscape lub oprogramowania CAD (AutoCAD, Inventor, Fusion 360 itd.) umożliwi stworzenie modelu, a za pomocą oprogramowania  CNCJS [(https://cnc.js.org)](https://cnc.js.org) wysłanie go do frezarki, której firmware GRBL wyfrezuje gotowy element na podstawie GCODE.

Za pomocą CNCFrog możesz dokładnie i wydajnie wytwarzać modele tak często, jak tylko tego potrzebujesz. Materiały obrabianych przedmiotów są praktycznie nieograniczone: korzystając z CNCFrog i opcjonalnych akcesoriów możesz obrabiać takie materiały jak drewno, tworzywa termoplastyczne (PS (polistyren, takich jak styropianu®, EPS, Depron®, Selitron®), ABS, PE (polietylen), PP (polipropylen np PPE) miękki / twardy PVC, Lexan®, poliamid, plexi®), niektóre elastomery / termoutwardzalne, materiały mieszane, takie jak DIBOND aż po carbon i metale nieżelazne (aluminium, mosiądzu lub miedź). Każdy z tych materiałów może być obrabiany przy zastosowaniu odpowiednich frezów.

## 6. Montaż frezarki zestaw do samodzielnego montażu (DIY) 

CNCFrog jest dostarczany jako zestaw części do samodzielnego montażu, który zmontujesz w kilka godzin według dostarczonej instrukcji składania. Instrukcja jest tak przygotowana by nie było większego problemu z montażem. Poprowadzi cię krok po kroku i pokaże jak należy połączyć ze sobą poszczególne części. Użyjesz przy tym kilka podstawowych narzędzi. Maszyna dostarczana jest z całym potrzebnym oprzyrządowaniem: wszystkie niezbędne elementy mechaniczne i elektroniczne, wszystkie zasilacze i kable są dołączone do zestawu.

Montaż frezarki przeprowadź kierując się instrukcją montażu dostępną pod adresem [http://cncfrog.pl/](http://cncfrog.pl/) lub w dalszej części tej instrukcji.

## 7. Konfiguracja przed uruchomieniem i frezowaniem 

* Ustaw frezarkę na stabilnym, poziomym podłożu. Najlepszym miejscem jest stół warsztatowy, który się nie ugina.
* Sprawdź czy frezarka jest oddalona od innych urządzeń o co najmniej 30 cm z każdej strony
* Sprawdź czy oś X jest prostopadle ustawiona w stosunku do osi Y
* Sprawdź czy wyłącznik bezpieczeństwa (czerwony grzybek) jest w pozycji ON
* Zamontuj wrzeciono w uchwyt i dokręć śruby mocujące tak by wrzeciono było stabilnie zamocowane w uchwycie.
* Podłącz wrzeciono do gniazda zasilającego po prawej stronie obok przycisku bezpieczeństwa.
* Podłącz przewód zasilania prądem zmiennym, sprawdź, czy wybrano prawidłowe ustawienie napięcia AC (110 V / 220 V) i włącz przełącznik na obudowie elektroniki

## 8. Obsługa offline i oprogramowanie do obsługi frezarki 

Frezarka CNCFrog posiada na wyposażeniu kontroler z ekranem LCD, który umożliwia sterowanie osiami frezarki oraz uruchomienie z karty Micro SD pliku gcode. Na karcie znajduje się plik testowy, gotowy gcode, który możesz uruchomić i przetestować działanie frezarki. 

Oczywiście jest możliwość także sterowania frezarką po podłączeniu jej kablem USB do komputera. Firmware zastosowany w elektronice CNCFrog to popularny GRBL [(https://github.com/grbl/grbl)](https://github.com/grbl/grbl), który daje wiele możliwości i jest w pełni Open Source. 

Do kontrolowania CNCFrog zalecamy użycie programu CNCJS [(https://cnc.js.org/)](https://cnc.js.org/) w pełni darmowy, a przy tym jest bardzo zaawansowanym oraz dość intuicyjnym kontrolerem. 

<figure markdown>
![cnc.js](/MkDocsTest/resources/cncjs.webp)
<figcaption>cnc.js</figcaption>
</figure>

## 9. Warunki gwarancji

1. Udziela się gwarancji na prawidłowe funkcjonowanie fabrycznie nowego urządzenia na okres 24 miesięcy (12 miesięcy dla firm) na terenie EU.

2. Data, od której obowiązuje gwarancja, jest datą wystawienia dokumentu sprzedaży, paragonu lub faktury VAT.

3. Wady ujawnione w okresie gwarancji będą bezpłatnie usuwane, w terminie 14 dni roboczych od daty dostarczenia urządzenia pod adres firmy sprzedającej

4. W celu dokonania naprawy gwarancyjnej należy dostarczyć produkt do punktu sprzedaży. Po wykonaniu naprawy produkt zostanie wysłany reklamującemu na koszt gwaranta.

5. Reklamujący powinien dostarczyć urządzenie odpowiednio zabezpieczone przed uszkodzeniem w czasie transportu.

6. Reklamujący odpowiada za zaginięcie urządzenia w czasie dostarczania, gwarant zobowiązuje się dostarczyć naprawione urządzenie do reklamującego i odpowiada za zaginięcie urządzenia w czasie transportu.

7. W okresie gwarancyjnym wadliwy sprzęt zostanie bezpłatnie naprawiony, lub wymieniony przez gwaranta na taki sam, wolny od wad. W przypadku gdy naprawa. bądź wymiana urządzenia na nowe jest niemożliwa, reklamującemu przysługuje prawo do zwrotu zapłaconej kwoty, lub wyboru innego sprzętu o podobnych walorach i specyfikacji. Ewentualna różnica pieniężna zostanie uregulowana przez gwaranta, bądź przez reklamującego, w zależności od kosztu wybranego przez reklamującego przedmiotu.

8. Niniejsza gwarancja obejmuje usterki sprzętu wynikłe w trakcie poprawnej eksploatacji lub spowodowane defektami produkcyjnymi i nie stosuje się do materiałów eksploatacyjnych lub innego wyposażenia dodatkowego.

9. Gwarancja nie obejmuje wad wynikłych na skutek:

    * Samowolnych, dokonanych przez użytkownika lub inne nieupoważnione osoby napraw, przeróbek lub zmian konstrukcyjnych.
    * Uszkodzeń mechanicznych, termicznych, chemicznych lub celowego uszkodzenia sprzętu.
    * Przechowywania i konserwacji urządzenia oraz innych uszkodzeń powstałych z winy użytkownika.
    * Obniżenie się jakości produktu spowodowane naturalnym procesem zużycia np. ścierania się zewnętrznej powłoki produktu, zarysowanie, pęknięcie itp.
    * Uszkodzeń powstałych w wyniku nieprzestrzegania zasad prawidłowej eksploatacji, a także użytkowania sprzętu niezgodnie z jego przeznaczeniem.

10. Gwarancja na zestawy DIY (do samodzielnego montażu) obejmuje poszczególne części, a nie całe urządzenie.
11. Gwarancja __nie wyłącza, nie ogranicza ani nie zawiesza__ uprawnień kupującego wynikających z przepisów o rękojmi za wady rzeczy sprzedanej.
