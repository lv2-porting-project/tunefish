Instructions to build LV2:

make -C src/tunefish4/Builds/LinuxMakefile -f Makefile.LV2 CONFIG=Release
cp src/tunefish4/Builds/LinuxMakefile/build/Tunefish4.so lv2/Tunefish4.lv2/
