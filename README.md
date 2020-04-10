# consoledesigner
Library positional like gotoXY 

from consoledesigner.ConsoleDesingner import ConsoleDesingner, Colors


cd = ConsoleDesingner()

c = Colors

cd.clear()
cd.goto_xy(2, 10, c.GREEN + c.ITALIC, 'testes')

print('teste')
