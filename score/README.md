## Developer Experience with Score


### Prerequisites 

go install -v github.com/score-spec/score-compose/cmd/score-compose@latest


## Usage with docker-compose

score-compose init

score-compose generate \
  ./order/score.yaml \
  ./product/score.yaml \
  ./store-front/score.yaml \
  ./store-admin/score.yaml \
  ./makeline/score.yaml

docker compose up --build -d


## Usage with kubectl

score-k8s init

score-k8s generate \
  ./order/score.yaml \
  ./product/score.yaml \
  ./store-front/score.yaml \
  ./store-admin/score.yaml \
  ./makeline/score.yaml

kubectl apply -f manifests.yaml

