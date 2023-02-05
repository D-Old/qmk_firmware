Compilation/flashing instructions
===============================================

### Compile firmware
qmk compile -kb ferris/sweep -km bv_colemak_dh_ger

### Flash halves accoring to side
qmk flash -kb ferris/sweep -km bv_colemak_dh_ger -bl avrdude-split-right

qmk flash -kb ferris/sweep -km bv_colemak_dh_ger -bl avrdude-split-left
