---
layout: page
title: FAQ
include_in_header: true
order: 2
ref: faq
description: "Answers to common questions about mobileKKM: tickets on mKKM, ticket inspections, Karta Krakowska, your account and privacy."
---
**Last updated**  
October 23, 2026

# Frequently asked questions

## About the app

### Is mobileKKM an official app?

No. mobileKKM is an unofficial app, not affiliated with ZTP or MPK S.A. in Kraków. It uses the same electronic passenger account (eKP, elektroniczne Konto Pasażera) and the same mobile Kraków City Card (mKKM, mobilna Krakowska Karta Miejska) as the official “mobilna KKM” app.

### Why was mobileKKM made?

mobileKKM was created in 2018. Back then, the mobile KKM was only available as the website m.kkm.krakow.pl. Using it in a browser was awkward, and you had to sign in again every time you showed your ticket. The author first made mobileKKM for personal use, then shared it with others. The official “mobilna KKM” app only appeared around 2021. Today, the goal of mobileKKM is to be a free and open alternative that anyone can check and improve.

### What is the app's legal status?

mobileKKM is an independent open-source project licensed under the GPL version 3 or later, developed by David Sn. It is not affiliated with ZTP or MPK S.A. in Kraków, and has neither their approval nor their support.

The app connects to the same eKP servers as the official “mobilna KKM” app. How to communicate with them was worked out by analysing the official app, solely to make an independent program interoperable. This is permitted by Art. 75(2)(3) of the Polish Copyright Act, which implements Art. 6 of Directive 2009/24/EC.

### Is it legal to use mobileKKM?

You use it on the same terms as the official app. You sign in with your own eKP account and buy regular tickets, which you pay MPK S.A. for through tPay. The tickets are stored in eKP and are just as valid as tickets bought in the official app.

