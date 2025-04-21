CXX = g++
CXXFLAGS = -Iinc -c


all:Lab07

Lab07: main.o Cylinder.o
	$(CXX) main.o Cylinder.o -o Lab07

main.o: main.cpp inc/Cylinder.h
	$(CXX) $(CXXFLAGS) main.cpp

Cylinder.o: src/Cylinder.cpp inc/Cylinder.h
	$(CXX) $(CXXFLAGS) src/Cylinder.cpp

clean:

	rm -rf *.o Lab07
.PHONY: clean all
