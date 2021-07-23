FROM mysql:latest

COPY ./products.csv /products.csv
COPY ./users.csv /users.csv

ENTRYPOINT ["/entrypoint.sh"]
CMD ["mysqld", "--secure-file-priv=/"]
