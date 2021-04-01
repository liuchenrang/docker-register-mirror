docker run --rm --network dockerregistermirror_default banzzaj/alpine-docker-curl curl 172.18.0.5:5000/v2/
docker run --rm --network dockerregistermirror_default banzzaj/alpine-docker-curl curl -i -L http://registry-gcr:5000//v2/knative-releases/knative.dev/net-http01/cmd/controller/manifests/latest

can config docker-compose 
image: curlimages/curl
command: ["/bin/sleep", "3650d"]