FROM envoyproxy/envoy:latest

RUN apt-get update && apt-get -q install -y \
    curl

CMD /usr/local/bin/envoy -c /etc/front-proxy-envoy.json --service-cluster front-proxy
