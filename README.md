# TW Clothes — Calculadora de PVP

Calculadora estática, instalável e com funcionamento offline. Não utiliza backend e não guarda encomendas centralmente.

Esta versão inclui o logótipo oficial da TW Clothes no cabeçalho, nas cotações, no favicon e nos ícones de instalação.

Cada artigo pode receber uma fotografia do telefone. A imagem é utilizada na cotação e num post quadrado 1:1, criado localmente no aparelho, com:

- logótipo no canto superior esquerdo;
- descrição no cabeçalho;
- preço sobreposto no canto inferior direito;
- opção para partilhar ou guardar a imagem.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub, por exemplo `tw-clothes-calculator`.
2. Envie **todos os ficheiros deste pacote** para a raiz do repositório.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Seleccione a branch `main`, a pasta `/(root)` e carregue em **Save**.
6. Aguarde a publicação e abra o endereço apresentado pelo GitHub.

Não altere os caminhos `./` dos ficheiros: foram preparados para funcionar tanto num domínio próprio como numa subpasta do GitHub Pages.

## Instalar no iPhone

1. Abra o endereço publicado no Safari.
2. Toque em **Partilhar**.
3. Escolha **Adicionar ao ecrã principal**.
4. Confirme em **Adicionar**.

Depois da primeira abertura online, a calculadora pode funcionar sem ligação à internet. Se publicar uma actualização, abra-a uma vez com internet para receber a versão nova.

## Gerar uma cotação

Preencha os artigos, acrescente as fotografias pretendidas e carregue em **Gerar cotação / PDF**. No ecrã de impressão do iPhone, abra a pré-visualização e use **Partilhar** para guardar ou enviar o PDF.

## Gerar um post 1:1

Depois de acrescentar a imagem de um artigo, carregue em **Post 1:1** na respectiva linha. Pode partilhar o post directamente ou guardar a imagem PNG.

## Regras de cálculo

- Compra: preço em EUR × câmbio.
- Transporte: maior valor entre peso total × tarifa/kg e o mínimo.
- Transporte repartido igualmente pelo número de artigos.
- O custo total da sacola é repartido igualmente por todos os artigos.
- Acréscimo predefinido: 30%.
- PVP arredondado ao múltiplo escolhido e reduzido em 10 MT: 3 000 → 2 990 e 3 050 → 3 040.
- O resumo apresenta o lucro estimado total do lote.

Os pressupostos podem ser alterados dentro da calculadora.
