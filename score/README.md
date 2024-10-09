## Developer Experience with Score


### Prerequisites 

go install -v github.com/score-spec/score-compose/cmd/score-compose@latest


## Usage

score-compose init

score-compose generate \
  apps/order/score.yaml \
  apps/product/score.yaml \
  apps/store-front/score.yaml \
  apps/store-admin/score.yaml \
  apps/makeline/score.yaml