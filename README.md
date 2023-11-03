# Getting started with the Elastic Stack and Docker-Compose

This repo is in reference to the blog [Getting started with the Elastic Stack and Docker-Compose](https://www.elastic.co/blog/getting-started-with-the-elastic-stack-and-docker-compose)

Please feel free to ask any questions via issues [here](https://github.com/elkninja/elastic-stack-docker-part-one/issues), our [Community Slack](https://ela.st/slack), or over in our [Discuss Forums](https://discuss.elastic.co/).

Pull Requests welcome :)


9911  cd INTELLIJ/
 9912  cd OTelemetry.Observability/src
 9913  docker-compose -f docker-compose.yaml build
 9914  docker-compose -f docker-compose.override.yaml up
 9915  docker inspect customer_db
 9916  docker-machine ssh
 9917  screen ~/Library/Containers/com.docker.docker/Data/vms/0/tty
 9918  git clone git@github.com:elkninja/elastic-stack-docker-part-one.git
 9919  cd elastic-stack-docker-part-one
 9920  docker-compose up
 9921  docker os
 9922  docker ps
 9923  cd INTELLIJ
 9924  git clone git@github.com:elkninja/elastic-stack-docker-part-two.git
 9925  cd elastic-stack-docker-part-two
 9926  ls -lrt /var/run/docker.sock
 9927  docker network
 9928  docker network ls
 9929  docker network rm 0180ff1298ee
 9930  docker-compose up --force-recreate
 9931  docker system prune -a
 9932  df -h
 9933  ls /var/run/docker.sock
 9934  ls /sys/fs/cgroup
 9935  ps aux
 9936  sudo kill -9 1326
 9937  cd INTELLIJ/elastic-stack-docker-part-one
 9938  docker-compose up --build
 9939  source -a .env
 9940  export $(cat .env | xargs)
 9941  export $(grep -v '^#' .env | xargs)
 9942  set -o allexport
 9943  . /.env
 9944  ./.env
 9945  . .env
 9946  export $(xargs < .env)export $(xargs < .env)
 9947  export $(xargs < .env)
 9948  eval $(cat .env | sed 's/^/export /')
 9949  printenv
 9950  [-f .env ] && . .env
 9951  [ -f .env ] && . .env
 9952  echo $ELASTIC_A
 9953  cat .env
 9954  cd INTELLIJ/elastic-stack-docker-part-two
 9955  echo $ELASTIC_APM_SECRET_TOKEN
 9956  cd Downloads/
 9957  cd Downloads
 9958  ls
 9959  cd filebeat_ingest_data
 9960  cd ../Downloads
 9961  unzip admin-ph-swift.zip
 9962  ls -laet
 9963  ls -lart
 9964  code .
 9965  cd INTELLIJ/elastic-stack-docker-part-one\ copy
 9966  cd Documents
 9967  keytool -list -v -keystore elasticsearch.keystore -storepass changeme
 9968  ls -lrt
 9969  sh elasticsearch-keystore -list -keystore elasticsearch.keystore
 9970  sh elasticsearch-keystore -list -keystore elasticsearch.keystore -storepass changeme
 9971  sh elasticsearch-keystore -list
 9972  sh elasticsearch-keystore list
 9973  bin/sh elasticsearch-keystore list
 9974  /bin/sh elasticsearch-keystore list
 9975  elasticsearch-keystore list
 9976  ./elasticsearch-keystore list
 9977  chmod 777 genca.sh
 9978  chmod 777 gencerts-acl.sh
 9979  ./genca.sh -a changeme -c CAELK
 9980  ./gencerts-acl.sh -a changeme -c kibana
 9981  ./gencerts-acl.sh -a changeme -c es01
 9982  ./gencerts-acl.sh -a changeme -c fleet-server
 9983  cd ../elastic-stack-docker-part-two
 9984  set -a
 9985  source .env
 9986  set +a
 9987  docker-compose up --force-recreate --build
 9988  cd certs/ca
 9989  openssl x509 -fingerprint -sha256 -noout -in ca.crt | awk -F"=" {' print $2 '} | sed s/://g
 9990  docker-compose down
 9991  cd INTELLIJ/datamanagement
 9992  git branch
 9993  git checkout -b ft/debugNotif
 9994  git push
 9995  git checkout master
 9996  git branch -d ft/debugNotif
 9997  git checkout -b ft/debugFailureNotif
 9998  git push
 9999  git checkout develop
10000  git checkout -b ft/dimSaison
10001  cd INTELLIJ
10002  ls -lrt
10003  history
10004  ls -lrt
10005  cd elastic-stack-docker-part-one
10006  rm -rf .git
10007  git init
10008  git remote add origin git@github.com:phgSW61HS/testelkapmpartone.git
10009  git branch -M master
10010  git push -u origin master
10011  git branch -M main
10012  rm -rf .git
10013  git remote add origin git@github.com:phgSW61HS/testelkapmpartone.git
10014  git init
10015  git add .
10016  git branch -M main
10017  git commit -m "Tutu"
10018  git branch -M main
10019  git remote add origin git@github.com:phgSW61HS/testelkapmpartone.git
10020  git push -u origin main
10021  ls -lrt