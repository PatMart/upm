upm_mixed_module_init (NAME ds18b20
    DESCRIPTION "DS18B20 1-wire Temperature sensor"
    C_HDR ds18b20.h
    C_SRC ds18b20.c
    CPP_HDR ds18b20.hpp
    CPP_SRC ds18b20.cxx
#    FTI_SRC ds18b20_fti.c
#    CPP_WRAPS_C
    REQUIRES upmc-utilities mraa)
