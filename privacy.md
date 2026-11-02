# Polityka prywatności bota Wyspiarz

*Ostatnia aktualizacja: 2 listopada 2026*

> English version below.

Ta polityka opisuje, jakie dane zbiera bot Discord Wyspiarz („Bot”), prowadzony przez xdeush („Operator”), w jakim celu i jak długo je przechowuje.

## 1. Jakie dane zbieramy

**Identyfikatory Discord.** Bot zapisuje ID użytkowników (liczbowe identyfikatory Discord), żeby przypisać do nich dane opisane niżej. Nie zapisujemy adresów e-mail, haseł, numerów telefonów ani adresów IP.

**Dane ekonomii i gier:** saldo, ekwipunek, wirtualne „akcje” i „kryptowaluty”, historia transakcji w grze, serie i czasy ostatnich nagród (np. daily/work), czas odnowienia gier, trwające rozgrywki (np. blackjack), ustawienie widoczności salda oraz zakupy w sklepie.

**Aktywność na kanałach głosowych.** Bot sprawdza, kto jest na kanale głosowym, żeby naliczać wirtualną walutę za aktywność. Bot **nie nagrywa ani nie odsłuchuje** dźwięku.

**Dane eventów:** punkty i przedmioty zebrane w eventach sezonowych (np. Halloween, Święta).

**Role czasowe:** kto, komu i jaką rolę przyznał oraz kiedy rola wygasa.

**Archiwum GIF-ów i kanał pomysłów:** ID autora, ID kanału i wiadomości oraz czas dodania (bez treści wiadomości), żeby uniknąć duplikatów i zarządzać wpisami.

**Wykrywanie multikont (moderacja).** Regulamin serwera zakazuje multikont, dlatego Operator korzysta z osobnego narzędzia, które działa na tokenie Bota i czyta historię kanałów dostępnych dla Bota. Dla każdej wiadomości z ostatnich 180 dni zapisuje ID autora, czas, kanał oraz ID osoby, której odpowiedziano lub którą oznaczono. Odpowiedź Bota na komendę liczy jako aktywność osoby, która ją wywołała. Podczas sprawdzania konta narzędzie pobiera też jego nazwę, nick, avatar i datę dołączenia, ale ich nie zapisuje. Ocena nie korzysta z nazw ani avatarów.

## 2. Treść wiadomości

Bot **nie ma dostępu do treści zwykłych wiadomości** na serwerze. Discord udostępnia mu tylko treść wiadomości, w których Bot został oznaczony (używane przez asystenta AI, patrz punkt 3). Wiadomości do moderacji na kanale purgatory są wysyłane komendą `/purgatory`. **Bot nie zapisuje treści wiadomości** w żadnej bazie danych. Narzędzie do wykrywania multikont również nie czyta ani nie zapisuje treści.

## 3. Asystent AI (Google Gemini)

Gdy uprawniona osoba oznaczy Bota, żeby zadać mu pytanie, Bot wysyła do **Google Gemini API**:
- treść tej wiadomości,
- nazwę użytkownika osoby pytającej i nazwę kanału.

