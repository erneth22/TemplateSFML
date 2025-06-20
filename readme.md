#TODO
Guide for future me how to use this template project for SFML 3.0 programming.
Current setup Linux(Fedora 42),vscode, cmake build using ninja and g++.

First Steps:
- This repo is a template, use it to create standalone project
- Change project name in CMakeLists.txt in project( -> nameOfProject <- LANGUAGES CXX)
- Adjust C++ standard in target_compile_features(main PRIVATE -> cxx_std_20 <- )
