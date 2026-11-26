# Documentação da Plataforma Rastro Científico

**Produto:** Rastro Científico  
**Edição documentada:** CNPq  
**Versão de referência:** 0.4.2  
**Situação:** versão candidata à homologação  
**Identificador dos repositórios:** `rastro_cientifico`

---

## 1. Apresentação

O **Rastro Científico** é uma ferramenta de apoio à documentação do uso de Inteligência Artificial (IA) em atividades de pesquisa científica.

A plataforma permite que pesquisadores organizem informações sobre a participação de ferramentas de Inteligência Artificial Generativa (IAG) e Inteligência Artificial Preditiva (IAP) em diferentes etapas de uma pesquisa. Com base nos registros realizados, o sistema gera um rascunho de declaração de uso de IA que pode ser revisado, complementado e preservado pelo pesquisador.

O Rastro Científico parte de uma necessidade prática: tornar mais clara e recuperável a informação sobre quais ferramentas foram utilizadas, em que etapa da pesquisa e com qual finalidade.

A ferramenta documenta os usos de IA. Ela não executa as atividades de pesquisa nem substitui os sistemas utilizados para produzir, analisar ou administrar conhecimento científico.

## 2. Finalidade

A finalidade do Rastro Científico é apoiar:

- a organização das informações sobre o uso de IA em pesquisas;
- a identificação das ferramentas e dos modelos utilizados, quando conhecidos;
- o registro das etapas da pesquisa em que houve utilização de IA;
- a descrição da finalidade específica de cada utilização;
- a documentação da intervenção humana e dos procedimentos de verificação informados pelo pesquisador;
- a elaboração e a preservação de declarações de uso de IA.

A plataforma busca contribuir para a transparência metodológica, a rastreabilidade das utilizações e a responsabilidade dos pesquisadores pelo conteúdo final de seus trabalhos.

## 3. Público a que se destina

A ferramenta foi concebida para pesquisadores, estudantes de pós-graduação, docentes e demais pessoas que precisem documentar a utilização de IA em atividades de pesquisa científica.

A versão 0.4.2 corresponde exclusivamente à **Edição CNPq**. Sua configuração foi organizada para apoiar a documentação relacionada às diretrizes do Conselho Nacional de Desenvolvimento Científico e Tecnológico, observada a incidência das normas sobre cada agente e atividade.

Uma futura **Edição Geral** poderá contemplar pesquisadores de diferentes instituições e contextos, com recursos adicionais de documentação. Essa edição não integra a versão 0.4.2.

## 4. Edição CNPq

A Edição CNPq tem como referências normativas principais:

- **Portaria CNPq nº 2.664/2026:** institui a Política de Integridade na Atividade Científica do CNPq.
- **Portaria CNPq nº 3.004/2026:** estabelece diretrizes para o uso de Inteligência Artificial Generativa e Inteligência Artificial Preditiva na pesquisa científica apoiada pelo CNPq.

A aplicação foi estruturada para apoiar o registro das informações relacionadas ao uso de IAG, especialmente ferramenta, versão quando disponível, etapa da pesquisa e finalidade específica.

Para IAP, a plataforma registra a utilização e permite indicar se o projeto envolve treinamento de modelos. Essa informação é relevante para a hipótese de declaração formal prevista no art. 9º da Portaria CNPq nº 3.004/2026.

A ferramenta não determina automaticamente a incidência das normas em cada caso. O pesquisador deve considerar sua condição, a atividade realizada, as regras institucionais e as orientações aplicáveis ao projeto, à submissão ou à publicação.

## 5. Conceitos utilizados

### 5.1. Inteligência Artificial Generativa (IAG)

Na plataforma, IAG corresponde a sistemas capazes de gerar ou transformar conteúdos, como textos, imagens, códigos e áudios, a partir de instruções ou entradas fornecidas pelo usuário.

Exemplos de atividades que podem envolver IAG:

- revisão ou reorganização de texto;
- sumarização de documentos;
- tradução;
- geração ou correção de código;
- apoio à elaboração de perguntas;
- produção de imagens ou outros conteúdos.

### 5.2. Inteligência Artificial Preditiva (IAP)

Na plataforma, IAP corresponde a modelos computacionais baseados em técnicas estatísticas, probabilísticas ou de aprendizado de máquina, utilizados para classificação, agrupamento, inferência, reconhecimento de padrões, previsão ou apoio à tomada de decisão.

