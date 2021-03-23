FROM node
RUN echo "Built from image id:" > /etc/buildinfo
ARG CACHEBUST=no
RUN echo "8185511cd5ad" >> /etc/buildinfo
RUN echo "an ubuntu 16.04 image" >> /etc/buildinfo 
RUN mkdir -p test/test2/test3
WORKDIR /test
RUN ls
CMD ["cat","/etc/buildinfo"]