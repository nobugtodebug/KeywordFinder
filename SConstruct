#use gprof
#env2 = Environment(CCFLAGS='-w -W -Wall -g -pg -std=c++0x -finput-charset=utf-8', LINKFLAGS='-pg')

env2 = Environment(CCFLAGS='-w -W -Wall -g -std=c++0x -finput-charset=utf-8', LIBS=["iconv"])
env2.Program('test',['test.cpp','keywordfinder.cpp'],CPPPATH=[".", "/usr/local/include"], LIBPATH='/usr/local/lib')

