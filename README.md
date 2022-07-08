# yolov5-fastapi
Machine Learning Model API using YOLOv5 with FAST API

### Getting start for this project

```
Run a local FastAPI Service directly:
uvicorn main:app --reload --host 0.0.0.0 --port 8000

Read service docs:
localhost:8000/docs

=====================================================
Build Docker image: 
docker build -t yolov5-fastapi:0.0.1 .

Run with Docker:
docker run -p 8000:8000 yolov5-fastapi:0.0.1

```
