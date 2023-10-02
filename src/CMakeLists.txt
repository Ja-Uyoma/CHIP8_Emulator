add_executable(chip)

target_sources(chip
    PUBLIC
        main.cpp
)

target_compile_features(chip PUBLIC cxx_std_17)

target_compile_options(chip PUBLIC -Wall -Wextra -Werror)