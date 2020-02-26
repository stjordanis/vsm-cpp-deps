Description
---

protoc and libprotobuf built with MinGW64 gcc 7.1


Build instructions
---

- Get protobuf source from github:

    git clone https://github.com/protocolbuffers/protobuf.git
    git checkout v3.6.1

- Build using cmake:

    cmake -Dprotobuf_BUILD_TESTS=OFF -DCMAKE_BUILD_TYPE=RELEASE -DCMAKE_INSTALL_PREFIX=C:\Users\Janis\install\p -G"MinGW Makefiles" ../../protobuf/cmake

    cmake --build . -- -j2 install

- copy everything from install directory here.
