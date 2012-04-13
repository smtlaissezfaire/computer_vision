CPP = g++
LIBS = -lopencv_core -lopencv_highgui -lopencv_imgproc -lopencv_video

ODIR = obj
BDIR = bin

all: skindetect

skindetect: camshiftdemo.cpp
	$(CPP) $(CFLAGS) -o skindetect $(LIBS) camshiftdemo.cpp

clean:
	rm -rf skindetect

.PHONY: clean all

