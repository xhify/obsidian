# Machine learning algorthms
Supervised learning
Unsupervised learning

docker run -v $(pwd)/output:/output deezer/spleeter:3.6-5stems separate -o /output audio_example.mp3
docker run -v %F:\matlab_data\sleeter\output:/output deezer/spleeter:3.6-5stems separate -o /output F:\matlab_data\sleeter\test1.m4a
"F:\matlab_data\sleeter\output"
"F:\matlab_data\sleeter\test1.m4a"
docker run -v $F:/matlab_data/sleeter/output:/output deezer/spleeter:3.6-5stems separate -o /output audio_example.mp3'
docker run \
    -v $F:/matlab_data/sleeter:/input \
    -v $F:/matlab_data/sleeter/output:/output \
    -v $MODEL_DIRECTORY:/model \
    -e MODEL_PATH=/model \
    deezer/spleeter \
    separate -o /output /input/audio_1.mp3 /input/audio_2.mp3

docker run -v F:\matlab_data\sleeter\output:/output deezer/spleeter:3.6-5stems separate -o /output audio_example.mp3
```bash
docker run -v F:\matlab_data\sleeter\output:/output -v F:\matlab_data\sleeter\input:/input deezer/spleeter:3.6-5stems separate test1.m4a -i /input -o /output
```
```bash
docker run -v F:\matlab_data\sleeter\output:/output -v F:\matlab_data\sleeter\input:/input deezer/spleeter:3.6-5stems separate  -i /input/test1.m4a -o /output


spleeter separate -p spleeter:2stems -o output test1.m4a
