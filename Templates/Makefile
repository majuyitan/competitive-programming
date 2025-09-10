CXX=g++-14
CXXFLAGS=-std=c++17 -O3 -DNDEBUG -Wall -Wextra -pedantic -Wshadow -Wformat=2 -Wfloat-equal -Wconversion -Wlogical-op -Wshift-overflow=2 -Wduplicated-cond -Wcast-qual -Wcast-align -Wno-unused-result -Wno-sign-conversion

SRCS=tmp.cpp
# OBJS=$(subst .cpp,.o,$(SRCS))

run:
	$(CXX) $(CXXFLAGS) $(LDFLAGS) -o tmp $(SRCS) $(LDLIBS)
	./tmp

clean:
	rm -f *.out *.o tmp
