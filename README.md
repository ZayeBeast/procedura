# Procedura
1. Organizatorem konkursu jest [Nircek](https://github.com/Nircek).
2. Organizator zastrzega sobie prawo do zmiany zasad konkursu.
3. Konkurs polega na przejściu kolejnych punktów:
 - posiadanie konta na GitHubie z powiązanym e-mailem
 - poprawne skonfigurowanie Gita oraz GPG zgodnie z [tymi](https://github.com/Zayebeast/labirynt/blob/master/git-komendy.md) i [tymi](https://github.com/Zayebeast/labirynt/blob/master/gpg-komendy.md) instrukcjami
 - sforkowanie tego repo
 - stworzenie pliku *.html (wszystko ma być w jednym pliku), który po uruchomieniu w przeglądarce:
   - w jakiś sposób poprosi użytkownika o dane wejściowe (tekst)
   - przetworzy te dane zgodnie z [algorytmem CRY (NR4C-6)](https://github.com/Nircek/NR4C/blob/master/6/nr4c-6.txt)
   - wyświetli zwrócony ciąg zakodowany w Base64 i wyświetli na ekran
   - będzie podawał takie same wyniki jak przykładowe implementacje zawarte w NR4C-6
 - zaszyfrowanie oraz podpisanie swojego pliku z rozwiązaniem za pomocą GPG na klucz podany przez Organizatora
 - stworzenie commita (żeby GitHub wyświetlał go jako "Verified" + był podpisany Tw kluczem GPG) na swoim forku z zaszyfrowanym rozwiązaniem w pliku `<Twój nick>.rozwiązanie.txt` oraz Twoim kluczem prywatnym w pliku `<Twój nick>.klucz.txt`
 - spushowanie commita na swojego forka
 - stworzenie Pull Requesta ze swojego forka do repo Zayebeast/procedura
4. Organizator zamieści swoje rozwiązanie, a następnie udostępni klucz do szyfrowania rozwiązań w pliku klucz.pub.txt
5. W momencie skończenia trwania konkursu (tj 2018-12-30T21:00+01:00) Organizator udostępni klucz prywatny i tym samym każda osoba będzie mogła odszyfrować rozwiązania innych
6. Rozwiązania po skończoniu konkursu nie będą rozpatrywane
