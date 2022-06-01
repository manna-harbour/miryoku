# Copyright 2022 Manna Harbour
# https://github.com/manna-harbour/miryoku

source := $(wildcard *.png)

targets := $(source:%=social/%)

all: $(targets)

social/%: % FORCE
	convert \
	$< \
	-background none \
	-gravity center  \
	-extent 668x332  \
	$@

FORCE: ;
