FROM node:14.17.3-alpine3.14
RUN addgroup app
RUN adduser -S -G app app
USER app

WORKDIR /app

EXPOSE 3000
CMD ["node", "."]