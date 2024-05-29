
                cmake_minimum_required (VERSION 3.0)
                project (BUILD_IT)
                find_package(SCI REQUIRED PATHS "/home/kim/Documents/GitHub/EzPC/Athos/../SCI/build/install")
                add_executable(model29may2_SCI_OT.out /home/kim/Documents/GitHub/bsc_thesis/demo/model29may2_56_sci_OT0.cpp)
                target_link_libraries(model29may2_SCI_OT.out SCI::SCI-OT)
            