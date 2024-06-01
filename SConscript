target = 'ExecDos'

files = Split("""
	execdos.c
""")

resources = Split("""
	execdos.rc
""")

libs = Split("""
	kernel32
	user32
""")

examples = []

docs = Split("""
	Readme.txt
""")

Import('BuildPlugin')

BuildPlugin(target, files, libs, examples, docs, res = resources)
