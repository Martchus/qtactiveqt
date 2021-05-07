# Generated from idc.pro.

#####################################################################
## idc Tool:
#####################################################################

qt_get_tool_target_name(target_name idc)
qt_internal_add_app(${target_name} # special case
#    BOOTSTRAP # special case
    TARGET_DESCRIPTION "Active Qt Interface Description Compiler"
    SOURCES
        main.cpp
    PUBLIC_LIBRARIES
        Qt::Core
)

#### Keys ignored in scope 1:.:.:idc.pro:<TRUE>:
# QMAKE_TARGET_DESCRIPTION = "Active Qt Interface Description Compiler"
# _OPTION = "host_build"
