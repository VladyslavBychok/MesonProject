dep = dependency('qtest', main: true)

e = executable('test1', sources:['ConcreteProductA1Test.cpp'], include_directories: inc, dependencies:[dep, source_lib])

test('test', e)