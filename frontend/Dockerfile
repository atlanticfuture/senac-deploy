# Use a imagem base do Nginx
FROM nginx:alpine

# Copie o arquivo de configuração do Nginx
COPY nginx.conf /etc/nginx/nginx.conf

# Copie os arquivos de build do Angular para o diretório padrão do Nginx
COPY dist/my-app /usr/share/nginx/html

# Exponha a porta 80
EXPOSE 80


