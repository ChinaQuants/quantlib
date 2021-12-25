add_executable(CDS CDS.cpp)
<<<<<<< HEAD
target_link_libraries(CDS ${QL_LINK_LIBRARY})
=======
target_link_libraries(CDS ql_library ${QL_EXAMPLES_LIBRARIES})
if (QL_INSTALL_EXAMPLES)
    install(TARGETS CDS RUNTIME DESTINATION ${QL_INSTALL_EXAMPLESDIR})
endif()
>>>>>>> 962f4f7574428e2b85d9eceed21733a162458277
