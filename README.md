# custom-wso2am-install

then run:

docker build -t custom-wso2am .
docker run -d -p 9443:9443 -p 8280:8280 -p 8243:8243 –-name WSO2AM320 custom-wso2am:latest
