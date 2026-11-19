add_test(NAME test_carre COMMAND calculator car 5)
set_tests_properties(test_carre PROPERTIES PASS_REGULAR_EXPRESSION "25")
add_test(NAME test_carre_negatif COMMAND calculator car -4)
set_tests_properties(test_carre_negatif PROPERTIES PASS_REGULAR_EXPRESSION "16")
