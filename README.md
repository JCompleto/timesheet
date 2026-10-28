# Folha de Horas

App de telemóvel para registar horas por cliente e projeto (4h ou 8h) e consultar a folha de horas por dia e por mês.

- Os registos ficam guardados **só no telemóvel**, no browser. Este repositório tem apenas o código, nunca os teus dados.
- Funciona sem internet depois da primeira abertura.
- **Nunca coloques aqui o ficheiro de cópia de segurança (`.json`)**: tem todos os teus registos.

## Publicar no GitHub Pages

1. Cria uma conta em https://github.com (se ainda não tiveres).
2. Cria um repositório novo: botão **New**, nome `folha-de-horas`, visibilidade **Public**, **Create repository**.
3. Na página do repositório, carrega em **uploading an existing file** (ou **Add file › Upload files**).
4. Arrasta **o conteúdo desta pasta** (o `index.html`, o `manifest.webmanifest`, o `sw.js`, o `README.md` e a pasta `icons`). Não arrastes a pasta exterior nem o zip.
5. Carrega em **Commit changes**.
6. Vai a **Settings › Pages**. Em **Branch** escolhe `main` e a pasta `/ (root)`, e carrega em **Save**.
7. Ao fim de um ou dois minutos aparece o endereço, do género `https://o-teu-utilizador.github.io/folha-de-horas/`.

## Instalar no telemóvel

- **iPhone (Safari):** abre o endereço › botão de partilhar › **Adicionar ao ecrã principal**.
- **Android (Chrome):** abre o endereço › menu **⋮** › **Instalar app** ou **Adicionar ao ecrã principal**.

Usa sempre o ícone do ecrã principal. No iPhone, o ícone guarda os registos à parte do Safari.

## Passar os registos da versão do claude.ai

1. Na versão antiga: **Configurar › Guardar cópia**.
2. Na app instalada: **Configurar › Restaurar cópia** e escolhe o ficheiro.

## Atualizar a app mais tarde

Substitui os ficheiros no repositório e, no `sw.js`, muda `folha-horas-v1` para `folha-horas-v2` (e assim sucessivamente). Na próxima vez que abrires a app com internet, ela atualiza-se. Os registos mantêm-se.
