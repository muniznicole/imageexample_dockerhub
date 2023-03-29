# Especifica a imagem base
FROM node:14

# Define o diretório de trabalho dentro do contêiner
WORKDIR /app

# Copia os arquivos de origem para o contêiner
COPY . .

# Instala as dependências
RUN npm install

# Expõe a porta em que a aplicação irá rodar
EXPOSE 3000

# Inicia a aplicação
CMD ["npm", "start"]
