FROM debian:jessie

ADD dig-a /dig-a
ADD dig-srv /dig-srv
COPY ["sentinel.template.conf", "k8s-redis-ha-sentinel", "run.sh", "/"]

CMD ["/run.sh"]

ENTRYPOINT ["bash", "-c"]
