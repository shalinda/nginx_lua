## Dockerfile with Nginx and Lua
# nginx_lua

# Docker build
'''docker build . -t nginx_lua
docker run -p 8080:80 nginx_lua'''

# Use httpie
'''http http://localhost:8080/hellolua?name1=shalinda'''
or
'''curl http://localhost:8080/hellolua?name1=shalinda'''


