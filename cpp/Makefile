format:
	clang-format -i stack-linked-list.cpp conio.h

%.out: %.cpp
	clang++ $< -o $@

build:	$(addsuffix .out, $(basename $(wildcard *.cpp)))

.DEFAULT_GOAL := build
