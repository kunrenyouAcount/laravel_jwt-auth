FROM --platform=linux/x86_64 mysql:8.0

ENV MYSQL_DATABASE=test \
  MYSQL_USER=training_user \
  MYSQL_PASSWORD=secret \
  MYSQL_ROOT_PASSWORD=secret \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf