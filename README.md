# opencv_js
memo
```
cd /home/hoge/
git clone https://github.com/opencv/opencv.git
cd opencv/
mkdir /home/hoge/build_opencv
git clone https://github.com/emscripten-core/emsdk.git
cd emsdk/
git pull
./emsdk install latest
source ./emsdk_env.sh
./emsdk activate latest
sudo apt install cmake
python ./platforms/js/build_js.py --emscripten_dir=/home/hoge/emsdk/emscripten/1.38.31/ /home/hoge/build_opencv/
```
