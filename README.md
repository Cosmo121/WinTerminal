# WinTerminal

Does what it do. My personal setup for Windows Terminal applicaiton.

## Usage
Change the backgroundImage property to whatever you want, or leave it off entirely.
```JSON
"backgroundImage": "C:\\users\\mhartman\\downloads\\21864ab.gif"
```
If the style is burning your eyeballs, remove the retro terminal effect.

```JSON
"experimental.retroTerminalEffect": true
```
Retro schema:
```JSON
    "schemes": [
        {
            "name": "Retro",
            "background": "#000000",
            "black": "#00ff00",
            "blue": "#00ff00",
            "brightBlack": "#00ff00",
            "brightBlue": "#00ff00",
            "brightCyan": "#00ff00",
            "brightGreen": "#00ff00",
            "brightPurple": "#00ff00",
            "brightRed": "#00ff00",
            "brightWhite": "#00ff00",
            "brightYellow": "#00ff00",
            "cyan": "#00ff00",
            "foreground": "#00ff00",
            "green": "#00ff00",
            "purple": "#00ff00",
            "red": "#00ff00",
            "white": "#00ff00",
            "yellow": "#00ff00"
        }
```

Documentation: https://docs.microsoft.com/en-us/windows/terminal/custom-terminal-gallery/custom-schemes


## License
MIT License

(c) 2020 Mike Hartman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
