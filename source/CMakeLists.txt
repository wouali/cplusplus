# Add executable called "helloDemo" that is built from the source files
# "demo.cxx" and "demo_b.cxx". The extensions are automatically found.

file(GLOB sources
    "*.cpp"
)

add_executable(my_exe ${sources})

