ARG version
FROM almalinux:${version:-9}
ARG name="pavan" \
    cloud="AWS"
ENV cloud=$cloud
RUN echo "Course: $course, duration: $duration, version: $version"
CMD ["sleep","100"]

# we can pass the arg values run time using below command
# docker build -t arg:v1 --build-arg cloud=azure .
# docker build -t arg:v4 --build-arg version=8 .