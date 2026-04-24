ARG ELEMENT_WEB_VERSION
ARG ORIGINAL_USER=root

FROM vectorim/element-web:${ELEMENT_WEB_VERSION}
ARG ORIGINAL_USER

USER root
RUN sed -i '/^[[:space:]]*listen[[:space:]]*\[::\]:/s/^/#/' /etc/nginx/templates/default.conf.template
USER ${ORIGINAL_USER}
