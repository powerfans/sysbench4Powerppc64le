# sysbench4Powerppc64le
sysbench 1.1.0 for Power ppc64le with built-in LuaJIT-ppc64-port 2.1.0.

# Guide for build sysbench
CFLAGS="-O3 -pthread " \
CXXFLAGS="-O3 -pthread " \
LDFLAGS="-ldl" \
./configure --prefix=/opt/sysbench --without-mysql --build=ppc64le 

make && make install
