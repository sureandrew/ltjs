project(ltjs)

cmake_minimum_required(VERSION 2.8)

set(CMAKE_MODULE_PATH ${CMAKE_SOURCE_DIR}/CMake)
set(LTJS_BIN_DIR ${CMAKE_BINARY_DIR}/build/bin)
set(LTJS_GAME_BIN_DIR ${LTJS_BIN_DIR}/game)
set(LTJS_TO2_BIN_DIR ${LTJS_BIN_DIR}/to2)

add_subdirectory(game/clientfxdll)
add_subdirectory(libs/butemgr)
add_subdirectory(game/clientshelldll/clientshellshared)
add_subdirectory(libs/cryptmgr)
add_subdirectory(engine/runtime/render_a/src/sys/d3d)
add_subdirectory(engine/libs/lib_dshow)
add_subdirectory(engine/runtime/sound/src)
add_subdirectory(engine/runtime/info/src)
add_subdirectory(libs/lith)
add_subdirectory(game/libs/ltguimgr)
add_subdirectory(engine/libs/ltmem)
add_subdirectory(libs/mfcstub)
add_subdirectory(game/objectdll/objectshared)
add_subdirectory(libs/regmgr)
add_subdirectory(engine/libs/rezmgr)
add_subdirectory(libs/stdlith)
add_subdirectory(engine/runtime/ui/src)
add_subdirectory(game/libs/wonapi)
add_subdirectory(engine/runtime/winbuild/lithtech)
add_subdirectory(engine/runtime/winbuild/ltmsg)
add_subdirectory(engine/runtime/winbuild/server)
add_subdirectory(game/libs/serverdir)
add_subdirectory(game/serverres/to2)
add_subdirectory(engine/runtime/sound/src/sys/s_dx8)
add_subdirectory(game/clientres/to2)
add_subdirectory(game/clientshelldll/to2)
add_subdirectory(game/objectdll/to2)
