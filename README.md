# Linear B input method
Input method based on [ibus](href="https://github.com/phuang/ibus) for the mycenean script of Linear B.

## How to install
1. Install ibus
2. After you clone the repository, run from that folder the following: `sudo ibus-table-createdb -n /usr/share/ibus-table/tables/linearb.db -s linearb.txt` AND `sudo cp linearb.svg /usr/share/ibus-table/icons/`
3. Restart ibus with `ibus-daemon -drx`

Then you can choose Linear B as an input method (usually with Ctrl+Space).

## How to use
You just type the words and the Linear B characters are shown. Those who have used pinyin to type Chinese know exactly what it is meant by the above. So, you can just type wanaka (meaning king) and the three respective characters will show up. There is also the ability to choose among characters. If one types "w" then four choices are listed: "wa", "we", "wi", "wo".
