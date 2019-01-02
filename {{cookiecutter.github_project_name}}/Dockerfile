FROM {{cookiecutter.base_image}}

ARG BUILD_DATE
ARG VCS_REF

LABEL org.label-schema.build-date=$BUILD_DATE \
      org.label-schema.vcs-url="https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.github_project_name}}.git" \
      org.label-schema.vcs-ref=$VCS_REF \
      org.label-schema.schema-version="1.0.0-rc1"

WORKDIR /documents

ENTRYPOINT ["/bin/sh"]
