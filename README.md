# congenial-octo-spork
yep
def mySolution(history):
if len(history) == 0:
return "d"
if len(history) > 0:
check = []
(you, them) = history[-1] #Access the most recent move made by both players. History is always a list of tuples consisting of your move and then your opponent's move.
check.append(them)
if "c" in check:
import random
number = random.randint(1,10)
if number == 10:
return "d"
else:
return "c"
else:
return "d"
