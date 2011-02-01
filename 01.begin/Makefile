ROFF ?= troff
POST ?= grops

all: begin.ps

begin.ps: u.mac u0 u1 u2 u3 u4 u5
	${ROFF} -ms $> | ${POST} > $@
