# Banco-de-dados-
Neste projeto está o modelo lógico e relacional. 
from google.colab import drive
drive.mount('/content/drive')

# Copiar a pasta para o ambiente local
!cp -r /content/drive/MyDrive/sua_pasta_aqui /content/

# Subir via Git (se o repositório estiver clonado)
!git clone https://github.com/seuusuario/seurepo.git
!cp -r /content/sua_pasta_aqui /content/seurepo/
%cd /content/seurepo/
!git add .
!git commit -m "Adicionando arquivos do Drive"
!git push
