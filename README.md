Assistente SENAI Diadema

Chatbot web para tirar dúvidas sobre a Escola SENAI "Manuel Garcia Filho" (Diadema/SP): cursos, matrículas, vestibulinho, contato e muito mais. Construído em HTML, CSS e JavaScript puro, sem frameworks, sem npm, sem servidor. Basta abrir o arquivo no navegador.

Funcionalidades

Chat com histórico: mantém o contexto da conversa entre perguntas, não é uma pergunta única e tchau.

Streaming em tempo real: as respostas vão aparecendo aos poucos, como um chat de verdade, usando Server-Sent Events da API do OpenRouter.

Enter para enviar e Shift mais Enter para quebrar linha, como em qualquer app de mensagens.

Perguntas sugeridas: clique em uma delas e o texto já vai para o campo de pergunta.

Design nas cores do SENAI, branco e vermelho, com informações de contato da unidade sempre visíveis.

Formatação automática: remove símbolos de markdown e exibe o texto de forma limpa e legível.

Sem backend: sua chave de API fica só no seu navegador, nada é salvo ou enviado para outro lugar além da OpenRouter.

Como usar

Baixe o arquivo senai-diadema-assistente.html.
Abra o arquivo diretamente no navegador, com duplo clique ou arrastando para uma aba.
Crie uma conta gratuita em openrouter.ai e gere uma chave de API.
Cole a chave no campo Chave de API do OpenRouter.
Digite sua pergunta e envie, pronto, é só conversar.

Nenhuma instalação, build ou servidor é necessário.

Sobre o modelo de IA

O assistente usa o modelo nvidia/nemotron-3-ultra-550b-a55b:free via OpenRouter, com um prompt de sistema que restringe as respostas a temas do universo SENAI: história da instituição, cursos técnicos, aprendizagem industrial, vestibulinho, matrículas, corpo docente, infraestrutura e contato da unidade de Diadema.

Informações da unidade

Nome: Escola SENAI Manuel Garcia Filho
Endereço: Rua Guatemala, 19, Jardim Canhema, Diadema, SP, CEP 09941-140
Telefone: (11) 4070-8950
E-mail: senaidiadema@sp.senai.br
Site: diadema.sp.senai.br

Tecnologias

HTML5, CSS3 sem frameworks, JavaScript puro com Fetch API e Streams API, e a API do OpenRouter para o modelo de linguagem.

Aviso

Este é um projeto não-oficial, feito de forma independente. As informações de contato foram obtidas de fontes públicas do SENAI-SP. Em caso de dúvida, confirme sempre pelos canais oficiais da instituição.

Licença

Projeto de uso livre para fins educacionais.
