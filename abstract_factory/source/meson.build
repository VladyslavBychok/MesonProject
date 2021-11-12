
sources_in = files([
    'ConcreteFactory1.cpp' , 
    'ConcreteFactory2.cpp' , 
    'ConcreteProductA1.cpp', 
    'ConcreteProductA2.cpp', 
    'ConcreteProductB1.cpp', 
    'ConcreteProductB2.cpp'])

source_lib = shared_library('source_lib', sourses: sources_in, include_directories: inc)

abstr_depend = declare_dependency(link_with:[sources_in], include_directories:[inc])

