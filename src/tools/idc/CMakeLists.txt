# Copyright (C) 2022 The Qt Company Ltd.
# SPDX-License-Identifier: BSD-3-Clause

#####################################################################
## idc Tool:
#####################################################################

qt_get_tool_target_name(target_name idc)
qt_internal_add_app(${target_name}
    TARGET_DESCRIPTION "Active Qt Interface Description Compiler"
    SOURCES
        main.cpp
    PUBLIC_LIBRARIES
        Qt::Core
)
qt_internal_return_unless_building_tools()
