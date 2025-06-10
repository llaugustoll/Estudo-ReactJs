FROM node:20-alpine

# Diretório de trabalho no container
WORKDIR /app

# Expõe a porta padrão do React
EXPOSE 3000

# Comando padrão do container (override via docker-compose)
CMD ["sh"]

# # Etapa de build
# FROM node:20-alpine AS builder

# # Diretório de trabalho no container
# WORKDIR /app

# # Copia os arquivos de dependência e instala
# COPY package*.json ./
# RUN npm install

# # Copia os demais arquivos e constrói o projeto
# COPY . .
# RUN npm run build

# # Etapa de produção
# FROM nginx:stable-alpine

# # Copia o build do React para o nginx
# COPY --from=builder /app/build /usr/share/nginx/html

# # Copia configuração customizada do nginx (opcional)
# # COPY nginx.conf /etc/nginx/nginx.conf

# # Exposição da porta padrão
# EXPOSE 80

# # Comando para iniciar o nginx
# CMD ["nginx", "-g", "daemon off;"]

