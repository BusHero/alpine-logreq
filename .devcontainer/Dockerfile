FROM alpine:3.17

RUN apk update \
	&& apk upgrade \
	&& apk add \
	alpine-sdk \
    sudo

# ENV USER=docker
# ENV UID=12345

# RUN mkdir "/home/$USER" \
#     && adduser \
#         --disabled-password \
#         --gecos "" \
#         --home "/home/$USER" \
#         --ingroup abuild \
#         --uid "$UID" \
#         "$USER"

# RUN sed \
#         -i 's/#PACKAGER=.*/PACKAGER="Petru Cervac petru.cervac@gmail.com"/' \
#         '/etc/abuild.conf' \
#     && sed \
#         -i 's/#MAINTAINER=.*/MAINTAINER="$PACKAGER"/' \
#         '/etc/abuild.conf'

# RUN mkdir -p /var/cache/distfiles \
#     && chgrp abuild /var/cache/distfiles \
#     && chmod g+w /var/cache/distfiles

# USER $USER

# RUN abuild-keygen -a -i -n
