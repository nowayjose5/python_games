sudoku game using pygame library

Design -
window with sudoku board, number group, timer, validate button, solve button

sudoku board: user can fill board with numbers. numbers can either be typed or clicked from number group.
                user can click on empty/filled tiles (tile will highlight)
                user can fill empty or change tiles or delete numbers, but not change/mutate originally filled tiles

number group: user can click numbers in this section. number will fill a tile if tile is highlighted.

timer: timer will start as soon as window displays. maybe add a pause/start again button to stop/start up timer again

validate button: user can press validate to check if puzzle is being solved correctly. show a green check for correct
                    puzzle, show red x for invalid puzzle.
                    if board has only the original filled tiles, message will display saying there's nothing to validate
                    if whole board is filled and correct, message will show up showing puzzle solved
                    and time it took to complete
                    messages will display in separate window.

Solve button: if user cannot figure next number, user can click solve button to allow program to solve rest of puzzle.
                look up algorithm for solving sudoku puzzle.
