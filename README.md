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