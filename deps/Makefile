

cmake_minimum_required(VERSION 3.7.1)
project(RdRand)
add_executable(RdRand rdrand/rdrand.c)

#[[
librdrand.$(SLIB): rdrand/rdrand.c
	cc -shared -fPIC -O2 rdrand/rdrand.c -o librdrand.$(SLIB) -Irdrand

clean:
	rm librdrand.$(SLIB)
]]
