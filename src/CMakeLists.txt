set(LLVM_LINK_COMPONENTS Support Object)

add_tablegen(custom-tblgen CUSTOM
  ./main.cpp
)
