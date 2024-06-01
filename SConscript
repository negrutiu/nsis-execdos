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

docs = Split("""
	Readme.txt
""")

Import('BuildPlugin')

BuildPlugin(target, files, libs, docs = docs, res = resources)
