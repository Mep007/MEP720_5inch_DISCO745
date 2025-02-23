SET(SOURCES screens/ui_Screen1.c
    screens/ui_Screen2.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    images/ui_img_afe_400_test_1_png.c
    images/ui_img_afe_needle_178x24_mep_png.c
    images/ui_img_gauge_big_hor_450x99_png.c
    images/ui_img_gauge_big_hor_inv_450x99_png.c)

add_library(ui ${SOURCES})
