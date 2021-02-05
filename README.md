# program-to-calculate-square-and-cube
#start program


print('Number\tSquare\tCube')
for number in range(5, 51, 5):
        square = number * number
        cube = number * square
        print(f'{number:7}\t{square:7}\t{cube:7}')
