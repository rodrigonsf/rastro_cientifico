# Manual de backup e transferência de dados

**Rastro Científico | Edição CNPq | Versão 0.4.2**

Este manual explica como proteger os registros armazenados no navegador e transferi-los para outro navegador ou computador.

## 1. Como os dados são armazenados

O Rastro Científico armazena as informações localmente no navegador, utilizando o IndexedDB.

Na prática:

- os registros ficam associados ao navegador e ao perfil utilizados;
- abrir a aplicação em outro navegador ou computador não transfere os dados automaticamente;
- limpar os dados do navegador ou remover o armazenamento do site pode apagar os registros locais;
- a aplicação não possui sincronização automática em nuvem.

Por isso, mantenha cópias de segurança fora do navegador.

## 2. Exportar um backup

1. Abra o Rastro Científico no navegador em que seus registros estão salvos.
2. Acesse **Backup e dados**.
3. Clique em **Exportar backup JSON**.
4. Aguarde o download do arquivo.
5. Guarde o arquivo em local seguro, preferencialmente com uma segunda cópia em outro dispositivo ou serviço de armazenamento confiável.

O arquivo JSON contém os dados exportados pela aplicação. Trate-o como um arquivo que pode conter informações da sua pesquisa e proteja seu acesso.

## 3. Restaurar um backup

1. Abra o Rastro Científico no navegador de destino.
2. Acesse **Backup e dados**.
3. Clique em **Restaurar backup**.
4. Selecione o arquivo JSON exportado anteriormente.
5. Aguarde a conclusão da operação.
6. Confira as pesquisas, utilizações e declarações recuperadas.

Se a aplicação apresentar uma mensagem de erro, não descarte o arquivo de backup. Preserve-o e procure apoio antes de tentar procedimentos que possam sobrescrever dados.

## 4. Transferir para outro navegador ou computador

1. No navegador de origem, exporte o backup JSON.
2. Transfira o arquivo para o computador de destino por um meio seguro.
3. Abra a mesma edição do Rastro Científico no navegador de destino.
4. Importe o arquivo JSON pela área **Backup e dados**.
5. Confira se as pesquisas, utilizações e declarações foram recuperadas.

A transferência entre navegadores depende do arquivo de backup. Não basta copiar o arquivo HTML da aplicação.

## 5. Antes de atualizar a aplicação

Antes de substituir ou abrir uma versão mais recente:

1. Abra a versão que contém seus dados.
2. Exporte um backup JSON.
3. Guarde o arquivo em local seguro.
4. Abra a nova versão no mesmo navegador e perfil, quando a intenção for continuar utilizando os dados locais existentes.
5. Confira se os registros continuam disponíveis.

Não utilize uma janela anônima para armazenar dados que deseja manter. O comportamento de armazenamento nesse modo pode ser temporário ou restrito pelo navegador.

## 6. Cuidados importantes

- Faça backup regularmente e antes de atualizações.
- Não edite manualmente o arquivo JSON, salvo se souber exatamente o que está fazendo.
- Não compartilhe backups sem avaliar se contêm informações pessoais, sensíveis, sigilosas ou confidenciais.
- Mantenha mais de uma cópia de segurança quando os registros forem importantes.
- Depois de restaurar, confira se as informações essenciais estão presentes.

## 7. Se algo der errado

Se os dados não aparecerem:

1. Confira se abriu a aplicação no navegador e perfil corretos.
2. Verifique se está utilizando a edição e o arquivo esperados.
3. Não limpe os dados do navegador.
4. Preserve o backup JSON mais recente.
5. Tente restaurar o backup em uma base de teste ou em outro perfil, evitando sobrescrever a única cópia dos dados.

O backup é a principal forma de transportar e recuperar os registros nesta versão da aplicação.