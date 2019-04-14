# linux_pl-for-windows
Polski układ klawiatury programisty przeportowany z Linuxa na Windowsa za pomocą programu [Microsoft Keyboard Layout Creator 1.4][1]
![map]

## Znaki specjalne
Ten układ posiada znacznie więcej znaków specjalnych niż układ z Windowsa, między innymi:

| Próbka |                Nazwa               |                        Skrót                        |
|:------:|:----------------------------------:|:---------------------------------------------------:|
|    „   |  Polski cudzysłów apostrofowy lewy |           <kbd>Alt Gr</kbd> + <kbd>V</kbd>          |
|    ”   | Polski cudzysłów apostrofowy prawy |           <kbd>Alt Gr</kbd> + <kbd>B</kbd>          |
|    –   |              Półpauza              |           <kbd>Alt Gr</kbd> + <kbd>-</kbd>          |
|    —   |                Pauza               | <kbd>Alt Gr</kbd> + <kbd>Shift</kbd> + <kbd>-</kbd> |
|    …   |             Wielokropek            |           <kbd>Alt Gr</kbd> + <kbd>K</kbd>          |

## Generowanie układu klawiatury
Aby wygenerować plik `.exe` do instalacji układu klawiatury, należy:
1. Wybrać w KLC opcję: `File > Load Source File…` lub wcisnąć <kbd>Ctrl</kbd> + <kbd>O</kbd> i wybrać plik `linux_pl.klc`.
2. Wybrać opcję: `Build DLL and Setup Package`

[map]: keyboard.png
[1]: https://www.microsoft.com/en-us/download/details.aspx?id=22339
