petdir = $(VICEDIR)/PET

roms = \
	basic1 \
	basic2 \
	basic4 \
	kernal1 \
	kernal2 \
	kernal4 \
	edit1g \
	edit2g \
	edit2b \
	edit4g40 \
	edit4b40 \
	edit4b80 \
	chargen \
	chargen.de

romsets = \
	rom1g.vrs \
	rom2b.vrs \
	rom2g.vrs \
	rom4b40.vrs \
	rom4b80.vrs \
	rom4g40.vrs

palettes = \
	amber.vpl \
	green.vpl \
	white.vpl

x11_keymaps = \
	x11_bdep.vkm \
	x11_bdep_de.vkm \
	x11_bdes.vkm \
	x11_bdes_de.vkm \
	x11_bgrp.vkm \
	x11_bgrp_de.vkm \
	x11_bgrs.vkm \
	x11_bgrs_de.vkm \
	x11_bukp.vkm \
	x11_bukp_de.vkm \
	x11_buks.vkm \
	x11_buks_de.vkm

sdl_keymaps = \
	sdl_buks.vkm \
	sdl_bgrs.vkm

extra_keymaps = \
	amiga_bgrs.vkm \
	amiga_buks.vkm \
	beos_bgrs.vkm \
	beos_buks.vkm \
	dos_bgrs.vkm \
	dos_buks.vkm \
	os2.vkm \
	os2_40.vkm \
	osx_sym_gr.vkm \
	osx_sym_uk.vkm \
	RObusi.vkm \
	ROgrph.vkm \
	win_sym_gr.vkm \
	win_sym_uk.vkm

win32_files = \
	win_hotkeys.vhk \
	win_shortcuts.vsc

if SDL_COMPILE
pet_DATA = $(roms) $(romsets) $(palettes) $(sdl_keymaps)

EXTRA_DIST = $(pet_DATA) $(extra_keymaps) $(x11_keymaps) $(win32_files)
else
pet_DATA = $(roms) $(romsets) $(palettes) $(x11_keymaps)

EXTRA_DIST = $(pet_DATA) $(extra_keymaps) $(sdl_keymaps) $(win32_files)
endif
