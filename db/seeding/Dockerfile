FROM mysql:latest

COPY ./seeding.sh /seeding.sh
RUN chmod +x /seeding.sh

CMD  ./seeding.sh