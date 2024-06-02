build:

conan install . --output-folder=build --build=missing

cmake -S. -Bbuild

cmake --preset conan-default
