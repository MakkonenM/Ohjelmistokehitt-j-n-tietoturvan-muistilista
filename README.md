# Ohjelmistokehittajan-tietoturvan-muistilista
## Koodauksen periaatteet

Älä kovakoodaa salasanoja tai API-avaimia koodiin.

Hyödynnä muuttujia ja salasanahallintaa.

Varmista, että koodi noudattaa turvallisen ohjelmoinnin periaatteita (esim. OWASP Top 10).

## Tunnistautuminen ja valtuutus

Käytä vahvoja salasanakäytäntöjä.

Hyödynnä monivaiheista tunnistautumista (MFA).

Toteuta asianmukaiset oikeustasot ja roolit.

## Tiedonhallinta ja tietojen suojaus

Salaa arkaluonteiset tiedot (sekä levossa että siirrossa).

Käytä turvallisia salausalgoritmeja (AES-256, RSA, SHA-256).

Minimoi tietojen tallennus - älä säilytä turhia tietoja.

## Tietoturvatestaukset ja auditoinnit

Suorita säännölliset koodianalyysit ja tietoturvatarkastukset.

Käytä työkaluja, kuten OWASP ZAP, Burp Suite ja SonarQube.

Tee haavoittuvuustestauksia (penetration testing, fuzz testing).

## Riippuvuuksien hallinta

Päivitä kirjastot ja paketit säännöllisesti.

Vältä tarpeettomia riippuvuuksia.

Käytä turvallisuusratkaisuja, kuten Dependabot ja Snyk.

## Verkkoturvallisuus

Varmista, että verkkopyynnöt ovat suojattuja (HTTPS, TLS 1.2+).

Suojaa API-rajapinnat (Rate limiting, API-avaimet, OAuth 2.0).

Suodata ja validoi käyttäjän syötteet (SQL Injection, XSS, CSRF).

## Lokitus ja valvonta

Toteuta lokitus, mutta älä tallenna arkaluonteisia tietoja lokeihin.

Monitoroi tietoturvahälytyksiä ja analysoi poikkeamat.

Käytä keskitettyä lokienhallintaa (SIEM, ELK Stack, Splunk).

## Käyttöönotto ja ylläpito

Rajoita palvelimien ja pilvipalveluiden käyttöoikeudet.

Automatisoi tietoturvapaikkaukset.

Hyödynnä infrastruktuurin koodina (IaC) -periaatteita.

## Häiriötilanteiden hallinta

Luo ja testaa tietoturvaan liittyvät varasuunnitelmat.

Harjoittele tietomurtoihin reagointia.

Toteuta varmuuskopiointiprosessit ja testaa niiden toimivuus.

## Käyttäjä- ja työntekijätietoturva

Kouluta kehittäjiä tietoturvakäytännöistä.

Tiedota käyttäjiä turvallisista toimintatavoista.

Seuraa ja noudata tietoturvalainsäädäntöä (GDPR, ISO 27001).
