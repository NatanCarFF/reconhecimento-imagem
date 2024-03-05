# 📁 Baixar e Instalar o Tesseract OCR:

📁 Você pode baixar a versão pré-compilada mais recente do Tesseract OCR para Windows a partir do repositório oficial do projeto no GitHub: Tesseract OCR - GitHub Releases.

📂 Baixe o arquivo de instalação adequado para o seu sistema operacional [tesseract-ocr-w64-setup.exe](https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-5.3.3.20231005.exe).

📂 Execute o arquivo de instalação baixado e siga as instruções na tela para concluir a instalação do Tesseract OCR.

## 💻 Adicionar o Tesseract OCR ao PATH do Sistema:

💿 Após a instalação, você precisa adicionar o diretório onde o Tesseract foi instalado ao PATH do sistema para que você possa acessá-lo facilmente a partir da linha de comando.

💻 Para fazer isso, clique com o botão direito do mouse em "Este Computador" (ou "Meu Computador"), selecione "Propriedades" e, em seguida, clique em "Configurações avançadas do sistema".

💻 Na janela Propriedades do Sistema, clique em "Variáveis de Ambiente".

💻 Na seção "Variáveis do Sistema", selecione a variável PATH e clique em "Editar".

💻 Na janela Editar Variável de Sistema, clique em "Novo" e adicione o caminho para o diretório onde o Tesseract foi instalado (por exemplo, C:\Program Files\Tesseract-OCR).

💻 Clique em "OK" em todas as janelas para salvar suas alterações.

## ⬛ Testar a Instalação:

```
tesseract --version
```

⬛ Abra o Prompt de Comando do Windows e execute o seguinte comando para verificar se o Tesseract foi instalado corretamente e está acessível a partir da linha de comando:

⬛ Você deverá ver a versão do Tesseract OCR sendo exibida no Prompt de Comando, indicando que a instalação foi bem-sucedida.

## 🖼 Preparação da Imagem:

🖼 Antes de usar o Tesseract OCR, você precisa ter uma imagem contendo o texto que deseja reconhecer. Certifique-se de que a qualidade da imagem seja boa e que o texto seja claro e legível.

## ⬛ Executar o Tesseract OCR via Linha de Comando:

⬛ Abra o Prompt de Comando do Windows.

⬛ Navegue até o diretório onde está a imagem que deseja processar. Você pode fazer isso usando o comando cd (por exemplo, cd caminho/para/o/diretorio).

⬛ Uma vez no diretório correto, você pode executar o comando tesseract seguido do nome do arquivo de imagem que deseja processar e o nome do arquivo de saída onde o texto reconhecido será salvo. Por exemplo:

```
tesseract imagem.png texto_reconhecido
```

🔎 Neste exemplo, imagem.png é o nome do arquivo de imagem que você deseja processar e texto_reconhecido é o nome do arquivo de saída onde o texto reconhecido será salvo. O Tesseract OCR irá processar a imagem e salvar o texto reconhecido no arquivo especificado, acrescentando a extensão .txt.

Verificar o Resultado:

📃 Depois que o Tesseract OCR terminar de processar a imagem, você pode verificar o arquivo de saída para ver o texto reconhecido. Você pode abrir o arquivo de texto usando um editor de texto, como o Bloco de Notas do Windows, para visualizar o texto reconhecido.
