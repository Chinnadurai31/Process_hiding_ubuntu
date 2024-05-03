all: multiple_libprocesshider.so

multiple_libprocesshider.so: multiple_processhide.c
    gcc -Wall -fPIC -shared -o multiple_libprocesshider.so multiple_processhide.c -ldl

.PHONY: clean
clean:
    rm -f multiple_libprocesshider.so
