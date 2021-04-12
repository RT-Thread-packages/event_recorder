from building import *

# get current directory
cwd     = GetCurrentDir()
# The set of source files associated with this SConscript file.
src     = Glob('*.c')
path    = [cwd]

group = DefineGroup('event_recorder', src, depend = [''], CPPPATH = path)

Return('group')
