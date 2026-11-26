# Rastro Científico

**Edição CNPq | Versão 0.4.2**

<sub>⬇️ **[Baixar a versão 0.4.2](https://github.com/rodrigonsf/rastro_cientifico/releases/tag/v0.4.2)** · [Instruções de download](DOWNLOAD.md)</sub>

Ferramenta de apoio ao registro e à documentação do uso de Inteligência Artificial Generativa (IAG) e Inteligência Artificial Preditiva (IAP) na pesquisa científica.

A Edição CNPq foi desenvolvida com base na **Portaria CNPq nº 3.004/2026**, na Política de Integridade na Atividade Científica (**Portaria CNPq nº 2.664/2026**) e na Lei Geral de Proteção de Dados Pessoais (**LGPD**), apoiando o registro das utilizações de IA e a elaboração de declarações conforme as diretrizes aplicáveis.

## Acesso rápido à documentação

**[📘 Manual de utilização](docs/manual-de-utilizacao.md)**

Consulte o guia passo a passo para abrir a aplicação, cadastrar pesquisas, registrar utilizações de IA, gerar declarações e salvar versões históricas.

- [Manual de backup e transferência de dados](docs/manual-de-backup-e-dados.md)
- [Documentação completa da plataforma](docs/documentacao-da-plataforma.md)
- [Aviso de escopo e responsabilidades](docs/DISCLAIMER.md)
- [Referencial normativo preliminar](docs/MARCO_NORMATIVO_REFERENCIAL.md)

## Começar a utilizar

1. Baixe o pacote ZIP da versão desejada na área de Releases.
2. Extraia o arquivo.
3. Abra `index.html` em um navegador moderno, preferencialmente Google Chrome ou Microsoft Edge.
4. Cadastre uma pesquisa e registre cada ferramenta utilizada em um registro próprio.
5. Gere, revise e salve a declaração correspondente.

A versão distribuída é executada diretamente no navegador. Não exige instalação de Node.js, npm, servidor ou compilação.

## Funcionalidades

- Cadastro de pesquisas.
- Registro individual de utilizações de IAG e IAP.
- Identificação de ferramenta, modelo e versão, quando conhecidos.
- Registro da fase e da finalidade específica de cada utilização.
- Registro de intervenção humana e procedimentos de verificação/validação.
- Informação sobre treinamento de modelos nos registros de IAP.
- Geração e revisão de declaração consolidada.
- Preservação de declarações históricas.
- Impressão ou salvamento de declarações em PDF pelo navegador.
- Exportação e restauração de backup em JSON.

## Armazenamento e privacidade

Os dados são armazenados localmente no navegador, por meio do IndexedDB. Esta versão não oferece contas de usuário, sincronização em nuvem ou colaboração simultânea. Para transferir dados entre navegadores ou computadores, utilize o backup JSON.

O armazenamento local não equivale a criptografia. Proteja o dispositivo e os arquivos de backup. Evite inserir dados pessoais, sensíveis, sigilosos ou confidenciais desnecessários.

## Limites

O Rastro Científico não executa ferramentas de IA, não verifica automaticamente a veracidade de respostas, dados ou referências, não detecta plágio, não apura denúncias, não emite parecer jurídico e não certifica conformidade normativa.

A declaração gerada é um rascunho. Os pesquisadores devem revisar e validar o conteúdo final e verificar as exigências aplicáveis à sua pesquisa, instituição, agência de fomento ou periódico.

Consulte [docs/DISCLAIMER.md](docs/DISCLAIMER.md) para os limites e responsabilidades da plataforma.

## Documentação

- [Documentação da plataforma](docs/documentacao-da-plataforma.md)
- [Manual de utilização](docs/manual-de-utilizacao.md)
- [Manual de backup e transferência de dados](docs/manual-de-backup-e-dados.md)
- [Aviso de escopo e responsabilidades](docs/DISCLAIMER.md)
- [Referencial normativo preliminar](docs/MARCO_NORMATIVO_REFERENCIAL.md)
- [Documentação técnica do software (Markdown)](docs/documentacao-tecnica-do-software.md)
- [Documentação técnica do software (PDF)] - Documento Suprimido
- [Como contribuir](CONTRIBUTING.md)

## Edições do projeto

O projeto prevê duas edições:

- **CNPq:** primeira edição implementada.
- **Geral:** edição futura, com orientações adicionais para pesquisadores de diferentes instituições e contextos.

A Edição Geral não integra a versão 0.4.2.

## Repositórios

- [GitLab](https://git.ufrj.br/rodrigonsf/rastro_cientifico)
- [GitHub](https://github.com/rodrigonsf/rastro_cientifico)

## Versão

- Produto: Rastro Científico
- Edição: CNPq
- Versão: 0.4.2
- Situação: versão candidata à homologação ampliada.
- Aplicação: arquivo HTML independente.
- Persistência: IndexedDB local.
- Backup: JSON.
