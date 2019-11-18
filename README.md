# Week12-utility
**Author:** <Liz Holter>
**Section:** <Section B>

# PrintOutput
def PrintOutput(string):
    print("OUTPUT: ", string)
	
# LoadFile
def LoadFile(filename):
    with open(filename, "r") as f:
        lines = f.readlines()
        print("OUTPUT", lines)
		
#UpdateString
def UpdateString(string1, string2, index):
    return string1[:index] + string2 + string1[index+1]
	
#FindWordCount 
def FindWordCount(user_list, user_string):
    count = user_list.count(user_string)
    return count
	
#ScoreFinder 
def ScoreFinder(players, scores, individual):
    for x in players:
        if individual == x:
            a = players.index(individual)
            print("OUTPUT",x, "got a score of", scores[a])
    else:
        print("OUTPUT player not found")