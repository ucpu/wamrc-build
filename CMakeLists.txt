cmake_minimum_required(VERSION 3.22)

project(wamrc LANGUAGES C ASM CXX)

set(WAMR_BUILD_DEBUG_AOT 0)
set(WAMR_BUILD_LIBC_BUILTIN 1)
set(WAMR_BUILD_LIBC_UVWASI 0)
set(WAMR_BUILD_LIBC_WASI 0)
set(WAMR_BUILD_LIB_PTHREAD 0)
set(WAMR_BUILD_LIB_WASI_THREADS 0)

add_subdirectory("wamr/wamr-compiler")
