ARG version
FROM almalinux:${version:-8}
RUN echo "Version installed for almalinux is ${version}"
ARG COURSE
ARG TRAINER
ENV COURSE =${COURSE}
ENV TRAINER =${TRAINER}
RUN echo "Trainer name is ${TRAINER}, Course name is ${COURSE}"
