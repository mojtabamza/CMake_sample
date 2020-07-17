this is a simple project to show how to use cmake to compile a CPP code


you just need to create
	
	project
		CMakeLists.txt
		build(dir) --> do nothing
		src(dir)
			CMakeLists.txt
			main.cpp
			lib(dir)
				lib.hpp
				lib.cpp




then cd build and run: $cmake ..

then run	         : $make


exit from build and now you can see the executable file in bin directory

note: the bin and lib directories will be created automatically by CMAKE

