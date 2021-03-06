#############################################################################
# Makefile for building: ../../lib/libosessame_datahandling.a
# Generated by qmake (1.02a) on: Sat Oct 18 17:32:57 2003
# Project:  datahandling.pro
# Template: lib
# Command: $(QMAKE) datahandling.pro
#############################################################################

####### Compiler, tools and options

CC       = gcc
CXX      = g++
LEX      = flex
YACC     = yacc
CFLAGS   = -pipe -Wall -W -g  
CXXFLAGS = -pipe -Wall -W -g  
LEXFLAGS = 
YACCFLAGS= -d
INCPATH  = -I../matrix -I../rotation -I../attitude -I../orbit -I../datahandling -I../dynamics -I../environment -I.. -I$(QTDIR)/mkspecs/default
AR       = ar cqs
RANLIB   = 
MOC      = $(QTDIR)/bin/moc
UIC      = $(QTDIR)/bin/uic
QMAKE    = qmake
TAR      = tar -cf
GZIP     = gzip -9f
COPY     = cp -f
COPY_FILE= $(COPY) -p
COPY_DIR = $(COPY) -pR
DEL_FILE = 
DEL_DIR  = 
MOVE     = mv

####### Output directory

OBJECTS_DIR = ../../objects/

####### Files

HEADERS = AttitudeHistory.h \
		History.h \
		OrbitHistory.h
SOURCES = AttitudeHistory.cpp \
		History.cpp \
		OrbitHistory.cpp
OBJECTS = ../../objects/AttitudeHistory.o \
		../../objects/History.o \
		../../objects/OrbitHistory.o
FORMS = 
UICDECLS = 
UICIMPLS = 
SRCMOC   = 
OBJMOC = 
DIST     = 
QMAKE_TARGET = osessame_datahandling
DESTDIR  = ../../lib/
TARGET   = ../../lib/libosessame_datahandling.a

first: all
####### Implicit rules

.SUFFIXES: .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o $@ $<

####### Build rules

all: Makefile $(TARGET)

staticlib: $(TARGET)

$(TARGET): $(UICDECLS) $(OBJECTS) $(OBJMOC) 
	test -d ../../lib/ || mkdir -p ../../lib/
	-rm -f $(TARGET)
	$(AR) $(TARGET) $(OBJECTS) $(OBJMOC)
	

mocables: $(SRCMOC)

$(MOC): 
	( cd $(QTDIR)/src/moc ; $(MAKE) )

Makefile: datahandling.pro  $(QTDIR)/mkspecs/default/qmake.conf 
	$(QMAKE) datahandling.pro
qmake: 
	@$(QMAKE) datahandling.pro

dist: 
	@mkdir -p ../../objects/osessame_datahandling && $(COPY_FILE) --parents $(SOURCES) $(HEADERS) $(FORMS) $(DIST) ../../objects/osessame_datahandling/ && ( cd `dirname ../../objects/osessame_datahandling` && $(TAR) osessame_datahandling.tar osessame_datahandling && $(GZIP) osessame_datahandling.tar ) && mv `dirname ../../objects/osessame_datahandling`/osessame_datahandling.tar.gz . && rm -rf ../../objects/osessame_datahandling

uiclean:

clean:
	-rm -f $(OBJECTS) 
	-rm -f *~ core *.core


####### Sub-libraries

distclean: clean
	-rm -f ../../lib/$(TARGET) $(TARGET)
	

FORCE:

####### Compile

../../objects/AttitudeHistory.o: AttitudeHistory.cpp AttitudeHistory.h \
		../rotation/Rotation.h \
		../attitude/AttitudeState.h \
		History.h \
		../matrix/Matrix.h \
		../matrix/cammva.h \
		../matrix/dmatrix.h \
		../matrix/dvector.h \
		../matrix/darray.h \
		../matrix/strctbse.h \
		../matrix/datahndl.h \
		../matrix/matbse.h \
		../matrix/vecbse.h \
		../matrix/range.h \
		../matrix/camtype.h \
		../matrix/under.h \
		../matrix/mvaimpexp.h \
		../matrix/mvalngbase.h \
		../matrix/access.h \
		../matrix/mvaexit.h \
		../matrix/typehndl.h \
		../matrix/arraybse.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../objects/AttitudeHistory.o AttitudeHistory.cpp

../../objects/History.o: History.cpp History.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../objects/History.o History.cpp

../../objects/OrbitHistory.o: OrbitHistory.cpp OrbitHistory.h \
		../matrix/Matrix.h \
		../rotation/Rotation.h \
		History.h \
		../orbit/OrbitState.h \
		../orbit/orbitstaterep/PositionVelocity.h \
		../matrix/cammva.h \
		../matrix/dmatrix.h \
		../matrix/dvector.h \
		../matrix/darray.h \
		../matrix/strctbse.h \
		../matrix/datahndl.h \
		../matrix/matbse.h \
		../matrix/vecbse.h \
		../matrix/range.h \
		../matrix/camtype.h \
		../matrix/under.h \
		../matrix/mvaimpexp.h \
		../matrix/mvalngbase.h \
		../matrix/access.h \
		../matrix/mvaexit.h \
		../matrix/typehndl.h \
		../matrix/arraybse.h \
		../orbit/orbitframes/OrbitFrame.h \
		../orbit/orbitstaterep/OrbitStateRepresentation.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../objects/OrbitHistory.o OrbitHistory.cpp

####### Install

install: all 

uninstall: 

