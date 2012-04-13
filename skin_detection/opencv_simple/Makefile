CPP = g++
LIBS = -lopencv_core -lopencv_highgui -lopencv_imgproc

ODIR = obj
BDIR = bin

all: skindetect

skindetect: calcBackProject_Demo1.cpp
	$(CPP) $(CFLAGS) -o skindetect $(LIBS) calcBackProject_Demo1.cpp

clean:
	rm -rf skindetect

.PHONY: clean all

