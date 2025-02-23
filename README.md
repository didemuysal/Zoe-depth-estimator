Zoe Depth Estimation API

Overview

The Zoe Depth Estimation API is a deep-learning model designed to estimate depth from images using PyTorch. This API leverages FastAPI to provide an efficient and scalable endpoint for real-time depth estimation.

### CLI Usage

```bash
usage: cli.py [-h] input_image output_image

Depth estimation using ZoeDepth

positional arguments:
  input_image   Path to input image.
  output_image  Path to output depth map.

options:
  -h, --help    show this help message and exit     
```


### API Usage
```
http://127.0.0.1:8000/predict
```

Features
- Fast and accurate depth estimation
- API-based integration with FastAPI
- Docker support for easy deployment
- Requires an API key from imgbb for image handling
- Requirements

Ensure you have the following installed:
- Python 3.7+
- PyTorch
- FastAPI (for running app.py)
- Docker (for containerized deployment)