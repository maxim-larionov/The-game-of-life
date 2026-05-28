# The game of life
It's just popular game that was created by _John Conway_.  
In this game you can make some cells __alife__, and they'll change liveliness by this __rules__:

- If there are __2 or 3__ _living_ cells nearby, the cell __survives__; a dead cell begins to live if there are __3__ cells nearby.
- If there are __fewer than 2__ living cells, the living cell __dies__ of _loneliness_, but if there are __more than 3__, the cell __dies__ of _overcrowding_.
  
## base controls (find more controls in code)
- Left button of mouse: change cell's liveliness
- Right buttonof mouse: set cursor
- Shift: change cell's liveliness with cursor
- Arrows: move cursor
- R: run simulation
- S: do 1 step
- C: make all cells liveless, clear the field
## to install
### you must run
<code>
git clone https://github.com/maxim-larionov/The-game-of-life
pip3 install numpy pygame
</code>

## to use
### run
<code>
cd The-game-of-life
python3 main.py
</code>

# Get fun!
