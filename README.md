# Calculadora · fx

Calculadora científica em página única, feita por **Danilo Gomes**.

Funciona 100% offline (todo o cálculo roda no próprio arquivo, sem depender de internet). Pode ser instalada como app na tela inicial do iPhone e do Android.

## Recursos

- Operações básicas: `+`, `−`, `×`, `÷`, `%`, `±`
- Funções científicas: `sin`, `cos`, `tan`, `ln`, `log`, `√`, `x²`, `xʸ`, `π`, `e`, fatorial (`n!`), `1/x`
- Alternância entre graus (`DEG`) e radianos (`RAD`)
- Expressões completas com pré-visualização do resultado ao vivo
- Teclado físico funciona quando aberta no computador
- Layout adaptado a toque, com suporte à área segura do iPhone (notch / ilha dinâmica)

---

## Como publicar no GitHub Pages (passo a passo)

O resultado é um link público, tipo `https://SEU-USUARIO.github.io/calculadora/`, que abre funcionando em qualquer aparelho.

1. **Crie o repositório**
   - Entre em github.com e clique em **New** (novo repositório).
   - Nome sugerido: `calculadora`.
   - Marque como **Public**.
   - Clique em **Create repository**.

2. **Envie os arquivos**
   - Na página do repositório, clique em **Add file → Upload files**.
   - Arraste os arquivos `index.html` e `README.md` (e o `.nojekyll`, se aparecer).
   - Clique em **Commit changes**.

3. **Ative o GitHub Pages**
   - Vá em **Settings** (aba no topo do repositório).
   - No menu lateral, clique em **Pages**.
   - Em **Source**, escolha **Deploy from a branch**.
   - Em **Branch**, selecione **main** e a pasta **/ (root)**.
   - Clique em **Save**.

4. **Pegue o link**
   - Aguarde cerca de 1 minuto e atualize a página de **Pages**.
   - O link aparece no topo: `https://SEU-USUARIO.github.io/calculadora/`.
   - Pronto — é só abrir ou compartilhar.

---

## Instalar como app no celular

Abra o link no navegador e:

- **iPhone (Safari):** botão Compartilhar → **Adicionar à Tela de Início**.
- **Android (Chrome):** menu (⋮) → **Adicionar à tela inicial** / **Instalar app**.

Depois de aberta uma vez, funciona sem internet.

---

## Observações técnicas

- Um único arquivo `index.html`, sem dependências externas nem bibliotecas.
- O ícone da tela inicial está embutido no próprio HTML (`apple-touch-icon` em base64).
- O arquivo `.nojekyll` evita que o GitHub Pages processe o site com Jekyll (não é essencial aqui, mas é boa prática).
