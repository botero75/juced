# Makefile autogenerated by premake
# Don't edit this file! Instead edit `premake.lua` then rerun `make`
# Options:
#   CONFIG=[Debug|Release]

ifndef CONFIG
  CONFIG=Debug
endif

export CONFIG

.PHONY: all clean nekobee

all: nekobee

Makefile: premake.lua
	@echo ==== Regenerating Makefiles ====
	@premake --file $^ --cc gcc --target gnu --os linux

nekobee:
	@echo ==== Building nekobee ====
	@$(MAKE) --no-print-directory -C . -f nekobee.make

clean:
	@$(MAKE) --no-print-directory -C . -f nekobee.make clean
