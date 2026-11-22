# Carregamento – Coletor

App offline (PWA) para o **carregamento (expedição)** dos fardos: escolhe a ordem de carregamento,
confere a placa (com foto), lê a etiqueta de cada fardo com o gatilho (leitor) do coletor
e confere lote e quantidade pedida. Feito para o coletor Chainway C72 (ou celular).

- Carrega o **pacote** gerado no app principal (Carregamento 🚚 › Pacote para o coletor).
- Funciona **sem internet** depois de instalado ("Adicionar à tela inicial").
- Exporta o arquivo de **cargas** (leituras + fotos) para importar no app principal.

Nenhum dado de ordens, lotes ou fardos fica neste repositório: os dados ficam só nos aparelhos.

**Segurança:** só conta fardo com a etiqueta lida pelo gatilho do coletor (sem câmera e sem campo visível para digitar). Número digitado (ou colado) não conta, trava a tela e fica registrado à parte na carga (`dig`), fora da contagem e dos alertas. Fardo não encontrado: feche a carga como incompleta e informe o motivo.
