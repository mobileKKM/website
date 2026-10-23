---
layout: page
title: Polityka prywatności
include_in_header: false
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

<br>

---

# Privacy Policy (English)

This policy covers the **mobileKKM** app (Google Play: `de.codebucket.mkkm`) and the mobilekkm.app website. The app is developed by David Sn as an open-source project ([source code](https://github.com/mobileKKM/mobile_kkm)).

mobileKKM is an **unofficial** app for Kraków's mobile city card (mKKM). It is not affiliated with ZTP or MPK S.A. in Kraków. It lets you use your eKP passenger account (elektroniczne Konto Pasażera): tickets, card and account.

## Summary

- **mobileKKM does not collect your data.** We run no server with user accounts and use no analytics, ads, crash reporting or Google Firebase services.
- Your data (account, tickets, payments) goes **directly to eKP**, whose controller is ZTP Kraków.
- Your location, photos and the tickets kept on your phone **stay on your phone**, unless you send a profile photo to eKP yourself.

## Services the app uses

| Service | Purpose | What it receives |
| :--- | :--- | :--- |
| **eKP** (`api.ekp.mpk.krakow.pl`), ZTP / MPK S.A. Kraków | Sign-in, account, card, tickets, purchase, ticket control | Everything you enter in the app (e-mail, password, personal details, photo, tickets) and, with every request: a random installation ID, OS and version, phone model, app version and your IP address. The same as the official mKKM app. |
| **relay.mobilekkm.app** (our server) | Fetches the public key used to encrypt ticket requests. It means your phone never contacts Google Firebase, where the official app gets this key. | Only the app's name and version and your IP address. No account data. The server keeps no access logs: IP addresses and request times are not stored anywhere. |
| **Cloudflare** | Protects and delivers traffic to relay.mobilekkm.app | IP address and technical connection data, processed under [Cloudflare's policy](https://www.cloudflare.com/privacypolicy/). |
| **tPay** (`secure.tpay.com`) | Paying for tickets, in a browser tab | The payment details you give tPay. The app does not see them. [tPay's policy](https://tpay.com/polityka-prywatnosci). |
| **OpenFreeMap** (`tiles.openfreemap.org`) | Map | IP address and the map area you view. Not your location. |
| **External websites** (e.g. ekp.mpk.krakow.pl, GitHub) | Links opened in the browser | What any visited website receives. |

The controller of eKP data is **Zarząd Transportu Publicznego w Krakowie** (ZTP, ul. Wielopole 1, 31-072 Kraków, Poland), and it is processed by **MPK S.A. w Krakowie**. Their rules are in eKP's [information notice](https://ekp.mpk.krakow.pl/documents/Obowi%C4%85zek%20informacyjny-sprzeda%C5%BC%20internetowa%20bilet%C3%B3w.pdf) and at [ztp.krakow.pl/rodo](https://ztp.krakow.pl/rodo) (Polish).

## Data on your phone

The app stores locally:

- your sign-in session and a random installation ID (in the system's encrypted storage),
- copies of your tickets, so they work offline,
- reference lists from eKP (such as lines and ticket types) and an image cache.

Signing out removes the session and ticket copies. Uninstalling the app or clearing its data removes everything.

## Permissions

- **Location**: only on the map, after you tap the location button, to show where you are. Your location is never sent anywhere.
- **Camera and photos**: only when you add a profile photo. The chosen photo is sent to eKP, which requires it.
- **Internet**: to connect to the services above.

Ticket codes are protected from screenshots.

## Children

An eKP account for someone under 16 is created by a parent or legal guardian. The app does not register such accounts and sends you to the eKP website's form instead.

## Your rights

Your account data is held by eKP, so GDPR rights (access, correction, deletion, restriction, objection, portability) are handled by ZTP Kraków: [iodo@ztp.krakow.pl](mailto:iodo@ztp.krakow.pl), or MPK S.A.: [iodo@mpk.krakow.pl](mailto:iodo@mpk.krakow.pl). You can also complain to the Polish data protection authority (Prezes Urzędu Ochrony Danych Osobowych).

- [Account deletion](usuwanie-konta.html)
- [Data deletion](usuwanie-danych.html)

## The mobilekkm.app website

The website is hosted on GitHub Pages, which may log visitors' IP addresses ([GitHub's policy](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)). It loads fonts and icons from Google Fonts and cdnjs (Cloudflare), which also see your IP address. We use no cookies or analytics on it.

## Changes

Changes to this policy will be published on this page with an updated date at the top.

## Contact

[mobilekkm@codebucket.de](mailto:mobilekkm@codebucket.de)
