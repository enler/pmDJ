bin_PROGRAMS = smdDump smd2mid pmDJ smdInfo swdDump
noinst_PROGRAMS = checkSmds easyName
check_PROGRAMS = test_midiFile test_smdFile test_smdMidi
smdDump_SOURCES = smdDump.cpp smdFile.cpp
smd2mid_SOURCES = smd2mid.cpp smdFile.cpp midiFile.cpp instMap.cpp smdMidi.cpp
smdInfo_SOURCES = smdInfo.cpp smdFile.cpp
pmDJ_SOURCES = pmDJ.cpp smdFile.cpp midiFile.cpp instMap.cpp smdMidi.cpp
checkSmds_SOURCES = checkSmds.cpp smdFile.cpp
swdDump_SOURCES = swdDump.cpp swdFile.cpp
easyName_SOURCES = easyName.cpp
test_midiFile_SOURCES = midiFile__test.cpp midiFile.cpp
test_midiFile_LDADD = -ltap++
test_smdFile_SOURCES = smdFile__test.cpp smdFile.cpp
test_smdFile_LDADD = -ltap++
test_smdMidi_SOURCES = smdMidi__test.cpp smdMidi.cpp midiFile.cpp smdFile.cpp instMap.cpp
test_smdMidi_LDADD = -ltap++
noinst_HEADERS = instMap.hpp midiFile.hpp smdFile.hpp smdMidi.hpp swdFile.hpp

AM_CXXFLAGS=-DPKGDIR=\"$(top_srcdir)\"
TESTS = test_midiFile test_smdFile test_smdMidi
EXTRA_DIST = drum_table.txt prog_table.txt README.md test_data/totaka.mid test_data/bgm0020.smd test_data/bgm0020.mid
