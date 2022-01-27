# notes-ffmpeg

## compile and install
```bash
git clone https://github.com/FFmpeg/FFmpeg.git
cd FFmpeg
sudo apt install libx264-dev
./configure --prefix=install --enable-shared --enable-libx264 --enable-gpl --enable-pthreads --disable-x86asm
make -j32 && make install
```
