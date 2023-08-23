set(LIB_NAME lib_test0)
set(LIB_VERSION 1.0.0)
set(LIB_INCLUDES api)
set(LIB_DEPENDENT_MODULES "danielpieczko/lib_test1(1.0.0)")

XMOS_REGISTER_MODULE()
