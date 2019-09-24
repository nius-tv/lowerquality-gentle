docker build \
	-t lowerquality-gentle \
	lowerquality-gentle

docker run \
  --name gentle \
  --network plasmic \
  -p 8765:8765 \
  lowerquality-gentle
