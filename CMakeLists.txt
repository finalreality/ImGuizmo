set (IMGUIZMO_SRCS
        ${CMAKE_CURRENT_SOURCE_DIR}/GraphEditor.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/ImCurveEdit.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/ImGradient.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/ImGuizmo.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/ImSequencer.cpp
)

add_library(imguizmo ${IMGUIZMO_SRCS})
