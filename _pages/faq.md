---
layout: page
title: FAQ
include_in_header: true
order: 2
ref: faq
description: "Odpowiedzi na najczęstsze pytania o mobileKKM: bilety na mKKM, kontrola biletów, Karta Krakowska, konto i prywatność."
---
**Ostatnia aktualizacja**  
23 października 2026

# Najczęściej zadawane pytania

## O aplikacji

### Czy mobileKKM to oficjalna aplikacja?

Nie. mobileKKM to nieoficjalna aplikacja, niepowiązana z ZTP ani MPK S.A. w Krakowie. Korzysta z tego samego elektronicznego Konta Pasażera (eKP) i tej samej mobilnej Krakowskiej Karty Miejskiej (mKKM) co oficjalna aplikacja „mobilna KKM”.

### Dlaczego powstała mobileKKM?

mobileKKM powstała w 2018 roku. Mobilna KKM była wtedy dostępna tylko jako strona internetowa m.kkm.krakow.pl. Korzystanie z niej w przeglądarce było niewygodne, a przy każdym pokazaniu biletu trzeba było logować się od nowa. Autor stworzył mobileKKM najpierw dla siebie, a potem udostępnił ją innym. Oficjalna aplikacja „mobilna KKM” pojawiła się dopiero około 2021 roku. Dziś celem mobileKKM jest darmowa i otwarta alternatywa, którą każdy może sprawdzić i ulepszyć.

### Jaki jest status prawny aplikacji?

mobileKKM to niezależny projekt open source na licencji GPL w wersji 3 lub nowszej, tworzony przez David Sn. Nie jest powiązana z ZTP ani MPK S.A. w Krakowie, nie ma ich zgody ani wsparcia.

Aplikacja łączy się z tymi samymi serwerami eKP co oficjalna aplikacja „mobilna KKM”. Sposób komunikacji z nimi ustalono, analizując działanie oficjalnej aplikacji, wyłącznie w celu osiągnięcia współdziałania (interoperacyjności) niezależnego programu. Pozwala na to art. 75 ust. 2 pkt 3 ustawy o prawie autorskim i prawach pokrewnych, który wdraża art. 6 dyrektywy 2009/24/WE.

### Czy korzystanie z mobileKKM jest legalne?

Korzystasz z niej na tych samych zasadach co z oficjalnej aplikacji. Logujesz się własnym kontem eKP i kupujesz zwykłe bilety, za które płacisz MPK S.A. przez tPay. Bilety są zapisane w eKP i są tak samo ważne jak bilety kupione w oficjalnej aplikacji.

