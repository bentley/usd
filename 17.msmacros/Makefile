ROFF ?= troff
POST ?= grops
SOELIM ?= soelim
PIC ?= pic
TBL ?= tbl

all: msmacros.ps

msmacros.ps: ms fig1.pic
	${SOELIM} $> | ${PIC} | ${TBL} | ${ROFF} -ms | ${POST} > $@
