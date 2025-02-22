FROM almalinux:9
ARG name="pavan" \
    cloud="aws"
RUN echo "name is $name working on $cloud"
CMD ["sleep","100"]

# we can pass the arg values run time using below command
# docker build -t arg:v1 --build-arg cloud=azure .