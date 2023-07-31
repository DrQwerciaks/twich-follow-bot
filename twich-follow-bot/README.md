# auto-twitch-follow-bot
Automatycznie wysyłaj polecenia, aby wysłać obserwujących Twitcha na dowolne konto Twitch. Musisz tylko być na serwerze Discord z botem obserwującym Twitcha!

> :warning: **Ten program używa samodzielnego bota Discorda**: Jest to sprzeczne z TOS Discorda. Używaj tego na własne ryzyko lub wyłącznie w celach edukacyjnych.

## Jak to działa?
Ten bot zaloguje się na twoje konto Discord i będzie wysyłał wiadomości na dowolnym typowym serwerze Twitch follow bot Discord w ustalonych odstępach czasu. Automatycznie zatrzyma się również, gdy osiągnie określoną liczbę obserwujących, którą ustawisz podczas uruchamiania bota.
Aby uruchomić tego bota, musisz dołączyć do serwera Twitch Follow Bot Discord.

## Zrzuty ekranu
![Image 1](https://i.ibb.co/rHfnJmf/Screenshot-2021-11-10-180340.png)\
![Image 2](https://i.ibb.co/F3CftWF/Screenshot-2021-11-10-180321.png)

## Jak to skonfigurować?
- Pobierz pliki [tutaj](https://github.com/thomaskeig/AutoTwitchFollowBot/archive/refs/heads/main.zip) i rozpakuj folder.
- Otwórz wiersz poleceń (lub wiersz poleceń, jeśli używasz systemu Linux) i zainstaluj wymagane pakiety `discord` i `pyyaml`. Można to zrobić za pomocą polecenia `pip install discord && pip install pyyaml` w systemie Windows i `sudo pip install discord && sudo pip install pyyaml` w systemie Linux.
- Otwórz `settings.yml` i zmień ustawienia, aby dostosować je do swoich potrzeb. Jeśli nie korzystasz jeszcze z serwera bota, listę znajdziesz poniżej.
- Uruchom bota otwierając wiersz poleceń w folderze, w którym znajduje się `main.py` i wpisz `python main.py`.
- Zostaniesz zapytany o przybliżoną liczbę obserwujących. Wpisz żądaną liczbę i naciśnij enter. Bot będzie teraz przydzielał ci obserwujących w oparciu o wcześniejsze ustawienia i pokazywał statystyki.

## Ale, czy zamierzasz ukraść mój token Discord?
Nie, po pobraniu plików nie mogę zobaczyć niczego, co zmienisz w pliku. Jeśli mi nie ufasz, zawsze możesz zajrzeć do kodu źródłowego!

## Śledź boty serwerów Discord
Te serwery działają przez prawie 100% czasu:
- https://discord.gg/7hFfJF2WTb
- Napisz do mnie na Twitterze, jeśli znajdziesz więcej (@drqwerciak)

## Samouczki YouTube
Jeśli stworzysz samouczek na YouTube, jak to skonfigurować, napisz do mnie na Twitterze @drqwerciaj, a zostawię tutaj link!