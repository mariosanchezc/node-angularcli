### Última Versión de Node
FROM node:latest

### Instalar globalmente angular cli utilizar --unsafe para solucionar problemas.
RUN npm install -g @angular/cli --unsafe

### Variable de Entorno del directorio de trabajo
ENV FRONTEND '/frontend'

### Colocarse en el directorio
WORKDIR ${FRONTEND}

### Copiar los archivos desde el host al contenedor
COPY . ${FRONTEND}