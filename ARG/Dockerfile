ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
ARG USERNAME=sivakumar
ENV USERNAME=$USERNAME
RUN echo "hello i am ${USERNAME} ${version}" > /tmp/hello.txt
CMD ["sleep","100"]