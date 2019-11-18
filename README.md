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