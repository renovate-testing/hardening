FROM koalaman/shellcheck-alpine@sha256:1bbe2db425ea3607c1d3ba8acd2b9b6ee4dadb7565663195d9b7cabfdf859d36

LABEL "com.github.actions.name"="Konstruktoid ShellCheck"
LABEL "com.github.actions.description"="ShellCheck for multiple files"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/konstruktoid/hardening"
LABEL "homepage"="https://github.com/konstruktoid/hardening"
LABEL "maintainer"="Thomas Sjögren <konstruktoid@users.noreply.github.com>"

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
