Projeto de Engenharia de Qualidade - Rede Raízes do Nordeste

Este repositório armazena as evidências práticas e os artefatos de validação desenvolvidos para o ecossistema integrado da rede de lanchonetes **Raízes do Nordeste**, atendendo aos critérios da Trilha de Qualidade de Software do Projeto Multidisciplinar.

👨‍🎓 Identificação do Autor
- Estudante: Rodrigo Teixeira Leandro
- RU: 4753868
- Instituição: Centro Universitário Internacional UNINTER
- Curso: Tecnologia em Análise e Desenvolvimento de Sistemas (2026)

Estrutura dos Artefatos de Teste

O repositório está organizado de forma unificada para validar a abordagem omnichannel (App Mobile, Totem, Balcão e Web) sem fatiamento de fases:

`raizes_nordeste_postman_collection.json`: Coleção oficial do Postman contendo as requisições HTTP RESTful para os testes funcionais de contrato e validação de endpoints do API Gateway (ex: rotas de checkout e logs de consentimento da LGPD).
`teste_carga_jmeter.jmx`: Script de configuração de estresse do Apache JMeter. Configurado para injetar 500 conexões concorrentes simultâneas por segundo para homologar o comportamento e resiliência da infraestrutura durante horários de pico comerciais.

Como Executar os Testes

1. Testes de API (Postman)
1. Faça o download do arquivo `raizes_nordeste_postman_collection.json` contido neste repositório.
2. Abra o Postman e clique em Import.
3. Selecione o arquivo baixado para carregar a coleção com as rotas integradas.

2. Testes de Estresse (Apache JMeter)
1. Certifique-se de possuir o Java JDK e o Apache JMeter instalados na máquina.
2. Baixe o arquivo `teste_carga_jmeter.jmx`.
3. Execute o JMeter via terminal e abra o script para visualizar o Grupo de Usuários configurado para alta carga.

*Nota: Este repositório cumpre as diretrizes administrativas de integridade e comprovação de autoria exigidas no AVA-Univirtus.*
