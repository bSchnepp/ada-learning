GNATMAKE := gnatmake
ADAC := gnatgcc

.PHONY: clean

hello: hello.adb
	$(GNATMAKE) hello.adb
	
clean:
	rm -rf hello.o main.o hello hello.ali