Pamiętaj, że ZTP lub MPK mogą w każdej chwili zmienić swój system albo zablokować nieoficjalne aplikacje. Twoje konto i bilety zostają wtedy w eKP, więc nadal zobaczysz je w oficjalnej aplikacji „mobilna KKM” i na [ekp.mpk.krakow.pl](https://ekp.mpk.krakow.pl).

### Czym mobileKKM różni się od oficjalnej aplikacji?

Obie korzystają z tego samego konta eKP, tej samej mKKM i tych samych biletów. mobileKKM oferuje jednak m.in.:

- **Wygodniejszą kontrolę biletów.** Kod odnawia się sam, więc ekran może być otwarty przez całą kontrolę. Ekran rozjaśnia się i nie wygasa, a kod można powiększyć na cały ekran.
- **Bilety bez internetu.** Bilety i dane konta są zapisane na telefonie, więc zobaczysz je także offline. Oficjalna aplikacja bez połączenia się nie uruchomi.
- **Wszystko ważne na pierwszy rzut oka.** Ekran główny od razu pokazuje Twój bilet i najważniejsze akcje. Przed powiązaniem biletu z telefonem aplikacja pyta o potwierdzenie.
- **Prywatność.** Bez śledzenia, analityki i Google Firebase, które ma oficjalna aplikacja. Do tego otwarty kod i dostępność w [F-Droid]({{ site.data.app.download.fdroid }}). Szczegóły w [polityce prywatności](privacy-policy.html).
- **Język angielski** oraz jasny i ciemny motyw.

### Czy aplikacja jest bezpłatna?

Tak, i zawsze będzie. mobileKKM to wolne oprogramowanie na licencji GPL, bez reklam, opłat i płatnych funkcji. Płacisz tylko za bilety, po cenach z [cennika ZTP](cennik.html), bez żadnych dopłat.

Stoi za tym zasada [„Publiczne pieniądze, publiczny kod”](https://publiccode.eu/pl/): oprogramowanie do usług finansowanych ze środków publicznych, takich jak komunikacja miejska, powinno być otwarte i dostępne dla wszystkich.

### Czy jest wersja na iPhone'a?

Na razie nie. mobileKKM jest dostępna na Androida w [Google Play]({{ site.data.app.download.playstore }}) i [F-Droid]({{ site.data.app.download.fdroid }}). Nowa wersja aplikacji jest napisana we Flutterze i testowana zarówno na Androidzie, jak i na iOS, więc w przyszłości mobileKKM może trafić także do App Store.

## Bilety i kontrola

### Czy mogę używać plastikowej karty KKM?

Nie. mobileKKM działa tylko z **mobilną Krakowską Kartą Miejską (mKKM)**. Biletów zapisanych na plastikowej KKM, Małopolskiej Karcie Aglomeracyjnej (MKA) czy innych kartach nie zobaczysz ani nie kupisz w aplikacji. Do nich służą [ekp.mpk.krakow.pl](https://ekp.mpk.krakow.pl), automaty biletowe i [Punkty Obsługi Pasażerów](https://ztp.krakow.pl/kmk/punkty-obslugi-pasazerow-kmk).

### Jak zacząć?

Zaloguj się kontem eKP (albo załóż je w aplikacji) i załóż w aplikacji mKKM ze swoim zdjęciem. Potem możesz kupować bilety na mKKM.

### Jak kupić bilet?

Wybierz bilet w aplikacji i zapłać przez tPay. Płatność otwiera się w karcie przeglądarki, więc aplikacja nie widzi danych Twojej karty płatniczej. Ceny znajdziesz w [cenniku](cennik.html).

### Na ilu urządzeniach mogę używać biletu?

Żeby pokazać bilet do kontroli, trzeba go najpierw powiązać z urządzeniem. **Jeden bilet można powiązać z najwyżej dwoma urządzeniami.** Powiązania nie da się cofnąć w aplikacji.

Za osobne urządzenie liczy się każda instalacja aplikacji. Osobne miejsce zajmuje więc np.:

- mobileKKM obok oficjalnej aplikacji „mobilna KKM” na tym samym telefonie (każda zajmuje własne miejsce),
- ponowna instalacja mobileKKM albo wyczyszczenie jej danych,
- nowy telefon.

Dlatego nie powiązuj biletu „na próbę” i zanim zmienisz telefon albo przeinstalujesz aplikację, upewnij się, że masz jeszcze wolne miejsce.

### Nie mogę już powiązać biletu. Co teraz?

Jeśli bilet jest już powiązany z dwoma urządzeniami, pokaż go do kontroli na jednym z nich. Jeśli nie masz już dostępu do żadnego z nich (np. po zgubieniu lub wymianie telefonu), zadzwoń na Infolinię MPK S.A. w Krakowie: 12 19 150. mobileKKM nie może usunąć powiązania za Ciebie.

### Czy bilet z mobileKKM jest ważny podczas kontroli?

Tak. To ten sam bilet na mKKM w eKP, który widzisz w oficjalnej aplikacji. Podczas kontroli otwórz aplikację i pokaż kod biletu.

### Czy aplikacja działa bez internetu?

Częściowo. Kopie Twoich biletów są zapisane na telefonie, więc ich szczegóły zobaczysz także bez połączenia. **Kod do kontroli biletów wymaga jednak aktywnego połączenia z internetem.**

Jeśli podczas kontroli nie masz zasięgu, powiedz o tym kontrolerowi. Kontroler może przyjąć bilet albo poprosić o ponowne okazanie kodu, gdy złapiesz zasięg. Jeśli mimo to dostaniesz wezwanie do zapłaty, możesz je anulować. Zobacz [pytanie poniżej](#anulowanie-mandatu).

### Dostałem mandat mimo ważnego biletu. Jak go anulować? {#anulowanie-mandatu}

Jeśli w chwili kontroli miałeś ważny bilet okresowy na mKKM, ale nie mogłeś go okazać (np. bez zasięgu albo z rozładowanym telefonem), masz **7 dni od dnia przejazdu**, żeby go pokazać. Możesz to zrobić:

- **osobiście** w Punkcie Obsługi Pasażerów KMK: os. Centrum D 7 (wejście 2), 31-933 Kraków, pon.–pt. 11:00–18:00, tel. 453 039 913,
- **pocztą** na ten sam adres (data stempla najpóźniej 7. dnia od przejazdu),
- **e-mailem** na [reklamacje.bilety@ztp.krakow.pl](mailto:reklamacje.bilety@ztp.krakow.pl): wyślij zrzut ekranu ze szczegółami biletu, swój numer klienta i numer wezwania do zapłaty.

Warunkiem anulowania jest **opłata manipulacyjna 20,00 zł**, także w ciągu 7 dni: przelewem na konto 14 1020 2892 0000 5102 0869 8823 (PKO Bank Polski, w tytule numer wezwania) albo w kasie Punktu Obsługi Pasażerów. Jeśli zapłaciłeś opłatę dodatkową na miejscu u kontrolera, dostaniesz zwrot pomniejszony o te 20 zł.

mobileKKM nie może anulować mandatu za Ciebie. Sprawę załatwiasz bezpośrednio z ZTP. Wysokość opłat, terminy płatności i zasady reklamacji sprawdzisz na stronie [Kontrola biletów KMK](https://ztp.krakow.pl/kmk/kontrola-biletow-kmk).

## Karta Krakowska {#karta-krakowska}

### Czym jest Karta Krakowska i do czego jej potrzebuję?

Status Karty Krakowskiej uprawnia m.in. do tańszych [Biletów Mieszkańca](cennik.html#bilety-mieszkanca). Mogą go dostać osoby zameldowane na pobyt stały w Krakowie lub rozliczające PIT w Krakowie (ze wskazaniem Krakowa jako miejsca zamieszkania), a także ich dzieci do 18. roku życia. Bez Karty Krakowskiej możesz kupić [Bilet Metropolitalny](cennik.html#bilet-metropolitalny). W mobileKKM Bilety Mieszkańca nazywają się **biletami sieciowymi**.

Status jest ważny rok. Wniosek składa się na [kk.krakow.pl](https://www.kk.krakow.pl/jak-wyrobic-karte-krakowska) albo w Punkcie Obsługi Pasażerów.

### mKKM, mKK, mKraków: czym to się różni?

To najczęstsze źródło pomyłek. „Karta Krakowska” to dwie rzeczy:

- **status** Karty Krakowskiej, czyli Twoje uprawnienie do zniżek,
- **nośnik** o tej samej nazwie, czyli miejska karta plastikowa (KK) albo aplikacja **mKraków** (dawniej mKK).

**mKKM** to inny nośnik: mobilna Krakowska Karta Miejska w eKP, której używają mobileKKM i oficjalna aplikacja „mobilna KKM”.

Status może być zapisany **tylko na jednym nośniku**. Wyjątek: na Karcie Krakowskiej oraz na KKM może być naraz w formie plastikowej i mobilnej. Status w aplikacji mKraków nie działa więc na mKKM. **Żeby kupić Bilet Mieszkańca w mobileKKM, status musi być zapisany na mKKM.**

### Jak uzyskać status Karty Krakowskiej na mKKM?

1. Najpierw załóż mKKM w mobileKKM.
2. Złóż „Wniosek o wydanie Karty” na [kk.krakow.pl](https://www.kk.krakow.pl/jak-wyrobic-karte-krakowska) albo na papierze w [Punkcie Obsługi Pasażerów](https://ztp.krakow.pl/kmk/punkty-obslugi-pasazerow-kmk).
3. Jako nośnik wybierz **Krakowską Kartę Miejską w formie mobilnej (mKKM)**.
4. Zaznacz zgodę na udostępnienie danych ZTP. Bez niej, żeby kupować bilety okresowe, trzeba będzie pójść do Punktu Obsługi Pasażerów.
5. Jeśli nie jesteś zameldowany w Krakowie, dołącz dokument potwierdzający rozliczenie PIT w Krakowie.

Wniosek jest rozpatrywany do 30 dni. Po pozytywnej decyzji status zapisuje się na mKKM automatycznie.

### Mam status na innym nośniku. Jak przenieść go na mKKM?

Dotyczy to statusu zapisanego np. w aplikacji mKraków, na plastikowej Karcie Krakowskiej, KKM, MKA lub legitymacji studenckiej.

Formularze „zmiany nośnika” i „dodatkowej formy” **nie pomogą**, bo przenoszą status tylko na Kartę Krakowską (plastikową KK albo mKraków), nigdy na mKKM. Obecnie jedyna droga to:

1. **Unieważnij obecny status.** „Wniosek o unieważnienie Karty” składa się tylko na papierze, w dowolnym [Punkcie Obsługi Pasażerów](https://ztp.krakow.pl/kmk/punkty-obslugi-pasazerow-kmk). Unieważnienie działa od dnia złożenia wniosku. Nie zaznaczaj usunięcia danych z programu.
2. **Złóż nowy „Wniosek o wydanie Karty”** i wybierz jako nośnik mKKM, jak w pytaniu powyżej.

Wskazówki:

- Oba wnioski możesz złożyć podczas jednej wizyty w Punkcie Obsługi Pasażerów.
- Nowy wniosek może być rozpatrywany do 30 dni, a przez ten czas nie masz statusu. Najlepiej zrobić to, gdy masz jeszcze ważny bilet, i zapytać w punkcie, czy pozostanie on ważny.
- Jeśli status masz na **plastikowej KKM**, może on być jednocześnie na mKKM. O taką zmianę zapytaj w Punkcie Obsługi Pasażerów.

Wzory wszystkich wniosków i procedurę znajdziesz na [kk.krakow.pl](https://www.kk.krakow.pl/aktyprawne/wzory-wnioskow/).

### Jak przedłużyć status?

Status jest ważny rok od pozytywnego rozpatrzenia wniosku. Osobom zameldowanym na pobyt stały w Krakowie (i ich dzieciom) przedłuża się sam, bez wniosku. Pozostałe osoby składają „Wniosek o przedłużenie ważności Karty”, najwcześniej miesiąc przed końcem ważności. Na nośniku mobilnym, takim jak mKKM, przedłużony status zapisuje się automatycznie.

### Gdzie uzyskam pomoc w sprawie Karty Krakowskiej?

Infolinia Karty Krakowskiej: 12 616 55 55, e-mail: [kontaktkk@um.krakow.pl](mailto:kontaktkk@um.krakow.pl). mobileKKM nie ma dostępu do Twojego statusu i nie może go zmienić.

## Konto i dane

### Jakim kontem się logować?

Swoim elektronicznym Kontem Pasażera (eKP), tym samym co na [ekp.mpk.krakow.pl](https://ekp.mpk.krakow.pl) i w oficjalnej aplikacji „mobilna KKM”. mobileKKM nie ma własnych kont.

### Czy moje dane są bezpieczne?

mobileKKM nie zbiera Twoich danych. Nie mamy serwera z kontami użytkowników, analityki ani reklam. Twoje dane trafiają bezpośrednio do eKP, którego administratorem jest ZTP. Szczegóły w [polityce prywatności](privacy-policy.html).

### Jak usunąć konto lub dane?

Zobacz strony [Usuwanie konta](usuwanie-konta.html) i [Usuwanie danych](usuwanie-danych.html).

## Problemy i kontakt

### Mam problem z płatnością, chcę zwrócić bilet albo złożyć reklamację

Bilety sprzedaje i rozlicza MPK S.A. na zlecenie ZTP, więc zwroty i reklamacje załatwiasz bezpośrednio u nich:

- reklamacje dotyczące mKKM i eKP: tel. 607 600 070 (całą dobę),
- formularz zwrotu biletu okresowego: w [przewodniku po biletach KMK](https://ztp.krakow.pl/kmk/przewodnik-po-biletach-kmk),
- osobiście: w [Punkcie Obsługi Pasażerów](https://ztp.krakow.pl/kmk/punkty-obslugi-pasazerow-kmk).

### Nie mogę się zalogować

Sprawdź, czy możesz zalogować się na [ekp.mpk.krakow.pl](https://ekp.mpk.krakow.pl). Jeśli tam też się nie udaje, zresetuj hasło na tej stronie albo zadzwoń na Infolinię MPK S.A. w Krakowie: 12 19 150.

### Znalazłem błąd w aplikacji

Zgłoś go na [GitHubie](https://github.com/mobileKKM/mobile_kkm/issues) albo napisz: [mobilekkm@codebucket.de](mailto:mobilekkm@codebucket.de).
