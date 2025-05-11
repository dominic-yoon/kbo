FROM node:20

# 작업 디렉터리 설정
WORKDIR /app

# 패키지 복사 및 설치
COPY package*.json ./
RUN npm install

# 소스 복사
COPY . .

# 개발 서버 포트
EXPOSE 5173

# Vite 개발 서버 실행
CMD [ "npm", "run", "dev" ]