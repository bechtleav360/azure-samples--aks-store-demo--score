## Developer Experience with Score


### Prerequisites 

go install -v github.com/score-spec/score-compose/cmd/score-compose@latest


## Usage

score-compose init

score-compose generate \
  ./order/score.yaml \
  ./product/score.yaml \
  ./store-front/score.yaml \
  ./store-admin/score.yaml \
  ./makeline/score.yaml