Google przetwarza te dane zgodnie z [warunkami Gemini API](https://ai.google.dev/gemini-api/terms). Bot nie zapisuje tych rozmów.

## 4. Dane członków serwera

Bot korzysta z listy członków serwera, żeby wysyłać wiadomości powitalne, liczyć członków, sprawdzać role (np. dostęp do asystenta AI lub do funkcji ekonomii) oraz zarządzać rolami. Lista członków i ich profile służą też do wykrywania multikont (punkt 1). Bot nie zbiera danych o statusie online ani aktywności (presence).

## 5. Do czego używamy danych

Dane służą wyłącznie do działania funkcji Bota i do moderacji serwera. **Nie sprzedajemy ich, nie udostępniamy reklamodawcom i nie używamy ich do reklam.** Jedynym zewnętrznym podmiotem, który dostaje jakiekolwiek dane, jest Google (patrz punkt 3).

**Profilowanie na potrzeby moderacji.** Narzędzie do wykrywania multikont porównuje czas pisania, kanały oraz daty założenia kont i dołączenia na serwer, a potem wylicza ocenę, czy dwa konta mogą należeć do jednej osoby. Jest to profilowanie. Podstawą jest prawnie uzasadniony interes Operatora (art. 6 ust. 1 lit. f RODO), czyli egzekwowanie regulaminu serwera. Ocena to poszlaka, a nie dowód: narzędzie nie nakłada kar automatycznie, a decyzję podejmuje człowiek. Wyniki widzi tylko Operator.

## 6. Przechowywanie i bezpieczeństwo

Dane są przechowywane w plikach na serwerze Operatora. Kopie zapasowe danych ekonomii tworzy się automatycznie co kilka godzin. Dane przechowujemy, dopóki Bot działa lub dopóki nie poprosisz o ich usunięcie. Dane do wykrywania multikont są zapisane w pliku na komputerze Operatora, a wpisy starsze niż 180 dni są usuwane przy kolejnym uruchomieniu narzędzia. Dane kopii zapasowych są regularnie usuwane.

## 7. Twoje prawa

Możesz poprosić o wgląd w swoje dane albo o ich usunięcie, kontaktując się z Operatorem (punkt 9). Usunięcie danych oznacza utratę postępu w ekonomii i eventach. Jeśli przebywasz w UE, przysługują Ci także prawa wynikające z RODO, w tym prawo do sprzeciwu wobec profilowania na potrzeby moderacji oraz prawo do złożenia skargi do organu nadzorczego (w Polsce: Prezes UODO).

## 8. Dzieci

Bot jest przeznaczony dla osób, które spełniają minimalny wiek wymagany przez Discord w ich kraju.

## 9. Kontakt

Napisz do właściciela bota (xdeush) na serwerze Discord: https://discord.gg/BPFGNPeUWz lub e-mailem: xDeushcontact@protonmail.com

## 10. Zmiany

Operator może aktualizować tę politykę. Datę aktualizacji podaje się na górze dokumentu.

---

# Wyspiarz Privacy Policy

*Last updated: 2 November 2026*

This policy explains what data the Discord bot Wyspiarz (“the Bot”), operated by xdeush (“the Operator”), collects, why, and how long it is kept.

## 1. Data we collect

**Discord IDs.** The Bot stores user IDs (numeric Discord identifiers) to link the data below to users. We do not store e-mail addresses, passwords, phone numbers or IP addresses.

**Economy and game data:** balance, inventory, virtual “stocks” and “crypto”, in-game transaction history, streaks and last reward times (e.g. daily/work), game cooldowns, ongoing games (e.g. blackjack), balance visibility setting and shop purchases.

**Voice channel activity.** The Bot checks who is in a voice channel to award virtual currency for activity. The Bot **does not record or listen to** audio.

**Event data:** points and items collected in seasonal events (e.g. Halloween, Christmas).

**Temporary roles:** who granted which role to whom, and when it expires.

**GIF archive and ideas channel:** author ID, channel and message IDs and timestamp (no message text), used to prevent duplicates and manage entries.

**Multi-account detection (moderation).** The server rules prohibit multiple accounts, so the Operator uses a separate tool that runs on the Bot's token and reads the history of channels the Bot can access. For each message from the last 180 days it stores the author's ID, the time, the channel and the ID of the person replied to or mentioned. A Bot reply to a command counts as activity of the person who ran that command. When checking an account, the tool also fetches its username, nickname, avatar and join date, but does not store them. The rating does not use usernames or avatars.

## 2. Message content

The Bot **does not have access to the content of regular messages** on the server. Discord only provides it with the content of messages that mention the Bot (used by the AI assistant, see section 3). Messages to moderators in the purgatory channel are sent with the `/purgatory` command. **The Bot does not store message content** in any database. The multi-account detection tool also does not read or store content.

## 3. AI assistant (Google Gemini)

When an authorized user mentions the Bot to ask a question, the Bot sends to the **Google Gemini API**:
- the content of that message,
- the asking user’s username and the channel name.

Google processes this data under the [Gemini API terms](https://ai.google.dev/gemini-api/terms). The Bot does not store these conversations.

## 4. Server member data

The Bot uses the server member list to send welcome messages, count members, check roles (e.g. access to the AI assistant or economy features) and manage roles. The member list and profiles are also used for multi-account detection (section 1). The Bot does not collect online status or activity (presence) data.

## 5. How we use data

Data is used only to run the Bot’s features and to moderate the server. **We do not sell it, share it with advertisers or use it for advertising.** The only third party that receives any data is Google (see section 3).

**Profiling for moderation.** The multi-account detection tool compares posting times, channels, account creation dates and server join dates, then calculates a rating of whether two accounts may belong to one person. This is profiling. Its legal basis is the Operator’s legitimate interest (Article 6(1)(f) GDPR) in enforcing the server rules. The rating is an indication, not proof: the tool does not impose penalties automatically, and a person makes the decision. Only the Operator sees the results.

## 6. Storage and security

Data is stored in files on the Operator’s server. Economy data is backed up automatically every few hours. Data is kept while the Bot is running or until you request deletion. Multi-account detection data is stored in a file on the Operator’s computer, and entries older than 180 days are removed the next time the tool runs. Backups are removed regularly.

## 7. Your rights

You can request access to or deletion of your data by contacting the Operator (section 9). Deletion means losing your economy and event progress. If you are in the EU, you also have rights under the GDPR, including the right to object to profiling for moderation and the right to lodge a complaint with a supervisory authority.

## 8. Children

The Bot is intended for users who meet Discord’s minimum age requirement in their country.

## 9. Contact

Contact the bot owner (xdeush) on the Discord server: https://discord.gg/BPFGNPeUWz or via e-mail: xDeushcontact@protonmail.com

## 10. Changes

The Operator may update this policy. The date at the top shows the latest version.
