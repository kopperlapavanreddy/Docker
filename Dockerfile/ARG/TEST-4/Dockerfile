ARG version
FROM almalinux:$version
ARG name="pavan" \
    cloud="aws"
RUN echo "name is $name working on $cloud"
CMD ["sleep","100"]

# we can pass the arg values run time using below command
# docker build -t arg:v1 --build-arg cloud=azure .
# docker build -t arg:v4 --build-arg version=8 .