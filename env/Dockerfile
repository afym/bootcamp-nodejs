FROM jupyter/minimal-notebook:latest

USER root

RUN apt-get update && \
    apt-get install -y curl build-essential && \
    curl -fsSL https://deb.nodesource.com/setup_20.x | bash - && \
    apt-get install -y nodejs && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

RUN npm install -g ijavascript
RUN ijsinstall --install=global

RUN npm install -g \
    express \
    nodemon \
    mongoose \
    dotenv \
    cors \
    axios \
    jsonwebtoken \
    bcryptjs \
    uuid \
    fs-extra

ENV NODE_PATH=/usr/lib/node_modules

RUN chown -R ${NB_UID}:${NB_GID} /home/jovyan/work

USER ${NB_UID}

CMD ["start-notebook.sh", "--NotebookApp.token=''", "--NotebookApp.password=''", "--allow-root"]
