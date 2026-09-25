## Miksi UNIX kirjoitettiin uudelleen c-ohjelmointikielellä? 
- Eri laitteistojärjestelmien välinen siirtyminen helpottui.

## Mikä tärkeä GNU-komponentti ei ollut valmis, kun Linux tuli saataville?
- Sen oma (käyttöjärjestelmän ydin/kernel) GNU hurd ei ollut valmis yleiseen käyttöön 

## Mikä vastuualue kuuluu käyttöjärjestelmän ytimelle?
- Ydin hallitsee käyttöjärjestelmäresursseja mm. suoritinta, muistia ja oheislaitteita.


## Mikä on Linux?
- Kernel on käyttöjärjestelmän ydin joka toimii siltanan eri laitteiston ja ohjelmistojen välillä, se hallinnoi suoritinta, muistia ja liitettyjälaitteita. 
- käyttöjärjestelmä = ydin (Linux) + työkalut ja ohjelmat (GNU)

## Mikä Linux-järjestelmän pääosa hallitsee laitteistoa?
- Linux Kernel/Ydin

## Mikä on jakelu/ linux-distro?
- Se on täydellinen käyttöjärjestelmä joka on rakennettu Linux-kernelin ympärille.
- Jakelu = Linux-ydin + järjestelmätyökalut + sovellukset + pakettienhallinta.
- Eri Linux-jakelut tekevät erilaisia ​valintoja vakauden, ohjelmistojen tuoreuden, työpöytäkokemuksen, pakettienhallinnan, tuen ja järjestelmäfilosofian suhteen.

## Jakeluperheet
| Perhe | Esimerkkejä | Pakettienhallinta | Missä käytetään |
| --- | --- | --- | --- |
| Debian | Debian, Ubuntu, Linux Mint | apt (pohjalla dpkg) | Palvelimet ja pilvi, työpöydät; vakaa ja konservatiivinen |
| Red Hat | RHEL, Fedora, Rocky Linux, Amazon Linux | dnf (vanhemmissa yum, pohjalla rpm) | Yritysten palvelimet, maksullinen tuki (RHEL); Fedora kokeilee uusimmat ominaisuudet ensin |

## Mikä on Debianin APT-työkalupakin päätarkoitus?
- Asenna, päivitä, poista ja hallinnoin ohjelmistopaketteja



## Minun koneeni
(aja `cat /etc/os-release` ja kirjoita, mikä jakelu ja versio sinulla on)
- Minulla on Ubuntu jakelu ja versio on: 24.04.4 LTS

