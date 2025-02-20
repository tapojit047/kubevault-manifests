FROM hashicorp/vault:latest
USER root
RUN setcap cap_ipc_lock=+ep /bin/vault
USER vault