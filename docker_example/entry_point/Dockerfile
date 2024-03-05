FROM alpine:latest
RUN apk --no-cache add sqlite
WORKDIR /data
CMD ["sqlite3", "example.db", "SELECT * FROM users;"]