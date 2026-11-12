PINEAPPLE_BASE_DTB += ../qcom/pineapple-v2.dtb
PINEAPPLE_APQ_BASE_DTB += ../qcom/pineapplep-sg-v2.dtb ../qcom/pineapplep-v2.dtb

SAMSUNG_PINEAPPLE_BOARDS += \
    q6q_eur_openx_w00_r02.dtbo \
    q6q_eur_openx_w00_r04.dtbo \
    q6q_eur_openx_w00_r08.dtbo \
    q6q_eur_openx_w00_r09.dtbo \
    q6q_eur_openx_w00_r10.dtbo

pineapple-overlays-dtb-y += $(SAMSUNG_PINEAPPLE_BOARDS) $(PINEAPPLE_BASE_DTB) $(PINEAPPLE_APQ_BASE_DTB)
dtb-y += $(SAMSUNG_PINEAPPLE_BOARDS) $(PINEAPPLE_BASE_DTB) $(PINEAPPLE_APQ_BASE_DTB)

always-y := $(dtb-y)
subdir-y := $(dts-dirs)
clean-files := *.dtb *.reverse.dts *.dtbo
