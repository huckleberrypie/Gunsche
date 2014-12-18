CXX=g++
CXXFLAGS=-O2

all: Gunsche

Gunsche: Gunsche.o
	$(CXX) -o $@ $< -lstdc++

Gunsche.o: Gunsche.cpp
	$(CXX) $(CXXFLAGS) -o $@ -c $<

