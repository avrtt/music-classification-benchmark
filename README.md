This is a system for classifying audio files by music genre. Utilizing [Essentia](https://essentia.upf.edu/) for audio analysis and TensorFlow for machine learning, it delivers high accuracy and efficiency in genre prediction. 

## Installation

Make sure you have **Docker** installed.

Clone & navigate:
```bash
git clone https://github.com/avrtt/music-classification-benchmark.git
cd music-classification-benchmark
```

Build and run the Docker container:
```bash
docker build -t music-classification-benchmark .
docker run -it -p 8000:8000 music-classification-benchmark
```

## Usage

Once the Docker container is running, you can navigate to the Swagger API interface to upload an audio file for classification:
```
http://localhost:8000/docs#/
```

## Contributing

Feel free to open PRs and issues.

## License

This project is licensed under the MIT License, allowing free use, modification, and distribution. See the LICENSE file for more information.