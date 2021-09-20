FROM        node:lts-alpine
COPY        . ./backend
RUN          npm install dotenv
WORKDIR     /backend
RUN         npm install
CMD         [ "node", "server.js" ]
