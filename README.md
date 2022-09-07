# flask-app-with-docker-and-kubernetes
test flask app
essential commands

sudo docker build -t flask-app .

sudo docker tag flask-app lyonga/project:flask-app
sudo docker push  lyonga/project:flask-app

kubectl apply -f flask.yaml