A classificação deve considerar a funcionalidade efetivamente utilizada. O nome de uma ferramenta, isoladamente, não determina se o uso foi de IAG ou IAP.

Por exemplo, Python e R são linguagens e ambientes de programação. Seu uso não caracteriza automaticamente IAP. É necessário considerar se foram empregados para executar técnicas preditivas ou de aprendizado de máquina.

### 5.3. Uma utilização por registro

Cada registro de utilização corresponde a uma ferramenta em uma pesquisa. Quando diferentes ferramentas participarem da mesma pesquisa, devem ser criados registros separados, vinculados à mesma pesquisa.

Essa organização permite descrever individualmente a finalidade e a etapa de cada utilização.

## 6. Funcionalidades da plataforma

### 6.1. Cadastro de pesquisas

Permite cadastrar pesquisas que servirão de referência para os registros de utilização de IA.

O cadastro contempla o título da pesquisa e informações complementares, como área do conhecimento e descrição.

### 6.2. Registro de utilizações de IA

Permite registrar cada utilização de IAG ou IAP e vinculá-la a uma pesquisa.

Os registros contemplam:

- tipo de IA: IAG ou IAP;
- ferramenta utilizada;
- especificação da ferramenta, quando selecionada a opção “Outros”;
- modelo utilizado, quando conhecido;
- versão, quando conhecida;
- fase da pesquisa;
- finalidade específica;
- intervenção humana informada;
- procedimentos de verificação e validação informados;
- indicação de treinamento de modelos, nos registros de IAP.

Os campos de intervenção humana e verificação/validação permitem documentar informações adicionais sobre o tratamento dado aos resultados. Seu preenchimento não representa uma certificação automática da qualidade desses procedimentos.

### 6.3. Geração de declaração

A plataforma reúne os registros associados a uma pesquisa e gera um rascunho consolidado de declaração de uso de IA.

A declaração apresenta seções distintas para IAG e IAP. O texto também contempla a responsabilidade dos pesquisadores pelo conteúdo final e orienta a revisão humana antes da utilização.

O usuário pode revisar e complementar o texto gerado.

### 6.4. Preservação de declarações históricas

Depois da revisão, a declaração pode ser salva como versão histórica.

A versão preservada mantém o texto e uma cópia dos registros utilizados em sua geração. Alterações posteriores nos registros de origem não devem modificar automaticamente a declaração histórica.

Quando houver necessidade de refletir novas informações, o pesquisador poderá gerar e salvar outra declaração.

### 6.5. Impressão e geração de PDF

A declaração pode ser encaminhada à impressão pelo navegador. Na janela de impressão, o usuário pode selecionar uma impressora ou utilizar a opção de salvar como PDF.

A conferência do documento final e de sua adequação às regras do destinatário permanece sob responsabilidade dos pesquisadores.

### 6.6. Backup e restauração

A plataforma permite exportar os dados em arquivo JSON e restaurar esse arquivo em outra instalação da aplicação ou em outro navegador.

O backup é o meio de transferência dos registros entre navegadores, perfis ou computadores nesta edição.

## 7. Fluxo geral de utilização

O fluxo recomendado é:

1. Cadastrar a pesquisa.
2. Identificar as ferramentas de IA utilizadas.
3. Criar um registro separado para cada ferramenta.
4. Classificar cada utilização como IAG ou IAP, conforme a atividade efetivamente realizada.
5. Informar ferramenta, modelo e versão, quando conhecidos.
6. Indicar a fase da pesquisa e descrever a finalidade específica.
7. Registrar, quando pertinente, a intervenção humana e os procedimentos de verificação e validação.
8. Nos registros de IAP, informar se o projeto envolve treinamento de modelos, quando essa condição puder ser identificada.
9. Gerar o rascunho da declaração.
10. Revisar e complementar o texto.
11. Salvar a declaração como versão histórica.
12. Imprimir ou salvar em PDF, se necessário.
13. Exportar backups periodicamente.

O passo a passo de cada operação está disponível no [Manual de utilização](manual-de-utilizacao.md) e no [Manual de backup e dados](manual-de-backup-e-dados.md).

## 8. Organização das informações

A plataforma trabalha com três conjuntos principais de informações:

| Conjunto | Finalidade |
|---|---|
| Pesquisas | Identificar os trabalhos científicos documentados |
| Utilizações de IA | Registrar as ferramentas e as atividades realizadas com auxílio de IA |
| Declarações | Preservar os textos gerados, revisados e associados aos registros de origem |

