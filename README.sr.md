<a href="https://www.hotelpansionzapse.com/"><img src="media/cover.jpg" alt="Golden Pets Hotel, naslovna strana na laptopu i telefonu" width="100%"></a>

# Golden Pets Hotel

Nov sajt za beogradski pansion za pse malih rasa, prenet sa WordPress-a iz 2019. godine, uz rešenje za svaku od 139 starih adresa.

**[hotelpansionzapse.com](https://www.hotelpansionzapse.com/)** · [Studija slučaja](https://svilenkovic.rs/radovi/golden-pets-hotel) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Golden Pets Hotel</td></tr>
  <tr><td><b>Delatnost</b></td><td>Pansion za pse malih rasa</td></tr>
  <tr><td><b>Lokacija</b></td><td>Beograd</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt sa više strana</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Redizajn, izrada, selidba, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, nginx, WebP, JSON-LD</td></tr>
</table>

## O projektu

Golden Pets Hotel čuva pse do 15 kg u kući sa ograđenim dvorištem umesto u boksovima, uz nadzor 24 sata. Stari sajt je bio WordPress zamrznut u 2019. godini, složen u page builder dodatku koji je povučen zbog bezbednosnog propusta, pa se uopšte nije mogao ažurirati. Vlasnik nije želeo online rezervacije ni kontakt formu: ljudi treba da pozovu, jer pansion pre svake potvrde pita za psa.

Stari sajt je u indeksu imao 139 poznatih adresa, a to je jedino što prelazak na nov sajt može da uništi za jedan dan. Glavne strane su zadržale stare putanje, 82 stare adrese preusmerene su preko mape na serveru, a za 76 ostataka, poput demo proizvoda iz prodavnice i prazne jezičke grane, server sada vraća 410 umesto preusmerenja na naslovnu. Posle prelaska sam svaku od njih proverio na živom domenu.

## Šta sam uradio

- Naslovna i četiri strane (o pansionu, galerija, novosti, kontakt), a cene, radno vreme i kontakt podaci stoje u jednom fajlu
- Ispravljeni linkovi za poziv, pošto se pokazalo da je svaki `tel:` link zvao broj bez poslednje cifre
- Cenovnik sa tri paketa i napomenom o popustu, gde svaki paket sada ima svoju jedinicu cene
- Galerija sa 16 od 28 fotografija koje je klijent poslao, sve sa psom, a cela mreža ima oko 210 KB
- Nijedan zahtev ka tuđem serveru: bez analitike, piksela, ugrađenih mapa i spoljnih fontova, pa ni traka za pristanak nije potrebna
- Uz sajt su prešli i domen i sanduče, sa nekoliko stotina poruka, a klijent nije morao da menja lozinku

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 100 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, septembar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `LocalBusiness`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Golden Pets Hotel, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Golden Pets Hotel, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Sekcija &quot;Vi planirate put, mi brinemo o psu&quot; sa pozivom na obilazak">
<sub>Sekcija "Vi planirate put, mi brinemo o psu" sa pozivom na obilazak</sub>

<img src="media/inner-2.webp" alt="Dodatne usluge, odmah iznad cenovnika">
<sub>Dodatne usluge, odmah iznad cenovnika</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
