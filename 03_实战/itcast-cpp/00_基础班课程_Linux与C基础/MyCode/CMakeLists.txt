cmake_minimum_required(VERSION 2.8.4)
project(MyCode C)

set(CMAKE_C_STANDARD 99)

# 第5章 数组和字符串
add_executable(5_2_1 chapter05array/5_2_1_one_dim_array.c)
add_executable(5_2_2 chapter05array/5_2_2_one_dim_array_init.c)
add_executable(5_2_3 chapter05array/5_2_3_one_dim_array_name.c)
add_executable(5_2_4 chapter05array/5_2_4_max_of_one_dim_array.c)
add_executable(5_2_4_2 chapter05array/5_2_4_reverse_one_dim_array.c)
add_executable(5_2_4_3 chapter05array/5_2_4_bubble_sort_one_dim_array.c)
add_executable(5_3_1 chapter05array/5_3_1_two_dim_array.c)
add_executable(5_3_2 chapter05array/5_3_2_two_dim_array_init.c)
add_executable(5_3_3 chapter05array/5_3_3_two_dim_array_name.c)
add_executable(5_3_4 chapter05array/5_3_4_two_dim_array_example.c)
add_executable(5_5_1 chapter05array/5_5_1_arr_and_str.c)
add_executable(5_5_2 chapter05array/5_5_2_arr_str_init.c)
add_executable(5_5_3 chapter05array/5_5_3_arr_str_input_output.c)
add_executable(5_5_4 chapter05array/5_5_4_arr_str_append.c)
add_executable(5_5_5 chapter05array/5_5_5_rand_and_srand.c)
add_executable(5_5_6_1 chapter05array/5_5_6_1_gets.c)
add_executable(5_5_6_2 chapter05array/5_5_6_2_fgets.c)
add_executable(5_5_6_3 chapter05array/5_5_6_3_puts.c)
add_executable(5_5_6_4 chapter05array/5_5_6_4_fputs.c)
add_executable(5_5_6_5 chapter05array/5_5_6_5_strlen.c)
add_executable(5_5_6_6 chapter05array/5_5_6_6_strcpy.c)
add_executable(5_5_6_7 chapter05array/5_5_6_7_strncpy.c)
add_executable(5_5_6_8 chapter05array/5_5_6_8_strcat.c)
add_executable(5_5_6_9 chapter05array/5_5_6_9_strncat.c)
add_executable(5_5_6_10 chapter05array/5_5_6_10_strcmp.c)
add_executable(5_5_6_11 chapter05array/5_5_6_11_strncmp.c)
add_executable(5_5_6_12 chapter05array/5_5_6_12_sprintf.c)
add_executable(5_5_6_13 chapter05array/5_5_6_13_sscanf.c)
add_executable(5_5_6_14 chapter05array/5_5_6_14_strchr.c)
add_executable(5_5_6_15 chapter05array/5_5_6_15_strstr.c)
add_executable(5_5_6_16 chapter05array/5_5_6_16_strtok.c)
add_executable(5_5_6_17 chapter05array/5_5_6_17_atox.c)

# 第6章 函数
add_executable(6 chapter06function/main.c chapter06function/func.h chapter06function/func.c)

