FROM node
    LABEL maintainer ian.miell@gmail.com
    RUN git clone -q https://github.com/docker-in-practice/todo.git
    WORKDIR todo
    RUN npm install > /dev/null
    EXPOSE 8000
    ENTRYPOINT ["npm", "start"]