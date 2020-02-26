Description
---

protoc and libprotobuf


Build instructions
---

- Get protobuf source from github:

    git clone https://github.com/protocolbuffers/protobuf.git
    git checkout v3.6.1

- Build using cmake:

    cmake -Dprotobuf_BUILD_TESTS=OFF -DCMAKE_BUILD_TYPE=RELEASE -DCMAKE_INSTALL_PREFIX=/home/j/sph/ugcs-deps/toolchain/linux/protobuf/ ../cmake/
    make install

- copy everything from install directory here.

