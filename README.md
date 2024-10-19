# pdfExtratorFront_end
Componente de Verificação de Texto em PDF
Este componente React permite ao usuário selecionar um arquivo PDF e verificar se ele contém uma palavra ou texto específico. O arquivo PDF é enviado a uma API, que realiza a análise do conteúdo e retorna se o texto procurado foi encontrado.

Fluxo de Funcionamento:
O usuário faz o upload de um arquivo PDF a partir da interface do componente.
O usuário insere a palavra ou texto que deseja verificar no PDF.
O componente envia o arquivo e o texto de busca para uma API externa que realiza a análise do conteúdo do PDF.
A API responde se o texto ou palavra está presente no documento.
O resultado é exibido na tela para o usuário, indicando se o texto foi encontrado ou não.
Funcionalidades:
Upload de arquivos PDF.
Entrada de texto para especificar a palavra ou frase a ser verificada.
Integração com uma API externa que processa o conteúdo do PDF.
Exibição de resultados em tempo real, com feedback ao usuário (carregamento, sucesso, erro).
Objetivo:
Este componente é útil para aplicações onde seja necessário verificar automaticamente a presença de termos ou frases específicas em documentos PDF, como em processos de revisão, validação de documentos ou automação de tarefas de busca textual.
