
from karel.stanfordkarel import *
     #   move()
      #  paint_corner(BLACK)

def main():
    turn_left()
    move()
    turn_right()
    row_1()
    row_2()
    row_3()
    row_4()
    row_5()
    row_6()
    

def row_1():
    move()
    move()
    for i in range(3):
        paint_corner(BLACK)
        move()
    for i in range(9):
        move()
    for i in range(3):
        paint_corner(BLACK)
        move()
    for i in range(2):
        move()
    turn_left()
    move()
    turn_left()

def row_2():
    for i in range (3):
        move()
    paint_corner(BLACK)
    for i in range(2):
        move()
        paint_corner(PINK)
    move()
    paint_corner(BLACK)
    for i in range(8):
        move()
    paint_corner(BLACK)
    move()
    for i in range(2):
        paint_corner(GREEN)
        move()
    paint_corner(BLACK)
    for i in range (2):
        move()
    turn_right()
    move()
    turn_right()

def row_3():
    for i in range(2):
        move()
    paint_corner(BLACK)
    for i in range(3):
        move()
        paint_corner(GREEN)
    for i in range(2):
        move()
        paint_corner(BLACK)
    for i in range(3):
        move()
    for i in range(2):
        move()
        paint_corner(BLACK)
    for i in range(2):
        move()
        paint_corner(MAGENTA)
    move()
    paint_corner(PINK)
    move()
    paint_corner(BLACK)
    for i in range(3):
        move()
    turn_left()
    move()
    turn_left()

def row_4():
    for i in range(4):
        move()
    paint_corner(BLACK)
    for i in range(2):
        move()
        paint_corner(MAGENTA)
    for i in range(2):
        move()
        paint_corner(BLUE)
    for i in range(3):
        move()
        paint_corner(BLACK)
    move()
    paint_corner(CYAN)
    for i in range(3):
        move()
        paint_corner(GREEN)
    move()
    paint_corner(BLACK)
    for i in range(3):
        move()
    turn_right()
    move()
    turn_right()

def row_5():
    for i in range(3):
        move()
    paint_corner(BLACK)
    move()
    paint_corner(YELLOW)
    for i in range(3):
        move()
        paint_corner(GREEN)
    for i in range(3):
        move()
        paint_corner(CYAN)
    for i in range(3):
        move()
        paint_corner(BLUE)
    move()
    paint_corner(MAGENTA)
    move()
    paint_corner(BLACK)
    turn_left()
    move()
    turn_left()
    move()

def row_6():
    paint_corner(BLACK)
    for i in range(2):
        move()
        paint_corner(BLUE)
    for i in range(3):
        move()
        paint_corner(CYAN)
    for i in range(3):
        move()
        paint_corner(GREEN)
    move()
    paint_corner(YELLOW)

def turn_around():
    for i in range(2):
        turn_left()


def turn_right():
    turn_left()
    turn_left()
    turn_left()
if __name__ == "__main__":
    run_karel_program()
