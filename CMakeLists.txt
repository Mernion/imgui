cmake_minimum_required (VERSION 3.18)

project(ImGui)

set(SOURCES 
	"imconfig.h"
	"imgui.cpp"
	"imgui_demo.cpp"
	"imgui_draw.cpp"
	"imgui_internal.h"
	"imgui_widgets.cpp"
	"imstb_rectpack.h"
	"imstb_textedit.h"
	"imstb_truetype.h"
)

add_library(ImGui STATIC ${SOURCES})

target_include_directories(ImGui PUBLIC "")

