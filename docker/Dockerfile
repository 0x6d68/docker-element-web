ARG ELEMENT_WEB_VERSION
FROM vectorim/element-web:${ELEMENT_WEB_VERSION}

RUN sed -i '/^[[:space:]]*listen[[:space:]]*\[::\]:/s/^/#/' /etc/nginx/templates/default.conf.template
