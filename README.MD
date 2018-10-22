docker build -t identidock .

docker run -d -P identidock 
docker run -d-P identidock 
docker run -d -e "ENV=DEV" -p 5000:5000 identidock 