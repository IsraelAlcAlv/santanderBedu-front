# Iniciar proyecto de git
git init

# Preparar archivos que se convertiran en commit
git add .

## El punto es para agregar todos los archivos modificados
git commit -m "Aqui va el mensaje"

# Agregar remoto "Solo la primera vez"
git remote add origin https://github.com/IsraelAlcAlv/santanderBedu-front.git

# Enviar commits al servidor de GitHub
git push -u origin main