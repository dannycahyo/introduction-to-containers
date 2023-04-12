FROM node:latest
WORKDIR /app
COPY . .
RUN npm i && npm run build

FROM nginx:alpine
COPY --from=0 /app/build /usr/share/nginx/html