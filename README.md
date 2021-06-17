# node12-multi-arch

docker buildx build --platform linux/amd64,linux/arm64,linux/arm/v7 -t we2app/node12-multi-arch:latest --push .