FROM gitlab/gitlab-ce:latest

VOLUME ["/var/opt/gitlab", "/var/log/gitlab", "/etc/gitlab"]

EXPOSE 80 443 22

ENV GITLAB_OMNIBUS_CONFIG="external_url 'http://gitlab.local';"

CMD ["tail", "-f", "/dev/null"]
