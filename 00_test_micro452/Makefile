# MPLAB IDE generated this makefile for use with GNU make.
# Project: test_micro452.mcp
# Date: Wed Oct 05 01:54:19 2011

AS = MPASMWIN.exe
CC = mcc18.exe
LD = mplink.exe
AR = mplib.exe
RM = rm

test_micro452.cof : test_micro452.o
	$(LD) /p18F87J11 "test_micro452.o" /u_CRUNTIME /u_DEBUG /z__MPLAB_BUILD=1 /z__MPLAB_DEBUG=1 /o"test_micro452.cof" /M"test_micro452.map" /W

test_micro452.o : test_micro452.c ../../../../../Program\ Files\ (x86)/Microchip/mplabc18/v3.40/h/p18f452.h
	$(CC) -p=18F87J11 "test_micro452.c" -fo="test_micro452.o" -D__DEBUG -Ou- -Ot- -Ob- -Op- -Or- -Od- -Opa-

clean : 
	$(RM) "test_micro452.o" "test_micro452.cof" "test_micro452.hex"

