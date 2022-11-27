# How to add namespace to P4 Compiler

Adding namespace to P4-16 language and compiler helps include base header file in new code without any name conflict. Namespace should not just support P4 header and struct, but also variables and Derived Types in P4. 

The C++ compiler already supports namespace using Name Mangling, https://en.wikipedia.org/wiki/Name_mangling which p4c can leverage.  Aso, see https://itanium-cxx-abi.github.io/cxx-abi/abi.html#mangling
