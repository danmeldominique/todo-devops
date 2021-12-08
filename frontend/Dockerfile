# Set base docker image
FROM node:16.3-alpine
# Set up workspace on docker container
WORKDIR /app
# Copy all files to docker container
COPY . .
# Install dependencies
RUN [ "npm", "install"]
# Expose app port
EXPOSE 8080
RUN [ "npm", "install"]
CMD [ "npm","run","serve" ]