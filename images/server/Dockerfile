FROM debian:jessie

ADD dig-a /dig-a
ADD dig-srv /dig-srv
COPY ["redis.template.conf", "k8s-redis-ha-server", "run.sh", "/"]

CMD ["/run.sh"]

ENTRYPOINT ["bash", "-c"]
