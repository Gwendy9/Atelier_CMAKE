add_test(NAME test_carre COMMAND calculator car 5)
set_tests_properties(test_carre PROPERTIES PASS_REGULAR_EXPRESSION "25")
