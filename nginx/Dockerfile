# exact copy/paste from dev Dockerfile

FROM nginx
# the docker hub page for nginx tells us how to setup nginx, aka the line below
COPY ./default.conf /etc/nginx/conf.d/default.conf
# this line was missing from the lectures, but EB will not deploy without this I think
EXPOSE 80