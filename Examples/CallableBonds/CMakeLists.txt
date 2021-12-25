add_executable(CallableBonds CallableBonds.cpp)
<<<<<<< HEAD
target_link_libraries(CallableBonds ${QL_LINK_LIBRARY})
=======
target_link_libraries(CallableBonds ql_library ${QL_EXAMPLES_LIBRARIES})
if (QL_INSTALL_EXAMPLES)
    install(TARGETS CallableBonds RUNTIME DESTINATION ${QL_INSTALL_EXAMPLESDIR})
endif()

>>>>>>> 962f4f7574428e2b85d9eceed21733a162458277
