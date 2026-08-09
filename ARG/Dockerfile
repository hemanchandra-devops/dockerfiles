ARG version
FROM almalinux:${version:-9}
ARG course="docker" \
    trainer="heman"
ENV course=${course}
RUN echo course is: "${course}"
CMD ["sleep", "1000"]