Uma pesquisa pode ter várias utilizações de IA. Cada utilização pertence a uma pesquisa. Uma pesquisa também pode ter diferentes versões históricas de declaração.

Essa organização permite documentar o uso de IA sem exigir que o pesquisador registre a pesquisa inteira na plataforma.

## 9. Armazenamento e proteção das informações

Na versão 0.4.2, os dados são armazenados localmente no navegador, por meio do IndexedDB.

Características desse modelo:

- não exige criação de conta;
- não oferece sincronização automática em nuvem;
- não possui colaboração simultânea entre usuários;
- não transfere automaticamente os dados para outro navegador ou computador;
- utiliza arquivos JSON para exportação e restauração.

A aplicação foi concebida para não enviar automaticamente os registros a servidores externos. O usuário deve, ainda assim, proteger o dispositivo, o perfil do navegador e os arquivos de backup.

O armazenamento local não elimina os deveres relativos à proteção de dados pessoais, à confidencialidade, ao sigilo e às regras institucionais. Não insira na ferramenta informações sigilosas, confidenciais ou dados pessoais desnecessários.

Consulte o [Manual de backup e dados](manual-de-backup-e-dados.md) para orientações de cópia de segurança e transferência.

## 10. Limites e responsabilidades

O Rastro Científico é uma ferramenta de documentação. Não é:

- um sistema de execução de inteligência artificial;
- um mecanismo de pesquisa bibliográfica;
- um gerenciador de referências;
- um sistema de análise estatística ou processamento de dados;
- um detector de conteúdo produzido por IA;
- uma ferramenta de detecção de plágio;
- um sistema de avaliação de integridade científica;
- um canal de denúncias ou apuração de infrações;
- um parecer jurídico;
- uma certificação de conformidade com normas do CNPq ou com a LGPD.

A plataforma não verifica automaticamente a veracidade de afirmações, citações, referências, dados ou análises. Também não confirma se os procedimentos de validação informados foram suficientes.

Os pesquisadores permanecem responsáveis pela revisão, validação e aprovação do conteúdo final, bem como pela observância das normas e orientações aplicáveis.

## 11. Princípios de concepção

O Rastro Científico é uma iniciativa de desenvolvimento tecnológico orientada pela transparência científica, pela responsabilidade no uso da Inteligência Artificial e pelo compromisso com a democratização do conhecimento.

Sua concepção parte de uma perspectiva sociotécnica. A tecnologia é compreendida como uma construção humana, histórica e social, atravessada por valores, práticas, relações e necessidades coletivas.

A plataforma procura favorecer a circulação e o compartilhamento de soluções tecnológicas, a autonomia e a ampliação do acesso ao conhecimento. Seu desenvolvimento considera que ferramentas de interesse coletivo podem ser compartilhadas, aperfeiçoadas e colocadas a serviço da sociedade.

**Idealizador:** Rodrigo NS Fernandes.

## 12. Edições do projeto

O projeto prevê duas edições:

| Edição | Objetivo | Situação |
|---|---|---|
| CNPq | Apoiar a documentação do uso de IA conforme as diretrizes aplicáveis do CNPq | Implementada na versão 0.4.2, candidata à homologação |
| Geral | Oferecer documentação ampliada para pesquisadores de diferentes instituições e contextos | Planejada; não integra a versão 0.4.2 |

As edições compartilham a proposta central do produto, mas poderão apresentar configurações, orientações e campos próprios.

## 13. Versão documentada

- **Produto:** Rastro Científico
- **Edição:** CNPq
- **Versão:** 0.4.2
- **Identificador do repositório:** `rastro_cientifico`
- **Situação:** versão candidata à homologação funcional.
- **Armazenamento:** local, no navegador.
- **Formato de backup:** JSON.

A documentação funcional não substitui a documentação técnica do código-fonte, da arquitetura de software ou do processo de desenvolvimento. Esses materiais são tratados separadamente.

## 14. Repositórios do projeto

- [GitLab](https://git.ufrj.br/rodrigonsf/rastro_cientifico)
- [GitHub](https://github.com/rodrigonsf/rastro_cientifico)

## 15. Documentos relacionados

- [README do projeto](../README.md)
- [Manual de utilização](manual-de-utilizacao.md)
- [Manual de backup e dados](manual-de-backup-e-dados.md)