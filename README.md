# Kanban de OPs — Belmonte Indústria

Sistema de gestão de Ordens de Produção (Ferro & Alumínio): quadro Kanban, cronograma (Gantt) e boletim de entrega para copiar em e-mail.

## ⚠️ Leia antes de usar fora do Claude

Este arquivo foi originalmente criado dentro do Claude, onde os dados ficavam salvos numa nuvem própria da Anthropic. Rodando aqui no GitHub Pages, os dados passam a ser salvos no **`localStorage` do seu navegador**. Isso muda algumas coisas importantes:

- Os dados ficam **só no navegador/computador onde você usou** — não sincronizam automaticamente entre celular, outro PC, ou outro navegador (ex: Chrome vs Edge).
- Se você limpar o cache/dados de navegação do navegador, **os dados somem**.
- **Use o botão "⬇ Exportar" com frequência** (ex: toda sexta-feira) para baixar um backup em `.json`. Se algo der errado, use "⬆ Importar" para restaurar.

Se você já tinha OPs cadastradas na versão dentro do Claude, exporte-as por lá (o botão Exportar já existe na versão de lá também) antes de migrar, e depois importe esse arquivo aqui no GitHub Pages.

## Como publicar no GitHub Pages (passo a passo)

1. **Crie um repositório novo no GitHub**
   - Acesse [github.com/new](https://github.com/new)
   - Dê um nome, ex: `kanban-op-belmonte`
   - Marque como **Public** (o GitHub Pages gratuito exige repositório público)
   - Clique em "Create repository"

2. **Envie o arquivo `index.html`**
   - Na página do repositório recém-criado, clique em "uploading an existing file" (ou "Add file" → "Upload files")
   - Arraste o arquivo `index.html` (deste pacote) para lá
   - Clique em "Commit changes"

3. **Ative o GitHub Pages**
   - No repositório, vá em **Settings** → **Pages** (menu lateral esquerdo)
   - Em "Build and deployment" → "Source", selecione **Deploy from a branch**
   - Em "Branch", selecione `main` e a pasta `/ (root)`
   - Clique em "Save"

4. **Aguarde 1–2 minutos**
   - O GitHub vai te dar um link parecido com:
     `https://SEU-USUARIO.github.io/kanban-op-belmonte/`
   - Esse é o endereço do seu sistema — pode salvar nos favoritos, mandar pro celular, etc.

## Atualizando o sistema depois

Sempre que eu (Claude) fizer uma melhoria nova, é só:
1. Baixar o `index.html` atualizado
2. No GitHub, ir no arquivo `index.html` do repositório → ícone de lápis (editar) → apagar tudo → colar o conteúdo novo → "Commit changes"
   - Ou: fazer upload do arquivo de novo (mesmo nome, ele substitui)
3. O site atualiza sozinho em ~1 minuto

**Seus dados não são afetados por essa atualização** — eles ficam salvos no navegador, separados do arquivo de código.

## Backup — recomendado

- Semanalmente, clique em **⬇ Exportar** e guarde o arquivo `.json` baixado em algum lugar seguro (Google Drive, e-mail para você mesmo, etc.)
- Se precisar restaurar (trocou de computador, limpou o navegador, etc.), clique em **⬆ Importar** e selecione esse arquivo
