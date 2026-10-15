FROM gcr.io/cadvisor/cadvisor:v0.55.1

EXPOSE 8080

ENTRYPOINT ["/usr/bin/cadvisor", "-logtostderr", "-port=8080", "-docker_only=true"]
