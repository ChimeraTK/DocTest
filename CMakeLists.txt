cmake_minimum_required (VERSION 2.8.7)

Project(DocTest)


  add_custom_target(doc
    mkdir -p html && cp ${PROJECT_SOURCE_DIR}/doc/index.html html
    WORKING_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR}
    )
