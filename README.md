# Como fazer Downloads de video do Youtube usando o Google Colab
* Python 🐍️
* Biblioteca Pytube▶️
* Salvar no Google drive🗃️

### Primeiro passo
* Acesse https://colab.research.google.com/drive/💻️
* Na parte superior esquerdo, Arquivo > Novo Notebook
* Ira abrir uma página do notebook

Na primeira linha do codigo coloque 
```bash
!python -m pip install git+https://github.com/pytube/pytube  
```
Executa no Play ao lado ▶️

```bash
Successfully installed pytube
```
Mensagem de retorno de sucesso na instalação da biblioteca.

### Motando o Google drive
Do lado esquerdo no notebook tem uma parte que da para navegar nos arquivos. Nesse local que monta o seu drive no notebook.
O processo e simples e rápido

### Fazendo Download do Vídeo
usei Essa linha para realizar o download do video em HD com boa qualidade. Primeira parte do scrits é levando o caminho do shell para o drive, a segunda parte é fazendo o download do video no formato mp4.
```bash
!cd /content/drive/MyDrive/Cursos; pytube URL do video --itag=22
```
### Finalizando 
Você pode depois baixa o video do drive sem problema, ou se tiver configurado a sicronia do drive em um dispotivo o arquivo em poucos minutos estará nesse dispositivo.
### OBS.
* Usei a ! para executar alguns comando shell linux nesse notebook 
* pode usar 
```bash
!pytube -h
```
para ver mais opções de download e configurações.
