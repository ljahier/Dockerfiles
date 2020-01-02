FROM epitechcontent/epitest-docker

RUN sed -i 's/tsflags=nodocs/#tsflags=nodocs/' /etc/dnf/dnf.conf

RUN dnf -y install man man-pages

RUN echo -e '\nalias norminette="/Epitech/norminette/norminette"' >> ~/.bashrc

VOLUME ~/iCloud\ Drive/Epitech/ /Epitech

COPY blih /usr/local/bin/