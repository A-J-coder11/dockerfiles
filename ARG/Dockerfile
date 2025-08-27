# FROM almalinux:9
ARG version
FROM almalinux:${version:-9}
ENV course="DevOps" \
    duration="120hrs" 
ARG trainer="Anand"
RUN echo "hi, course is : ${course}, duration is : ${duration}, trainer is : ${trainer}"
CMD ["sleep", "1000"]