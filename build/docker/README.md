# How to use it ?

export HOST_USER_ID=$(id -u)
export MYSQL_ROOT_PWD=$(tr -dc A-Za-z0-9 </dev/urandom | head -c 13; echo)

docker-compose up -d