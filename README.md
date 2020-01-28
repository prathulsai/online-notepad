# online-notepad
# to execute the command lines and getting the output
import os
stream = os.popen('echo Returned output')
output = stream.read()
output
