**Helsingin Yliopiston** kurssi ohjelmistotekniikka (5 ECTS)

# TypingTest

Sovelluksella voit testata kirjoitusnopeutta, antaen tilastoja reaaliajassa. Sovellus myös tarjoaa yleisen kuvan tilastoista, jolla käyttäjä voi verrata edistymistään.

## Dokumentaatio

[Käyttöohje](/dokumentaatio/k%C3%A4ytt%C3%B6ohje.md)

[Vaatimuusmäärittely](/dokumentaatio/vaatimusm%C3%A4%C3%A4rittely.md)

[Arkkitehtuurikuvaus](/dokumentaatio/arkkitehtuuri.md)

[Testausdokumentti](/dokumentaatio//testausdokumentti.md)

[Työaikakirjanpito](/dokumentaatio/ty%C3%B6aikakirjanpito.md)

[Changelog](/dokumentaatio/changelog.md)

## Asennus

1. Asenna riippuvuudet TypingTest-kansiossa komennolla:

``poetry install``

2. Alusta sovellus komennolla:

``poetry run invoke build``

3. Käynnistä sovellus komennolla

``poetry run invoke start``

## Komentorivitoiminnot

### Ohjelman suorittaminen

Ohjelman pystyy suorittamaan komennolla:

``poetry run invoke start``

### Testaus

Testit suoritetaan komennolla

``poetry run invoke test``

### Testikattavuus

Testikattavuus generoidaan komennolla

``poetry run invoke coverage-report``

### Pylint

Tiedoston [.pylintrc](./TypingTest/.pylintrc) määritelmät tarkistukset onnistuu komennolla:

``poetry run invoke lint``


