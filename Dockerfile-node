FROM node:13.7.0-alpine3.10

#=======================
# General Configuration
#=======================
EXPOSE 5000

RUN mkdir -p /app
WORKDIR /app

COPY index.js /app/

CMD ["node", "/app/index.js"]