Keep in mind that ZTP or MPK may change their system or block unofficial apps at any time. Your account and tickets stay in eKP, so you will still see them in the official “mobilna KKM” app and on [ekp.mpk.krakow.pl](https://ekp.mpk.krakow.pl).

### How is mobileKKM different from the official app?

Both use the same eKP account, the same mKKM and the same tickets. mobileKKM, however, offers among other things:

- **Easier ticket inspections.** The code refreshes on its own, so the screen can stay open for the whole inspection. The screen brightens and doesn't time out, and you can enlarge the code to full screen.
- **Tickets without internet.** Your tickets and account details are stored on your phone, so you can see them offline. The official app won't start without a connection.
- **Everything important at a glance.** The home screen shows your ticket and the main actions straight away. The app asks you to confirm before linking a ticket to your phone.
- **Privacy.** No tracking, analytics or Google Firebase, which the official app has. Plus open source code and availability on [F-Droid]({{ site.data.app.download.fdroid }}). Details in the [privacy policy](privacy-policy.html).
- **English language** and a light and dark theme.

### Is the app free?

Yes, and it always will be. mobileKKM is free software under the GPL, with no ads, fees or paid features. You only pay for tickets, at [ZTP's prices](prices.html), with no surcharge.

It follows the [“Public Money, Public Code”](https://publiccode.eu/) principle: software for publicly funded services, such as public transport, should be open and available to everyone.

### Is there an iPhone version?

Not yet. mobileKKM is available for Android on [Google Play]({{ site.data.app.download.playstore }}) and [F-Droid]({{ site.data.app.download.fdroid }}). The new version of the app is written in Flutter and tested on both Android and iOS, so mobileKKM may come to the App Store in the future.

## Tickets and inspections

### Can I use a plastic KKM card?

No. mobileKKM only works with the **mobile Kraków City Card (mKKM)**. Tickets stored on a plastic KKM, the Małopolska Agglomeration Card (MKA) or other cards can't be seen or bought in the app. For those, use [ekp.mpk.krakow.pl](https://ekp.mpk.krakow.pl), ticket machines and the [Passenger Service Points](https://ztp.krakow.pl/kmk/punkty-obslugi-pasazerow-kmk) (Polish).

### How do I get started?

Sign in with your eKP account (or create one in the app), then create your mKKM with your photo in the app. After that, you can buy tickets on your mKKM.

### How do I buy a ticket?

Choose a ticket in the app and pay through tPay. The payment opens in a browser tab, so the app never sees your payment card details. You can find the prices in the [price list](prices.html).

### On how many devices can I use a ticket?

To show a ticket during an inspection, you first have to link it to a device. **One ticket can be linked to at most two devices.** A link can't be undone in the app.

Every installation of the app counts as a separate device. So each of these takes up a separate slot:

- mobileKKM next to the official “mobilna KKM” app on the same phone (each takes its own slot),
- reinstalling mobileKKM or clearing its data,
- a new phone.

So don't link a ticket “just to try”, and before you change phones or reinstall the app, make sure you still have a free slot.

### I can't link my ticket any more. What now?

If the ticket is already linked to two devices, show it during inspections on one of them. If you no longer have access to either of them (for example after losing or replacing your phone), call the MPK S.A. Kraków helpline: +48 12 19 150. mobileKKM can't remove the link for you.

### Is a ticket from mobileKKM valid during an inspection?

Yes. It is the same ticket on your mKKM in eKP that you see in the official app. During an inspection, open the app and show the ticket code.

### Does the app work without internet?

Partly. Copies of your tickets are stored on your phone, so you can see their details without a connection. **The code for ticket inspections, however, needs an active internet connection.**

If you have no signal during an inspection, tell the inspector. The inspector may accept the ticket or ask you to show the code again once you have a signal. If you still get a penalty notice, you can have it cancelled. See the [question below](#cancelling-a-fine).

### I got a fine even though I had a valid ticket. How do I cancel it? {#cancelling-a-fine}

If you had a valid period ticket on your mKKM at the time of the inspection but couldn't show it (for example with no signal or a flat battery), you have **7 days from the day of travel** to show it. You can do this:

- **in person** at the KMK Passenger Service Point: os. Centrum D 7 (entrance 2), 31-933 Kraków, Mon–Fri 11:00–18:00, phone +48 453 039 913,
- **by post** to the same address (postmarked no later than the 7th day after the journey),
- **by e-mail** to [reklamacje.bilety@ztp.krakow.pl](mailto:reklamacje.bilety@ztp.krakow.pl): send a screenshot of the ticket details, your customer number and the penalty notice number.

The fine is only cancelled after you pay a **20.00 zł handling fee**, also within 7 days: by bank transfer to account 14 1020 2892 0000 5102 0869 8823 (PKO Bank Polski, with the penalty notice number as the payment reference) or at the Passenger Service Point's cash desk. If you paid the additional fee to the inspector on the spot, you will get a refund minus these 20 zł.

mobileKKM can't cancel a fine for you. You deal with ZTP directly. Fees, payment deadlines and complaint rules are on the [KMK ticket inspection](https://ztp.krakow.pl/kmk/kontrola-biletow-kmk) page (Polish).

## Karta Krakowska {#karta-krakowska}

### What is Karta Krakowska and why do I need it?

The Karta Krakowska (Kraków Card) status entitles you to, among other things, the cheaper [Resident Tickets](prices.html#resident-tickets). You can get it if you are registered as a permanent resident of Kraków or pay income tax (PIT) in Kraków (with Kraków as your place of residence), and so can your children under 18. Without Karta Krakowska, you can buy the [Metropolitan Ticket](prices.html#metropolitan-ticket). In mobileKKM, Resident Tickets are called **network tickets**.

The status is valid for one year. You apply on [kk.krakow.pl](https://www.kk.krakow.pl/jak-wyrobic-karte-krakowska) (Polish) or at a Passenger Service Point.

### mKKM, mKK, mKraków: what's the difference?

This is the most common source of confusion. “Karta Krakowska” means two things:

- the Karta Krakowska **status**, which is your entitlement to discounts,
- the **carrier** with the same name: the city's plastic card (KK) or the **mKraków** app (formerly mKK).

**mKKM** is a different carrier: the mobile Kraków City Card in eKP, used by mobileKKM and the official “mobilna KKM” app.

The status can be stored **on only one carrier**. The exception: on Karta Krakowska and on the KKM, it can be in both plastic and mobile form at the same time. So a status in the mKraków app doesn't work on mKKM. **To buy a Resident Ticket in mobileKKM, the status must be stored on your mKKM.**

### How do I get the Karta Krakowska status on my mKKM?

1. First, create your mKKM in mobileKKM.
2. Submit the “Wniosek o wydanie Karty” (card application) on [kk.krakow.pl](https://www.kk.krakow.pl/jak-wyrobic-karte-krakowska) or on paper at a [Passenger Service Point](https://ztp.krakow.pl/kmk/punkty-obslugi-pasazerow-kmk).
3. As the carrier, choose **Krakowska Karta Miejska w formie mobilnej (mKKM)**.
4. Tick the consent to share your data with ZTP. Without it, you will have to go to a Passenger Service Point to buy period tickets.
5. If you are not registered as a resident of Kraków, attach a document confirming you pay PIT in Kraków.

The application is processed within 30 days. Once it is approved, the status is stored on your mKKM automatically.

### My status is on another carrier. How do I move it to my mKKM?

This applies to a status stored, for example, in the mKraków app, on a plastic Karta Krakowska, KKM, MKA or a student ID.

The “carrier change” (zmiana nośnika) and “additional form” (dodatkowa forma) forms **won't help**, because they only move the status to Karta Krakowska (the plastic KK or mKraków), never to mKKM. Currently, the only way is:

1. **Cancel your current status.** The “Wniosek o unieważnienie Karty” (card cancellation application) can only be submitted on paper, at any [Passenger Service Point](https://ztp.krakow.pl/kmk/punkty-obslugi-pasazerow-kmk). The cancellation takes effect on the day you submit it. Don't tick the option to delete your data from the programme.
2. **Submit a new “Wniosek o wydanie Karty”** and choose mKKM as the carrier, as in the question above.

Tips:

- You can submit both applications in one visit to a Passenger Service Point.
- The new application may take up to 30 days, and you have no status during that time. It's best to do this while you still have a valid ticket, and to ask at the service point whether it will stay valid.
- If your status is on a **plastic KKM**, it can be on your mKKM at the same time. Ask about this change at a Passenger Service Point.

All application forms and the procedure are on [kk.krakow.pl](https://www.kk.krakow.pl/aktyprawne/wzory-wnioskow/) (Polish).

### How do I renew the status?

The status is valid for one year from when the application is approved. For people registered as permanent residents of Kraków (and their children), it renews by itself, with no application. Everyone else submits the “Wniosek o przedłużenie ważności Karty” (renewal application), at the earliest one month before it expires. On a mobile carrier such as mKKM, the renewed status is stored automatically.

### Where can I get help with Karta Krakowska?

Karta Krakowska helpline: +48 12 616 55 55, e-mail: [kontaktkk@um.krakow.pl](mailto:kontaktkk@um.krakow.pl). mobileKKM has no access to your status and can't change it.

## Account and data

### Which account do I sign in with?

Your eKP account, the same one you use on [ekp.mpk.krakow.pl](https://ekp.mpk.krakow.pl) and in the official “mobilna KKM” app. mobileKKM has no accounts of its own.

### Is my data safe?

mobileKKM doesn't collect your data. We have no server with user accounts, no analytics and no ads. Your data goes directly to eKP, whose controller is ZTP. Details in the [privacy policy](privacy-policy.html).

### How do I delete my account or data?

See the [Account deletion](account-deletion.html) and [Data deletion](data-deletion.html) pages.

## Problems and contact

### I have a payment problem, want to return a ticket or make a complaint

Tickets are sold and settled by MPK S.A. on behalf of ZTP, so refunds and complaints are handled by them directly:

- complaints about mKKM and eKP: phone +48 607 600 070 (24/7),
- period ticket refund form: in the [KMK ticket guide](https://ztp.krakow.pl/kmk/przewodnik-po-biletach-kmk) (Polish),
- in person: at a [Passenger Service Point](https://ztp.krakow.pl/kmk/punkty-obslugi-pasazerow-kmk).

### I can't sign in

Check whether you can sign in on [ekp.mpk.krakow.pl](https://ekp.mpk.krakow.pl). If that doesn't work either, reset your password there or call the MPK S.A. Kraków helpline: +48 12 19 150.

### I found a bug in the app

Report it on [GitHub](https://github.com/mobileKKM/mobile_kkm/issues) or write to [mobilekkm@codebucket.de](mailto:mobilekkm@codebucket.de).
