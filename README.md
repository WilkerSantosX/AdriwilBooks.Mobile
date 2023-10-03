# AdriwilBooks.Mobile
Aplicativo mobile que faz a interface gráfica para localização de documentos na Web. Documentos pdf, xls, txt, doc, entre outros. <br><br>

## VISÃO MACRO

A imagem abaixo ilustra a arquitetura/estrutura macro de comunicação e funcionamento do aplicativo ADRIWIL BOOKS.

![Imagem do WhatsApp de 2023-10-02 à(s) 21 44 50_452f96c1](https://github.com/WilkerSantosX/AdriwilBooks.Mobile/assets/136654507/10d6e7da-eeb5-470c-b06e-f2de6f280958) <br><br>

## ESTRUTURA E DADOS
Sendo o banco de dados um arquivo simples (JSON) disponibilizado na seguinte URL: 
- https://adriwil.com.br/json/booklist.json

A estrutura do JSON consiste:

| Propriedade | Tipo    | Obrigatório | Value Default |  Descrição
| :--------:  | :-----: | :---------: | :-----------: |  :-----------: 
| author      | string  | Sim         |               |  Nome do autor do arquivo
| book        | string  | Sim         |               |  Nome do arquivo
| path        | string  | Sim         |               |  URL onde o arquivo está
| urlImage    | string  | Sim         |   Vazio       |  URL da imagem da capa do arquivo
| yearBook    | int     | Sim         |     0         |  Ano do arquivo

<br>

## FERRAMENTAS USADAS

- Android Studio
- Emulador
- Excel
- Notepad++<br><br>

## INSERÇÃO DE DADOS NO APLICATIVO
1.	O arquivo precisa estar disponível em algum link da internet.
2.	Alimentar as informações no json modelo.
3.	Atualizar o json no ambiente ADRIWIL.<br><br>

## ARQUIVO AUXILIAR
Para ajudar a compor a lista de objetos json
[booklist.xlsx](https://github.com/WilkerSantosX/AdriwilBooks.Mobile/files/12795514/booklist.xlsx)

<br>

```yaml 
{
  "author":"Wilker Santos", 
  "book":"Eurídice e Orfeu", 
  "path":"https://docs.google.com/document/...", 
  "urlImage":"", 
  "yearBook": 0 
} 

