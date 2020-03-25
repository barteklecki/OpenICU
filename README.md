> OPENICU.org
> autor: Bartek Ł.

> W kilku zdaniach / Abstrakt

Sytuacja ostatnich miesięcy i pandemii COVID-19 pokazała jak wielkim zagrożeniem może być niewystarczająca ilość zasobów medycznych w tym sprzętu ratującego życie. W sytuacji triażu (wiki https://pl.wikipedia.org/wiki/Tria%C5%BC) lekaże muszą codziennie podejmować skrajnie trudne decyzje. Proponujemy rozwiązanie Open Source / Open Hardawe do zastosowań ratujących życie (do zastosowań TYLKO przy braku innych środków) zawierające “SOR w walizce”. Rozwiązanie składające się w hardware’u i software’u opracowanego w licencji otwartej przy użyciu CrowdSourcingu (opracowanie, prototypowanie, testowanie i produkcja rozproszona) oraz napędzane przez CrowdFunding. Nasza marka i najwyższe wewnętrzne standardy będą gwarantowały możliwie wysokie bezpieczeństwo. To wszystko za mniej niż 100-200$ (?) na łóżko. 


> Koncepcja 

Cel: zbudowanie “SORu w walizce” przeznaczonego dla jednego łóżka z podzespołów ogólnodostępnych, niedrogich i umożliwiających produkcję przy pomocy stosunkowo prostych narzędzi ale też produkcję zautomatyzowaną.

Na zastaw w wersji 1 składałoby się:
EKG 3-punktowe (moduł Open Hardware) z bramkami dla innych czujników
pulsooksymetr napalcowy
naskórny czujnik temperatury ciała
pendrive z oprogramowaniem Linux zmieniający bez instalowania dowolny komputer PC w tzw. monitor pacjenta / kardiomonitor (prekonfiguracja)
moduł automatycznego nieinwazyjnego pomiaru ciśnienia tętniczego (opcja?)
awaryjny respirator low-cost (TYLKO w sytuacji triażu) m.in. z funkcją “oddychania z pacjentem” (tryb A/C, PSV - brak potrzeby paraliżowania mięśni), wyświetlaniem (PC) i regulacją podstawowych parametrów, alarmami dla personelu, współpracujący z różnymi źródłami powietrza i tlenu

Celem kolejnych wersji rozwojowych byłoby w pierwszej kolejności budowanie jeszcze większej niezawodności i łatwości obsługi bazując na doświadczeniach poprzednich. Tylko pełne wersji (1,2,3,.. itd) byłyby wypuszczane do produkcji jako dopracowanie.

> Plan dla wersji 1 

Etap 1: promocja, planowanie i projektowanie (także selekcja istniejących rozwiązań)
Etap 2: prototypowanie i intensywne testy 
Etap 4: akredytacja / dopuszczenie / certyfikat
Etap 5: masowa produkcja rozproszona 
Etap 6: zbieranie danych oraz iteracja kolejnej wersji jako ulepszenia


> Wyzwania 

opracowanie hardware i softweru, koordynacja
wyeliminowanie podzespołów trudno dostępnych lub mogących być trudno dostępnymi w skali, wykorzystanie podzespołów “z półki”
przyspieszone lecz rygorystyczne testy z udziałem specjalistów/autorytetów
promocja i wykorzystanie efektów społecznych: croudsourcing, croudfinding, viral itp.
akredytacja (TYLKO dla sytuacji triażu) dla sprzętu i oprogramowania przez instytucje pozarządowe, państwowe jednostki na nawet rządy
rozwój kolejnych “wyższych warstw projektu” (support, E-karta pacjęta, remote, AI)


> Istniejące projekty Open Source / Open Hardware

EKG (ECG)
https://www.instructables.com/id/DIY-ECG-EKG-Portable-Heart-Monitor/
https://www.swharden.com/wp/category/diy-ecg-home-made-electrocardiogram/
https://www.youtube.com/watch?v=oHcYBmxfK28&feature=emb_logo
https://www.mccauslandcenter.sc.edu/crnl/open-source-eegecgemg

Respirator (ventilator)
https://web.mit.edu/2.75/projects/DMD_2010_Al_Husseini.pdf
https://github.com/covid-response-projects/covid-respirator
https://hackaday.io/project/170189-pandemic-pressure-control-ventilatorb
https://www.popsolutions.co/openventilator
https://github.com/jcl5m1/ventilator
https://github.com/CSSALTlab/Open_Source_Ventilator
http://www.onebreathventilators.com/
https://github.com/jcl5m1/ventilator/wiki/Build-a-Low-Cost-PAPR
https://www.gofundme.com/f/open-source-pandemic-ventilator
https://www.youtube.com/watch?v=5AAjVFM0t0o

Pulsoksymetr
https://hackaday.com/2010/05/02/diy-pulse-oximeter/
https://www.swharden.com/wp/2013-04-14-simple-diy-ecg-pulse-oximeter-version-2/
http://www.openbiomedical.org/open-source-pulse-oximeter/
https://github.com/GliaX/oximeter

Monitor pacjenta (kilka komponentów zintegrowanych)
https://www.healthysimulation.com/3032/downloadable-vital-sign-simulator-patient-monitor/
https://www.microchip.com/wwwAppNotes/AppNotes.aspx?appnote=en607462


> Instytucje i fundacje które mogą nas wespierać (sojusznicy) 
http://www.biomech.pwr.wroc.pl/index.php/sklad-osobowy/
http://www.brain-it.eu/intensiveShare/
https://www.projectopenair.org/
...


> Baza wiedzy / źródła / linki / kursy / filmy 

https://www.analog.com/en/education/education-library/webcasts/technologies-for-wearable-and-clinical-vital-signs-monitoring.html
https://event.on24.com/wcc/r/1659383/BDB17327A7EB93F9ABD47E9B3AC07A61?partnerref=ADI_Webcast
https://www.healthysimulation.com/3032/downloadable-vital-sign-simulator-patient-monitor/
...


> Media o wirusie i brakach w sprzęcie medycznym 

https://tvn24.pl/swiat/koronawirus-na-swiecie-rosyjscy-oligarchowie-wykupuja-respiratory-4427721
https://www.termedia.pl/mz/Co-z-tymi-respiratorami-,37130.html
https://polskatimes.pl/koronawirus-na-swiecie-wlochy-respiratory-w-pierwszej-kolejnosci-dla-mlodszych-bo-maja-wieksze-szanse-na-przezycie/ar/c1-14859943
https://www.polsatnews.pl/wiadomosc/2020-03-22/osoby-po-60-nie-dostaja-szansy-we-wloszech-za-malo-respiratorow/
https://www.medpagetoday.com/infectiousdisease/covid19/85462 (USA)
https://erj.ersjournals.com/content/27/2/343
https://sensing.honeywell.com/medical/respiratory
https://www.youtube.com/watch?v=gk_Qf-JAL84&t=3s
https://web.mit.edu/2.75/projects/DMD_2010_Al_Husseini.pdf
https://www.capnography.com/physics/types-of-capnographs
https://tvnmeteo.tvn24.pl/informacje-pogoda/swiat,27/przyjrzeli-sie-prawie-19-tysiacom-przypadkow-hiszpanie-wiedza-dla-kogo-koronawirus-jest-najgrozniejszy,318132,1,0.html
https://www.theregister.co.uk/2020/03/18/diy_ventilator_shortage/
https://www.dailymail.co.uk/health/article-8125219/Ventilators-modified-help-FOUR-coronavirus-patients-scientists-say.html




