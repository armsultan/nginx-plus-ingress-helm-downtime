IMAGE = myregistry.com/dev-backend

build:
	docker build -t $(IMAGE) .

push:
	docker push $(IMAGE)

test:
	docker run --rm -p 8000:80 $(IMAGE)
	