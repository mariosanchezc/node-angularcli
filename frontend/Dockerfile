### Última Versión de Node
FROM node:7.9.0

### Instalar globalmente angular cli utilizar --unsafe para solucionar problemas.
RUN npm install -g @angular/cli --user root --unsafe-perm true

### Variable de Entorno del directorio de trabajo
ENV FRONTEND '/frontend/'

### Colocarse en el directorio
WORKDIR ${FRONTEND}/multasapp

### Copiar los archivos desde el host al contenedor
COPY . ${FRONTEND}