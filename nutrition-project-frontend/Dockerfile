FROM node
RUN mkdir -p /usr/src/app
EXPOSE 4200
WORKDIR /usr/src/app
COPY dist /usr/src/app/dist
RUN npm install -g http-server
CMD ["http-server","dist/NutritionFrontEnd", "--port=4200"]