# 第7章 指针
add_executable(7_2_1 chapter07pointer/7_2_1_def_init.c)
add_executable(7_2_2 chapter07pointer/7_2_2_modify_pointer.c)
add_executable(7_2_3 chapter07pointer/7_2_3_size_of_pointer.c)
add_executable(7_2_4 chapter07pointer/7_2_4_wild_pointer.c)
add_executable(7_2_5 chapter07pointer/7_2_5_void_pointer.c)
add_executable(7_2_6 chapter07pointer/7_2_6_const_pointer.c)
add_executable(7_3_1 chapter07pointer/7_3_1_array_name_pointer.c)
add_executable(7_3_2_1 chapter07pointer/7_3_3_pointer_add.c)
add_executable(7_3_2_2 chapter07pointer/7_3_3_pointer_sub.c)
add_executable(7_3_4 chapter07pointer/7_3_4_pointer_array.c)
add_executable(7_4 chapter07pointer/7_4_multi_level_pointer.c)
add_executable(7_5_1 chapter07pointer/7_5_1_func_pointer_params.c)
add_executable(7_5_2 chapter07pointer/7_5_2_array_as_params.c)
add_executable(7_5_3 chapter07pointer/7_5_3_pointer_as_return.c)
add_executable(7_6_1 chapter07pointer/7_6_1_char_pointer.c)
add_executable(7_6_2 chapter07pointer/7_6_2_char_pointer_as_params.c)
add_executable(7_6_3 chapter07pointer/7_6_3_const_pointer.c)
add_executable(7_6_4 chapter07pointer/7_6_4_main_pointer_argv.c)
add_executable(7_6_5_1 chapter07pointer/7_6_5_1_str_while.c)
add_executable(7_6_5_2 chapter07pointer/7_6_5_2_both_direction_iteration.c)
add_executable(7_6_5_3 chapter07pointer/7_6_5_3_str_inverse.c)

# 第8章 内存管理
add_executable(8_1_1 chapter08memory/8_1_1_auto.c)
add_executable(8_1_2 chapter08memory/8_1_2_static.c)
add_executable(8_2_2 chapter08memory/8_2_2_memory_type.c)
add_executable(8_2_3_1 chapter08memory/8_2_3_1_memset.c)
add_executable(8_2_3_2 chapter08memory/8_2_3_2_memcpy.c)
add_executable(8_2_3_4 chapter08memory/8_2_3_4_memcmp.c)
add_executable(8_2_4 chapter08memory/8_2_4_malloc.c)
add_executable(8_3_1 chapter08memory/8_3_1_stack.c)
add_executable(8_3_2 chapter08memory/8_3_2_data.c)
add_executable(8_3_3 chapter08memory/8_3_3_val_pass.c)
add_executable(8_3_4 chapter08memory/8_3_4_val_pass.c)
add_executable(8_3_5 chapter08memory/8_3_5_heap.c)

# 第9章 复合类型(就结构体、共用体、枚举和typedef)
add_executable(9_1_3 chapter09struct/9_1_3_basic_use.c)
add_executable(9_1_4 chapter09struct/9_1_4_struct_arr.c)
add_executable(9_1_5 chapter09struct/9_1_5_struct_in_struct.c)
add_executable(9_1_6 chapter09struct/9_1_6_assign_value.c)
add_executable(9_1_7_1 chapter09struct/9_1_7_1_common_struct_pointer.c)
add_executable(9_1_7_2 chapter09struct/9_1_7_2_struct_in_heap.c)
add_executable(9_1_7_3 chapter09struct/9_1_7_3_pointer_in_struct.c)
add_executable(9_1_8_1 chapter09struct/9_1_8_1_struct_as_func_params.c)
add_executable(9_1_8_2 chapter09struct/9_1_8_2_struct_pointer_as_func_params.c)
add_executable(9_1_8_3 chapter09struct/9_1_8_3_struct_arr_pointer_as_func_params.c)
add_executable(9_3 chapter09struct/9_3_enum.c)
add_executable(9_4 chapter09struct/9_4_typedef.c)

# 第10章 文件操作
add_executable(10_2_2 chapter10file/10_2_2_fopen.c)
add_executable(10_2_3 chapter10file/10_2_3_fclose.c)
add_executable(10_3_1_1 chapter10file/10_3_1_1_fputc.c)
add_executable(10_3_1_3 chapter10file/10_3_1_3_fgetc.c)
add_executable(10_3_2_1 chapter10file/10_3_2_1_fputs.c)
add_executable(10_3_2_2 chapter10file/10_3_2_2_fgets.c)
add_executable(10_3_4_1 chapter10file/10_3_4_1_fwrite.c)
add_executable(10_3_4_2 chapter10file/10_3_4_2_fread.c)
add_executable(10_4 chapter10file/10_4_fseek_ftell_rewind.c)
add_executable(10_6 chapter10file/10_6_stat.c)