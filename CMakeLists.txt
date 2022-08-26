add_library(indexer STATIC src/hand_index.c src/deck.c)
target_include_directories(indexer PUBLIC src)
