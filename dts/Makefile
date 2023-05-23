# SPDX-License-Identifier: GPL-2.0
dtb-y += mediatek/mt6768.dtb

dtbo-y += samsung/mt6768-m32_eur_open_01.dtbo
dtbo-y += samsung/mt6768-m32_eur_open_00.dtbo


targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
