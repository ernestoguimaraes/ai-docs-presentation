# Do documento à decisão · Demo Microsoft Foundry

Página animada que mostra um agente no Microsoft Foundry percorrendo um processo de negócio de ponta a ponta:

1. Entrada multicanal
2. Planejamento do agente
3. Extração de documentos
4. Grounding em conhecimento corporativo
5. Ferramentas e APIs
6. Aprovação humana
7. Execução, auditoria e melhoria contínua

## Como publicar

1. Crie um repositório no GitHub (ex.: `foundry-demo`).
2. Envie todo o conteúdo desta pasta, incluindo `.github/workflows/pages.yml`, para a branch `main`.
3. No repositório, abra **Settings → Pages** e, em **Source**, selecione **GitHub Actions**.
4. O workflow publica automaticamente. A URL fica em `https://<seu-usuario>.github.io/foundry-demo/`.

## Download

A página publicada tem o botão **⬇ Baixar** no cabeçalho e um link no rodapé, que baixam a demo como `foundry-demo.html` para uso offline.

## Controles

- `←` / `→`: etapa anterior / próxima
- `Espaço`: pausar / reproduzir
- Clique em qualquer etapa da linha do tempo para pular direto

> Os valores exibidos na animação são fictícios e servem apenas para ilustração.
