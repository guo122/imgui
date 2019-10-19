
set(PROJECT_NAME imgui)

set(SRCROOT ${CMAKE_CURRENT_LIST_DIR})

set(DIR_SRCS
	${SRCROOT}/imgui.cpp
	${SRCROOT}/imgui.h
	${SRCROOT}/imgui_demo.cpp
	${SRCROOT}/imgui_draw.cpp
	${SRCROOT}/imgui_widgets.cpp
	${SRCROOT}/imgui_internal.h
	${SRCROOT}/imconfig.h
	${SRCROOT}/imstb_rectpack.h
	${SRCROOT}/imstb_textedit.h
	${SRCROOT}/imstb_truetype.h
)

add_lib(
    ${PROJECT_NAME}
    FOLDER "3rd"
    SOURCES ${DIR_SRCS}
)
