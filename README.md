# rate limiting demo
###### The demo showcases subscription based API rate limiting using fixed window algorithm. Application also implements authentication and session externalisation using Redis and Spring.

###### Run using docker

	docker run -p 127.0.0.1:8080:8080 -e SPRING_REDIS_HOST=<HOST> -e SPRING_REDIS_PORT=<PORT> -e SPRING_REDIS_PASSWORD=<PSWD> abhishekcoder/rate_limiting_app:latest

ref: https://life.wongnai.com/%E0%B8%AD%E0%B8%AD%E0%B8%81%E0%B8%A3%E0%B8%B0%E0%B8%9A%E0%B8%9A-rate-limit-%E0%B8%9A%E0%B8%99-distributed-system-efcacc69aec8
