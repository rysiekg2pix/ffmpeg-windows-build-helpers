ffmpeg-windows-build-helpers
============================
**Cross-compiling from a Linux environment:**
  
1. Install minigw-w64 
```
   $ sudo apt-get install mingw-w64
```

2. Clone this repo

3. Run ```./cross_compile_ffmpeg.sh -h``` to see what are the available options

4. Invoke the cross compilation script as _root_ !
   (invocation example)
```
   $  sudo ./cross_compile_ffmpeg.sh --build-ffmpeg-static=n --build-ffmpeg-shared=y --gcc-cpu-count=4 --compiler-flavors=win64
```

