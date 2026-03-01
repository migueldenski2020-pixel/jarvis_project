# Todas as funções de Jarvis:
1. Núcleo de Automação do Windows (As Mãos)
O Jarvis deve ter permissão de administrador para manipular o sistema operacional sem restrições.
Execução de Aplicativos: Abrir e fechar qualquer software (VS Code, Discord, Navegador, Jogos) via comandos de voz ou gatilhos de contexto.
Gestão de Janelas: Organizar a área de trabalho (ex: "Jarvis, modo de estudo" abre o VS Code na esquerda e a documentação na direita).
Manipulação de Arquivos: Mover, renomear, deletar ou organizar pastas de projetos automaticamente.
Controle de Hardware: Alterar brilho, volume, plano de energia (economia vs. performance) e monitorar a temperatura da CPU/GPU integrada.
2. Agente Acadêmico Autônomo (O Estagiário)
Esta função deve rodar em Background Threading para não interferir na sua latência de voz ou no seu código.
Web Scraping Técnico: Pesquisar temas (como Biologia) em fontes confiáveis (Artigos, Wikipedia, Documentações) e extrair dados brutos.
Redação de Documentos: Gerar arquivos .docx ou .pdf formatados. Enquanto você programa, ele processa o texto, cria a introdução, desenvolvimento e conclusão baseada nos dados coletados.
Síntese de Conhecimento: Ele deve ser capaz de te dar um "briefing" por voz: "Senhor, terminei o trabalho de Biologia sobre Mitocôndrias. Resumo: elas são as usinas de força da célula. O arquivo está na sua área de trabalho."
Tradução e Resumo: Ler PDFs técnicos em inglês e traduzi-los para você em tempo real.
3. Orquestrador de Performance (Sobrevivência)
Dado que você opera com 497MB de VRAM, esta função é a mais crítica para manter o sistema estável.
VRAM Watchdog: Monitorar o uso de memória de vídeo. Se o Ollama ou o Windows ocupar demais, ele deve suspender processos não essenciais automaticamente.
Limpeza Automática: Deletar arquivos temporários, __pycache__ e limpar a lixeira para manter o SSD ágil.
Otimização de Compilação: Identificar quando você salva um código e sugerir correções ou rodar testes unitários em segundo plano.
4. Interface de Personalidade Stark (O Protocolo de Sarcasmo)
Aqui aplicamos o que está no seu base.jsonl.
Filtro de Relevância: Se você fizer uma pergunta óbvia, ele deve responder com o sarcasmo configurado.
Níveis de Resposta:
Modo Analítico: Respostas puramente técnicas e curtas.
Modo Stark: Respostas com humor ácido e observações sobre a sua produtividade.
Reconhecimento de Contexto: Se você estiver errando o código por muito tempo, ele pode intervir: "Senhor, talvez se você parar de encarar o erro e realmente digitar o comando correto, nós terminemos isso antes do próximo século."
5. Segurança e Sentinela (Proteção de Dados)
Bloqueio de Estação: O que você já tem, mas com log de quem passou pela frente da webcam.
Criptografia de Memória: Proteger a base.json para que as suas informações de login ou preferências não sejam acessíveis por outros scripts
