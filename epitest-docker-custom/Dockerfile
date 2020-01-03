FROM epitechcontent/epitest-docker

RUN sed -i 's/tsflags=nodocs/#tsflags=nodocs/' /etc/dnf/dnf.conf

RUN dnf -y install man man-pages

RUN echo -e '\nalias norminette="/norminette/norminette"' >> ~/.bashrc

RUN git clone https://github.com/Epitech/epitech-emacs.git /tmp/epitech-emacs; cd /tmp/epitech-emacs; ./INSTALL.sh local

COPY blih /usr/local/bin/