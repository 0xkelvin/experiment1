# experiment1

```
git clone https://github.com/microsoft/vcpkg
cd vcpkg
git checkout 2023.04.15
./bootstrap-vcpkg.sh
brew install nasm yasm
./vcpkg install libvpx libyuv opus aom
git clone https://github.com/0xkelvin/experiment1
cd rustdesk
export VCPKG_ROOT=[your path]/vcpkg
wget https://github.com/c-smile/sciter-sdk/raw/master/bin.osx/libsciter.dylib
cargo run
```
