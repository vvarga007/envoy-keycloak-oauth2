FROM quay.io/keycloak/keycloak:18.0.2-legacy

COPY ./realm.json /realm.json

ENV KEYCLOAK_USER admin
ENV KEYCLOAK_PASSWORD admin
ENV KEYCLOAK_IMPORT /realm.json
