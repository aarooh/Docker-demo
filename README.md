# Docker-demo


FROM nginx – Install nginx web-server
COPY index.html /usr/share/nginx/html/ 
EXPOSE 80 – Set port to 80


Run: "docker build -t dockerdemo https://github.com/aarooh/Docker-demo.git"
Run: "docker run -itd --name dockerwebser --publish 8081:80 dockerdemo"
