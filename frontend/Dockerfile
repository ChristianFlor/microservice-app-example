FROM node:9.11.1-alpine
#variable de entorno para que al momento de hacer confimracion por consola me omita cualquier confirmacion 
#me paro dentro de la carpeta 
WORKDIR /app

COPY package*.json ./


RUN npm install

ENV PORT=8080 

COPY . . /app/


EXPOSE 8080

#me corre el servidor de apache en modo deatahc

CMD ["npm","start"] 
