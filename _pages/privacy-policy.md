---
layout: page
title: Polityka prywatności
include_in_header: false
order: 3
ref: privacy
description: "mobileKKM nie zbiera Twoich danych: bez analityki, reklam i Google Firebase. Zobacz, z jakich usług korzysta aplikacja."
---

**Ostatnia aktualizacja**  
23 października 2026

# Polityka prywatności

Ta polityka dotyczy aplikacji **mobileKKM** (Google Play: `de.codebucket.mkkm`) i strony mobilekkm.app. Aplikację tworzy David Sn jako projekt open source ([kod źródłowy](https://github.com/mobileKKM/mobile_kkm)).

mobileKKM to **nieoficjalna** aplikacja do mobilnej Krakowskiej Karty Miejskiej (mKKM). Nie jest powiązana z ZTP ani MPK S.A. w Krakowie. Służy do obsługi Twojego elektronicznego Konta Pasażera (eKP): biletów, karty i konta.

## W skrócie

- **mobileKKM nie zbiera Twoich danych.** Nie mamy serwera z kontami użytkowników, nie używamy analityki, reklam, raportowania błędów ani usług Google Firebase.
- Twoje dane (konto, bilety, płatności) trafiają **bezpośrednio do eKP**, którego administratorem jest ZTP w Krakowie.
- Lokalizacja, zdjęcia i bilety, które zostają na telefonie, **nie opuszczają go**, chyba że sam wyślesz zdjęcie profilowe do eKP.

## Usługi, z których korzysta aplikacja

| Usługa | Po co | Co otrzymuje |
| :--- | :--- | :--- |
| **eKP** (`api.ekp.mpk.krakow.pl`), ZTP / MPK S.A. w Krakowie | Logowanie, konto, karta, bilety, zakup, kontrola biletów | Wszystko, co podajesz w aplikacji (e-mail, hasło, dane osobowe, zdjęcie, bilety), a przy każdym zapytaniu: losowy identyfikator instalacji, system i jego wersję, model telefonu, wersję aplikacji i adres IP. Tak samo jak oficjalna aplikacja mKKM. |
| **relay.mobilekkm.app** (nasz serwer) | Pobranie publicznego klucza potrzebnego do szyfrowania zapytań o bilety. Dzięki niemu Twój telefon nie łączy się z Google Firebase, skąd ten klucz pobiera oficjalna aplikacja. | Tylko nazwę i wersję aplikacji oraz adres IP. Żadnych danych konta. Serwer nie zapisuje logów dostępu: adresy IP i czasy zapytań nie są nigdzie przechowywane. |
| **Cloudflare** | Ochrona i dostarczanie ruchu do relay.mobilekkm.app | Adres IP i dane techniczne połączenia, przetwarzane przez Cloudflare zgodnie z [jego polityką](https://www.cloudflare.com/privacypolicy/). |
| **tPay** (`secure.tpay.com`) | Płatność za bilet, w karcie przeglądarki | Dane płatności, które podajesz tPay. Aplikacja ich nie widzi. [Polityka tPay](https://tpay.com/polityka-prywatnosci). |
| **OpenFreeMap** (`tiles.openfreemap.org`) | Mapa | Adres IP i obszar mapy, który oglądasz. Nie Twoją lokalizację. |
| **Strony zewnętrzne** (np. ekp.mpk.krakow.pl, GitHub) | Linki otwierane w przeglądarce | To, co zwykle otrzymuje odwiedzana strona. |

Administratorem danych eKP jest **Zarząd Transportu Publicznego w Krakowie** (ul. Wielopole 1, 31-072 Kraków), a przetwarza je **MPK S.A. w Krakowie**. Zasady opisuje [obowiązek informacyjny eKP](https://ekp.mpk.krakow.pl/documents/Obowi%C4%85zek%20informacyjny-sprzeda%C5%BC%20internetowa%20bilet%C3%B3w.pdf) i strona [ztp.krakow.pl/rodo](https://ztp.krakow.pl/rodo).

## Dane na Twoim telefonie

Aplikacja zapisuje lokalnie:

- sesję logowania i losowy identyfikator instalacji (w zaszyfrowanym magazynie systemu),
- kopie Twoich biletów, żeby były dostępne bez internetu,
- słowniki z eKP (np. listy linii i biletów) oraz pamięć podręczną obrazków.

Wylogowanie usuwa sesję i kopie biletów. Odinstalowanie aplikacji lub wyczyszczenie jej danych usuwa wszystko.

## Uprawnienia

- **Lokalizacja**: tylko na mapie, po dotknięciu przycisku lokalizacji, żeby pokazać Twoją pozycję. Lokalizacja nie jest nigdzie wysyłana.
- **Aparat i zdjęcia**: tylko gdy dodajesz zdjęcie profilowe. Wybrane zdjęcie jest wysyłane do eKP, które go wymaga.
- **Internet**: do połączeń z usługami powyżej.

Kody biletów są chronione przed zrzutami ekranu.

## Dzieci

Konto eKP osoby poniżej 16 lat zakłada rodzic lub opiekun prawny. Aplikacja nie rejestruje takich kont i kieruje do formularza na stronie eKP.

## Twoje prawa

Dane Twojego konta są w eKP, więc prawa z RODO (dostęp, sprostowanie, usunięcie, ograniczenie, sprzeciw, przenoszenie) realizuje ZTP w Krakowie: [iodo@ztp.krakow.pl](mailto:iodo@ztp.krakow.pl), lub MPK S.A.: [iodo@mpk.krakow.pl](mailto:iodo@mpk.krakow.pl). Możesz też złożyć skargę do Prezesa Urzędu Ochrony Danych Osobowych.

- [Usuwanie konta](usuwanie-konta.html)
- [Usuwanie danych](usuwanie-danych.html)

## Strona mobilekkm.app

Strona jest hostowana na GitHub Pages, który może zapisywać adres IP odwiedzających ([polityka GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)). Czcionki i ikony pobiera z Google Fonts i cdnjs (Cloudflare), które również widzą adres IP. Nie używamy na niej plików cookie ani analityki.

## Zmiany

Zmiany tej polityki opublikujemy na tej stronie i zaktualizujemy datę na górze.

## Kontakt

[mobilekkm@codebucket.de](mailto:mobilekkm@codebucket.de)
