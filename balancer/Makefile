
docker-build:
	docker build -t eshurupov/em23-balancer:1.0 -t eshurupov/em23-balancer:latest .

docker-login:
	docker login

docker-push:
	docker push --all-tags eshurupov/em23-balancer

docker-build-push: docker-build docker-push