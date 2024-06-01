target = 'ExecDos'

files = Split("""
	execDos.c
""")

resources = Split("""
	execDos.rc
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
