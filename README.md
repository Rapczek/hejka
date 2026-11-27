# LS

Strona do udostępniania tekstu i plików po kodzie (Firebase Firestore, hosting statyczny).

## Pliki
- `index.html` - cała strona (HTML, CSS, JS w jednym pliku)
- `firestore.rules` - reguły bazy, wklejasz je w konsoli Firebase

## Uruchomienie
1. Utwórz projekt na https://console.firebase.google.com, dodaj aplikację Web i skopiuj `firebaseConfig`.
2. Build -> Firestore Database -> Create database (tryb production).
3. Firestore -> Rules -> wklej zawartość `firestore.rules` -> Publish.
4. W `index.html` podmień `PASTE_HERE` na wartości z configu.
5. Wrzuć na GitHub Pages (Settings -> Pages -> Deploy from a branch -> main / root).

## Limity
- plik do 9 MB, tekst do ok. 100 KB, do 100 otwarć
- licznik otwarć nie jest w pełni wiążący (patrz uwagi w rozmowie): kod zna każdy, kto go ma
