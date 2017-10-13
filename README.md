# O LaTeXu słów kilka

Materiały do wstępnych zajęć z LaTeXa, które od 3 lat prowadzę na letnich obozach naukowych [Klubu Astronomicznego Almukantarat](http://almukantarat.pl) dla licealistów. Zajęcia przewidziane są na 3 godziny (2 części po 1.5 godziny) i w tym czasie, w zależności od wielkości grupy, zwykle daje się pokryć opisany tu materiał. 

## Zawartość repozytorium
Plik `sciaga.pdf` (i jego wersja źródłowa `sciaga.tex`) z grubsza pokrywają się z treścią wywodu osoby prowadzącej zajęcia, plik `pliczek.tex` jest zestawem ćwiczeń, przeznaczonym do modyfikowania przez uczestnika. 
Wszystkie te pliki uczestnicy powinni mieć te pliki na swoich komputerach już od początku zajęć. Oprócz tego bardzo polecam dostarczenie im pliku `sciaga.pdf` w wersji wydrukowanej. 

## Wymagania
### Uczestnicy
Do udziału w zajęciach nie jest wymagana żadna wstępna wiedza ani doświadczenie w programowaniu. Nie polecam jednak (z doświadczenia) przeprowadzać tych zajęć dla uczestników młodszych niż licealiści — nawet absolwenci gimnazjum nie są nimi zbyt zainteresowani, bo nie widzą zastosowania TeXa w ich życiu. 

Wielkość grupy — maksymalnie ok. 10 osób. Im mniej, tym lepiej ;)

### Sprzęt
Komputery z zainstalowanym LaTeXem, minimum jeden na dwoje uczestników. Idealnie także rzutnik. 

### Oprogramowanie
Na obozach uczestnicy mają do dyspozycji komputery z linuksem (ubuntu) i zainstalowanymi pakietami: 
``texlive, texlive-latex-extra, texlive-lang-polish, texlive-math-extra,
texlive-metapost, latex-beamer, texmaker``. 
Oczywiście LaTeXa można zainstalować także na Windowsie. Jeśli zajęcia mają się odbywać w miejscu z utrudnionym dostępem do internetu (np. w lesie :P), warto pamiętać, że `MiKTeX` pobiera pakiety dopiero przy ich pierwszym użyciu i już wcześniej zaopatrzyć się w ich bezpieczny zestaw (np. ``parskip, latexsym, gensymb, amsmath, amssymb, amsthm, graphicx, pifont, geometry, bbm,beamer, textcomp, xcolor, indentfirst, multicol, multirow, mathcomp, float, fancyhdr, hyperref``).

Polecam prowadzić zajęcia na edytorze `TeXMaker` (dostępnym na wszystkie platformy), bo ułatwia on łagodne przejście z edytorów typu WISYWYG (sporo da się _wyklikać_), podpowiada komendy, ma wbudowany kompilator z podglądem. 

## Filozofia
### Forma zajęć
Forma zajęć jest próbą odpowiedzi na niską jakość zajęć _przy komputerach_, z jaką zazwyczaj się spotykam. 
Najczęstsze strategie prowadzących, z jakimi się spotkałam, wyglądają następująco:
- _spróbujcie napisać program, który robi X_ (efekt: najbystrzejsza osoba w grupie coś robi, reszta gapi się tępo w ekrany),
- _napiszę wam teraz na tablicy program, a wy go przepiszcie, uruchomcie i zobaczcie, jak działa_ (efekt: wszyscy przepisują kod bez zrozumienia, większość popełnia przy tym jakiś błąd i przez resztę zajęć prowadzący biega między uczestnikami, żeby każdemu pokazać, gdzie zrobił literówkę).

Nie ma tu oczywiście rozwiązań uniwersalnych, można wprowadzić kilka ulepszeń:
- _pisanie kodu na komputerze podłączonym do rzutnika_ (eliminuje problemy związane z nieczytelnością pisma odręcznego)
- _zwiększenie liczby prowadzących_ (większa liczba prowadzących może pomóc jednocześnie większej liczbie uczestników, wprowadza to niestety rozgardiasz)
- _przygotowanie dla uczestników pliku (szablonu), który będą modyfikować_ (oszczędza czas potrzebny na przepisanie mniej istotnych partii kodu, zmniejsza ilość kodu, którą uczestnicy muszą sami napisać (co w przypadku zajęć z _podstaw_ jest dla nich często trudne), a jednocześnie wymusza pewną samodzielność).

Ostatnia metoda została zastosowana podczas prowadzenia tych zajęć. Przygotowany plik (`pliczek.tex`) jest gotowym, kompilującym się dokumentem, w którym uczestnicy dokonują tylko drobnych modyfikacji, poprawek, zmieniają formatowanie itp. Takie ćwiczenia są bardzo proste, ale wymagają zrobienia czegoś _samemu_, a to jest chyba najważniejsze. 


### Cel
Mimo że jestem wielką fanką LaTeXa, celem tych zajęć _nie jest_ przekonanie uczestników o wyższości tej technologii nad innymi. Zajęcia mają na celu obniżenie nieco _bariery potencjału_, jaką trzeba pokonać, zaczynając pisać w LaTeXu (która to bariera jest sporo wyższa niż w przypadku edytorów typu WISYWYG, zwłaszcza dla użytkowników niemających doświadczenia w programowianiu), zachęcenie ich do własnych prób składania dokumentów w LaTeXu (gdyż, jako przyszłych studentów kierunków ścisłych, może im się to zwyczajnie przydać), ale także (a może: _przede wszystkim_) zwrócenie uwagi na ogólne zasady typografii i zalety stosowania _formatowania logicznego_, niezależnie od używanej technologii. 


## TODO
- dodanie do ściągi sekcji dotyczącej typografii
- rozszerzenie zajęć o część trzecią — tworzenie prezentacji w klasie `beamer`
