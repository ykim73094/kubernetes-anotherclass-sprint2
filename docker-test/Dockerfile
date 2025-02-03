# 베이스 이미지 선택 (Python 3.9)
FROM python:3.9-slim

# 작업 디렉토리 설정
WORKDIR /app

# 필요한 파일 복사
COPY ./app.py /app
COPY ./requirements.txt /app

# 패키지 설치
RUN pip install --no-cache-dir -r requirements.txt

# 컨테이너 실행 시 실행할 명령어
CMD ["python", "app.py"]

# 컨테이너에서 사용할 포트 지정
EXPOSE 8080
