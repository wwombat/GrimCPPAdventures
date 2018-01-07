CC=gcc
CXX=g++
RM=rm -f
CPPFLAGS=-g -std=c++11 -Wall -Wextra -Werror

SRCS=$(wildcard *.cpp)
OBJS=$(subst .cpp,.o,$(SRCS))

all: build 

build: $(OBJS)
	$(CXX) $(LDFLAGS) -o example.tsk $(OBJS) $(LDLIBS) 

clean:
	$(RM) $(OBJS)

distclean: clean
	$(RM) tool
