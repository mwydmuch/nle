cmake_minimum_required(VERSION 3.5)

add_library(
  bz2_static STATIC
  blocksort.c
  bzlib.c
  compress.c
  crctable.c
  decompress.c
  huffman.c
  randtable.c)
target_link_libraries(bz2_static)
