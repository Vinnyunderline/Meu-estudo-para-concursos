# Informática para a banca examinadora IDIB

INFORMÁTICA
APOSTILA ESTRATÉGICA PARA CONCURSOS
BANCA IDIB

Teoria direcionada • exemplos de cobrança • 30 questões inéditas • gabarito comentado

Material elaborado a partir do conteúdo programático informado. As questões são autorais e inspiradas no formato objetivo de concursos; não são transcrições de provas oficiais.
Como utilizar esta apostila
- Estude a explicação de cada capítulo e marque os conceitos que confundiu.
- Faça as questões sem consultar o texto e leia os comentários mesmo quando acertar.
- Revise fórmulas, protocolos, atalhos, permissões, conceitos da LGPD e diferenças entre termos parecidos.
- As prioridades são orientativas. Todo assunto expressamente previsto no edital pode ser cobrado.
Mapa de prioridades
Prioridade	Conteúdos
Muito alta	Excel/Calc; Word/Writer; Windows; hardware/software; internet e redes; e-mail
Alta	Segurança da informação; LGPD; armazenamento; operações com arquivos
Complementar, mas previsto no edital	PowerPoint/Impress; nuvem e colaboração; banco de dados; governo digital; gestão documental; formatos e integração


1. Fundamentos de informática: hardware, software e arquivos
Hardware
É a parte física do computador. CPU executa instruções; memória RAM mantém temporariamente dados e programas em uso; HD e SSD guardam dados de forma não volátil; placa-mãe interliga componentes; fonte fornece energia; GPU processa gráficos. A RAM é volátil: seu conteúdo é perdido quando falta energia. HD e SSD mantêm os arquivos mesmo com o equipamento desligado.
Software
É a parte lógica: programas, sistemas e instruções. Software de sistema administra o equipamento (Windows, Linux); software aplicativo realiza tarefas do usuário (Word, Excel, navegador). Software livre diz respeito às liberdades de usar, estudar, modificar e redistribuir conforme a licença. Código aberto permite acesso ao código-fonte segundo os termos da licença. Gratuito não é sinônimo de livre.
Arquivos e extensões
A extensão ajuda a identificar o formato e o aplicativo associado: DOCX (Word), XLSX (Excel), PPTX (PowerPoint), ODT/ODS/ODP (OpenDocument), PDF (documento portátil), TXT (texto simples), JPG/PNG (imagem), ZIP (compactação), EXE (executável Windows). A extensão, sozinha, não garante que o arquivo seja seguro nem prova seu conteúdo.
Armazenamento
Local é feito no próprio dispositivo ou mídia conectada; remoto fica em outro equipamento/servidor acessado pela rede; nuvem usa infraestrutura de servidores acessível pela internet. Sincronizar mantém cópias alinhadas; compartilhar concede acesso; copiar cria outra cópia; mover altera a localização. Backup é uma cópia de segurança planejada para recuperação, não apenas sincronização.
2. Windows 11 e Linux Ubuntu
Sistema operacional
É o software básico que gerencia processador, memória, arquivos, dispositivos, usuários e execução de programas. Windows e distribuições Linux são sistemas operacionais. Ubuntu é uma distribuição baseada em Linux, não um programa de escritório.
Windows 11
Conheça Área de Trabalho, Menu Iniciar, barra de tarefas, Configurações, Explorador de Arquivos, Lixeira, contas de usuário e Gerenciador de Tarefas. Arquivo guarda dados; pasta organiza arquivos; atalho aponta para um item; excluir para a Lixeira normalmente permite restaurar, enquanto exclusão definitiva pode impedir a recuperação simples.
Operações com arquivos
Copiar cria uma segunda ocorrência e mantém o original; mover transfere o item; recortar seguido de colar normalmente move; renomear altera o nome, não o conteúdo; compactar reúne arquivos e pode reduzir o espaço ocupado. A extensão pode ficar oculta nas configurações do Explorador, por isso é importante reconhecer o tipo do arquivo.
Atalhos do Windows
Win+E abre o Explorador; Win+D mostra a Área de Trabalho; Win+L bloqueia a sessão; Win+I abre Configurações; Alt+Tab alterna janelas; Win+R abre Executar; Ctrl+Shift+Esc abre o Gerenciador de Tarefas. Ctrl+C copia, Ctrl+X recorta, Ctrl+V cola e Ctrl+Z desfaz.
Ubuntu e terminal
No Linux, diretórios organizam arquivos. Comandos básicos: pwd mostra o diretório atual; ls lista itens; cd muda de diretório; mkdir cria diretório; cp copia; mv move ou renomeia; rm remove; cat exibe conteúdo; sudo executa comando com privilégios administrativos. Root é a conta administrativa; sudo permite executar comandos autorizados com privilégios elevados.
Permissões Linux
As permissões básicas são leitura (r), escrita (w) e execução (x), aplicadas a proprietário, grupo e outros. Não confunda permissão de leitura com permissão de alteração. O princípio é conceder somente o acesso necessário.
3. Microsoft Excel e LibreOffice Calc
Estrutura
Pasta de trabalho é o arquivo; planilha é uma folha dentro do arquivo; coluna é identificada por letras; linha por números; célula é o encontro entre linha e coluna; intervalo é um conjunto de células. B5 significa coluna B, linha 5. A1:A10 representa um intervalo vertical.
Fórmulas e operadores
Fórmulas começam com =. Operadores: + adição, - subtração, * multiplicação, / divisão, ^ potência e % porcentagem. Parênteses controlam a ordem de cálculo. Exemplo: =(A1+B1)*2.
Referências
Relativa A1 muda ao copiar a fórmula; absoluta $A$1 mantém linha e coluna; mista $A1 fixa a coluna e A$1 fixa a linha. Exemplo: ao copiar =A1*$B$1 para a linha seguinte, A1 pode virar A2, mas $B$1 permanece fixo.
Funções essenciais
SOMA adiciona valores; MÉDIA calcula média aritmética; MÁXIMO e MÍNIMO retornam extremos; CONT.NÚM conta células numéricas; CONT.VALORES conta células não vazias; CONT.SE conta células que atendem a critério; SOMASE soma valores associados a um critério; SE testa uma condição e retorna um resultado se verdadeira e outro se falsa. Exemplos: =SOMA(A1:A5), =MÉDIA(B1:B5), =CONT.SE(C1:C20;"Ativo"), =SE(A1>=7;"Aprovado";"Reprovado"). O separador de argumentos pode variar conforme configuração regional.
Organização e análise
Classificar ordena registros; filtro exibe apenas linhas que atendem a critérios, sem necessariamente apagar as demais; remover duplicadas elimina registros repetidos; formatação condicional muda a aparência conforme regras; congelar painéis mantém linhas/colunas visíveis durante a rolagem; gráficos representam dados visualmente.
Formatação
Formatos comuns: Geral, Número, Moeda, Contábil, Data, Hora, Porcentagem e Texto. Alterar a aparência não significa necessariamente alterar o valor armazenado. Exibir 10% e exibir 0,1 podem representar o mesmo valor subjacente.
Calc
O LibreOffice Calc tem estrutura e funções semelhantes ao Excel. O formato nativo mais associado é ODS. A lógica de células, fórmulas, referências, filtros e gráficos é equivalente, embora nomes de menus, atalhos e compatibilidade possam variar.
4. Microsoft Word e LibreOffice Writer
Edição e formatação
Word e Writer criam e editam documentos. Formatar fonte altera tipo, tamanho, cor e efeitos; formatar parágrafo altera alinhamento, recuos, espaçamento e listas. Negrito destaca, itálico inclina e sublinhado coloca linha abaixo do texto.
Alinhamento
À esquerda alinha pela margem esquerda; centralizado posiciona o texto no centro; à direita alinha pela margem direita; justificado ajusta o texto às duas margens, distribuindo os espaços entre palavras.
Página
Margens definem distâncias das bordas; orientação pode ser retrato ou paisagem; tamanho define papel (por exemplo, A4); cabeçalho e rodapé ficam nas áreas superior e inferior; quebra de página inicia conteúdo em nova página sem depender de linhas vazias.
Revisão e produtividade
Localizar procura termos; substituir troca ocorrências; verificação ortográfica aponta possíveis erros; comentários registram observações; controle de alterações acompanha edições; mala direta gera documentos personalizados em lote; estilos organizam títulos e permitem criar sumário automático.
Atalhos e formatos
Atalhos comuns incluem Ctrl+C, Ctrl+V, Ctrl+X, Ctrl+Z e Ctrl+P. Em versões e idiomas diferentes, atalhos de formatação podem variar; confira o comando indicado no menu do aplicativo. DOCX é formato associado ao Word; ODT é formato aberto do Writer.
5. PowerPoint e LibreOffice Impress
Elementos
Uma apresentação é composta por slides. Layout organiza os espaços reservados; tema define conjunto visual de cores, fontes e efeitos; transição é o efeito na passagem de um slide para outro; animação é aplicada a objetos dentro do slide.
Exibição e conteúdo
O modo de apresentação exibe os slides ao público. É possível inserir texto, imagens, tabelas, gráficos, áudio e vídeo. F5 geralmente inicia a apresentação do começo; Shift+F5 inicia do slide atual; Esc encerra a apresentação.
Impress
O LibreOffice Impress tem finalidade equivalente ao PowerPoint e utiliza, por padrão, o formato ODP. Ao abrir arquivos de outro pacote, alguns efeitos, fontes ou layouts podem sofrer alterações.
6. Internet, intranet, navegadores e redes
Internet e redes
Internet é uma rede mundial de redes; intranet é uma rede privada de uma organização; extranet permite acesso controlado a usuários externos. LAN é rede local; WAN cobre grandes distâncias; WLAN é uma LAN sem fio; MAN cobre uma área metropolitana.
Equipamentos
Roteador encaminha pacotes entre redes; switch conecta dispositivos em uma rede local; modem adapta a comunicação à tecnologia do provedor; ponto de acesso oferece conectividade sem fio; firewall filtra tráfego segundo regras de segurança.
Protocolos
IP endereça e encaminha pacotes; TCP oferece transporte confiável e orientado à conexão; UDP é mais simples e não estabelece conexão; DNS traduz nomes de domínio em endereços IP; DHCP distribui configurações de rede; HTTP transfere recursos web; HTTPS protege a comunicação web com TLS; FTP transfere arquivos.
Endereçamento
IPv4 utiliza 32 bits e costuma ser escrito em quatro números decimais separados por pontos. IPv6 utiliza 128 bits e é representado em grupos hexadecimais separados por dois-pontos. DNS permite acessar serviços por nomes em vez de decorar endereços IP.
Navegadores
Chrome, Edge e Firefox permitem abrir páginas, usar guias, favoritos, histórico, downloads, extensões e navegação privativa. Histórico registra páginas visitadas; cache guarda cópias temporárias para acelerar carregamento; cookies armazenam informações de sessão e preferências; favoritos guardam endereços.
HTTPS e certificados
HTTPS utiliza TLS para proteger a comunicação e o certificado ajuda a autenticar a identidade do servidor. O cadeado indica conexão protegida, mas não garante que o conteúdo ou a empresa sejam honestos: sites fraudulentos também podem usar HTTPS.
Pesquisa e fontes
Aspas pesquisam expressão exata; site: restringe a domínio; filetype: restringe tipo de arquivo; sinal de menos exclui termo; OR indica alternativas. Exemplo: site:gov.br edital filetype:pdf. Avalie autoria, data, domínio, evidências, contexto e confirmação por fontes independentes. Imagens podem estar fora de contexto ou manipuladas.
7. Correio eletrônico
Webmail e cliente
Webmail é acessado pelo navegador, como Gmail. Cliente de e-mail é um programa, como Outlook ou Thunderbird. Ambos permitem enviar, receber e organizar mensagens.
Campos
Para indica destinatário principal; Cc envia cópia visível; Cco envia cópia oculta, sem revelar aos demais os endereços incluídos nesse campo; Assunto resume o tema; anexo acompanha a mensagem como arquivo.
Protocolos
SMTP é usado para envio. POP3 recebe mensagens e frequentemente baixa cópias para o dispositivo, conforme configuração. IMAP mantém a caixa no servidor e sincroniza pastas e estado das mensagens entre dispositivos.
Organização
Caixa de entrada recebe mensagens; enviados guarda mensagens remetidas; rascunhos guarda mensagens não concluídas; spam reúne mensagens suspeitas ou não solicitadas; lixeira recebe itens excluídos; filtros e regras automatizam organização.
Segurança
Phishing tenta induzir a vítima a revelar dados ou executar ações; spoofing falsifica identidade/origem; spam é mensagem não solicitada; malware é software malicioso. Verifique endereço real, domínio, links e anexos. Não forneça senhas por links recebidos inesperadamente.
8. Nuvem e colaboração
Modelos
IaaS oferece infraestrutura (máquinas virtuais, rede e armazenamento); PaaS oferece plataforma para desenvolver/executar aplicações; SaaS oferece software pronto pela internet. OneDrive e Google Drive são exemplos de armazenamento e colaboração; Microsoft 365 e Google Workspace reúnem aplicativos de produtividade.
Compartilhamento
Leitor pode visualizar; comentador pode comentar; editor pode alterar. O acesso pode ser restrito a pessoas, grupos ou liberado por link. Link público ou permissões excessivas aumentam o risco de exposição.
Coautoria e versões
Coautoria permite que mais de uma pessoa trabalhe no mesmo documento. Histórico de versões permite consultar ou restaurar versões anteriores. Revogar acesso impede que uma pessoa continue acessando por aquela permissão; transferência de propriedade muda quem administra ou detém o arquivo, conforme o serviço.
Continuidade
Sincronização não substitui backup: exclusões ou alterações indevidas podem se propagar. Documentos institucionais devem ter proprietário institucional, permissões adequadas, retenção e cópias de segurança conforme regras do órgão.
9. Segurança da informação e LGPD
Tríade CIA
Confidencialidade: acesso somente por pessoas autorizadas. Integridade: proteção contra alteração ou destruição indevida. Disponibilidade: acesso aos dados e serviços quando necessários.
Autenticação, autorização e auditoria
Autenticação verifica quem é o usuário; autorização define o que ele pode fazer; accounting/auditoria registra atividades e consumo. Exemplo: login autentica; permissão para consultar processo autoriza; log registra quem consultou e quando.
Menor privilégio e segregação
Menor privilégio concede apenas os acessos necessários à função. Segregação de funções distribui etapas críticas entre pessoas diferentes para reduzir fraude, erro e abuso.
Trilhas e continuidade
Logs registram eventos, usuários, horários e operações, apoiando rastreabilidade e investigação. Backup, redundância, plano de continuidade e recuperação de desastres ajudam a manter ou restaurar serviços.
LGPD: conceitos
A Lei 13.709/2018 disciplina o tratamento de dados pessoais. Dado pessoal é informação relacionada a pessoa natural identificada ou identificável. Dado sensível inclui, entre outros, origem racial ou étnica, convicção religiosa, opinião política, saúde, vida sexual, dado genético ou biométrico vinculado à pessoa.
Agentes e titular
Titular é a pessoa a quem os dados se referem. Controlador toma decisões sobre o tratamento; operador trata dados em nome do controlador; encarregado atua como canal de comunicação. A ANPD é a Autoridade Nacional de Proteção de Dados.
Princípios
Memorize: finalidade, adequação, necessidade, livre acesso, qualidade dos dados, transparência, segurança, prevenção, não discriminação e responsabilização/prestação de contas. Consentimento é uma das bases legais, mas não a única. O poder público também está sujeito à LGPD, observadas as regras próprias.
10. Dados, informação e bancos de dados
Dado, informação e conhecimento
Dado é registro bruto; informação é dado contextualizado e organizado; conhecimento é interpretação que apoia decisões. Exemplo: 85 (dado); 85 atendimentos em maio (informação); aumento da demanda exige reforço da equipe (conhecimento).
Sistema de informação
Seus componentes incluem hardware, software, dados, pessoas, processos e redes/comunicação. A tecnologia isolada não constitui todo o sistema: pessoas e procedimentos também são essenciais.
Banco de dados
É uma coleção organizada de dados. Tabela organiza registros em linhas e campos em colunas; chave primária identifica unicamente cada registro; chave estrangeira referencia chave de outra tabela e estabelece relacionamento; SGBD é o software que gerencia o banco.
Qualidade
Dados de qualidade devem ser precisos, completos, consistentes, válidos e atuais. Dados duplicados, desatualizados ou contraditórios prejudicam decisões e serviços.
11. Governo digital e Administração Pública
Serviços digitais
Governo digital utiliza tecnologia para facilitar o acesso a serviços, reduzir etapas, melhorar eficiência e ampliar transparência. Exemplos: protocolo eletrônico, agendamento, emissão de documentos e consulta de processos.
Identificação e autenticação
Identificação é declarar quem é o usuário; autenticação verifica essa identidade; autorização define quais serviços ou dados ele pode acessar. O gov.br é uma plataforma de identificação e autenticação para serviços públicos digitais.
Integração de dados
O compartilhamento entre órgãos pode evitar que o cidadão apresente repetidamente informações já disponíveis ao Estado. Deve ocorrer com finalidade, segurança, controle de acesso e respeito à legislação.
Transparência e dados abertos
Transparência ativa é a divulgação espontânea pelo órgão; passiva é o fornecimento após solicitação. Dados abertos devem permitir acesso, uso e reutilização, respeitadas restrições legais, como proteção de dados pessoais.
Acessibilidade
Serviços digitais devem ser utilizáveis por pessoas com deficiência e diferentes necessidades: navegação por teclado, contraste adequado, textos alternativos, estrutura clara e compatibilidade com tecnologias assistivas.
Documentos digitais
Nato-digital nasce em formato digital; digitalizado resulta da conversão de documento físico. Gestão documental inclui captura, classificação, indexação, armazenamento, acesso, preservação, temporalidade e destinação. Autenticidade e integridade devem ser preservadas ao longo do ciclo de vida.
12. Formatos abertos, proprietários e integração
Formatos
DOCX, XLSX e PPTX são formatos associados ao Microsoft Office; ODT, ODS e ODP pertencem à família OpenDocument. PDF é formato portátil para preservar apresentação. Formato aberto possui especificação disponível e condições de implementação; formato proprietário é controlado por titular/licença. Aberto não significa necessariamente gratuito.
Compatibilidade
Office e LibreOffice conseguem abrir e salvar diversos formatos, mas podem ocorrer diferenças em fontes, fórmulas, macros, layout, comentários e efeitos. Para preservar o conteúdo, prefira o formato exigido pelo destinatário e confira o arquivo após converter.
13. Questões inéditas – estilo IDIB
Assinale uma única alternativa em cada questão.

Questão 1. A memória RAM é caracterizada por:
- A) Armazenar dados permanentemente, mesmo sem energia.
- B) Ser volátil e manter temporariamente dados em uso.
- C) Substituir o processador na execução de instruções.
- D) Armazenar exclusivamente arquivos de vídeo.
  Questão 2. Assinale a alternativa que apresenta um formato padrão do LibreOffice Calc.
- A) XLSX
- B) PPTX
- C) ODS
- D) EXE
  Questão 3. No Windows, a operação que cria uma segunda cópia e mantém o arquivo original é:
- A) Mover
- B) Copiar
- C) Renomear
- D) Excluir
  Questão 4. No Ubuntu, o comando utilizado para exibir o diretório atual é:
- A) ls
- B) pwd
- C) mkdir
- D) rm
  Questão 5. Em uma planilha, a referência $C$4 é:
- A) Relativa
- B) Mista
- C) Absoluta
- D) Inválida
  Questão 6. Qual função conta células que atendem a um critério?
- A) SOMA
- B) CONT.SE
- C) MÁXIMO
- D) MÉDIA
  Questão 7. A fórmula =SE(A1>=7;"Aprovado";"Reprovado"):
- A) Soma A1 com 7.
- B) Conta células maiores que 7.
- C) Retorna Aprovado quando A1 é maior ou igual a 7.
- D) Formata A1 como porcentagem.
  Questão 8. Em uma planilha, aplicar filtro significa:
- A) Apagar definitivamente as linhas que não atendem ao critério.
- B) Exibir somente os registros que atendem ao critério.
- C) Converter números em texto.
- D) Proteger todas as células.
  Questão 9. No editor de texto, alinhamento justificado:
- A) Centraliza cada linha.
- B) Alinha o texto às margens esquerda e direita.
- C) Alinha somente à direita.
- D) Transforma o texto em tabela.
  Questão 10. No Word, o recurso que registra as modificações feitas no documento para revisão é:
- A) Mala direta
- B) Controle de alterações
- C) Quebra de página
- D) Zoom
  Questão 11. Em apresentações, a diferença correta é:
- A) Transição atua entre slides; animação atua em objetos do slide.
- B) Animação atua entre arquivos; transição altera fontes.
- C) São recursos idênticos.
- D) Transição só pode ser aplicada a imagens.
  Questão 12. Uma intranet é:
- A) A própria internet mundial.
- B) Uma rede privada de uma organização.
- C) Uma rede exclusivamente via satélite.
- D) Um aplicativo de edição de texto.
  Questão 13. O protocolo que traduz nomes de domínio em endereços IP é:
- A) SMTP
- B) DNS
- C) FTP
- D) POP3
  Questão 14. O protocolo HTTPS utiliza mecanismos de segurança para:
- A) Garantir que todo site seja confiável.
- B) Proteger a comunicação entre cliente e servidor.
- C) Impedir qualquer tipo de fraude na internet.
- D) Substituir o DNS.
  Questão 15. No navegador, o cache é utilizado principalmente para:
- A) Armazenar temporariamente recursos e acelerar carregamentos.
- B) Enviar cópia oculta de mensagens.
- C) Substituir o histórico.
- D) Bloquear todos os cookies.
  Questão 16. No e-mail, o campo Cco permite:
- A) Enviar mensagem sem assunto.
- B) Ocultar dos demais destinatários os endereços incluídos nesse campo.
- C) Bloquear anexos.
- D) Criptografar automaticamente a mensagem.
  Questão 17. O protocolo mais diretamente associado ao envio de e-mails é:
- A) IMAP
- B) POP3
- C) SMTP
- D) DNS
  Questão 18. A principal característica do IMAP é:
- A) Apenas enviar mensagens.
- B) Manter mensagens no servidor e sincronizar o acesso entre dispositivos.
- C) Converter anexos em PDF.
- D) Bloquear spam automaticamente.
  Questão 19. Phishing é uma prática que busca:
- A) Melhorar a velocidade da rede.
- B) Induzir o usuário a fornecer dados ou executar ação maliciosa.
- C) Compactar arquivos.
- D) Atualizar o sistema operacional.
  Questão 20. No compartilhamento em nuvem, conceder permissão de editor significa permitir que a pessoa:
- A) Somente visualize.
- B) Visualize e, em regra, altere o conteúdo.
- C) Acesse sem autenticação em qualquer circunstância.
- D) Se torne automaticamente proprietária.
  Questão 21. Qual alternativa diferencia corretamente backup e sincronização?
- A) São sinônimos.
- B) Backup é cópia para recuperação; sincronização mantém versões alinhadas entre locais.
- C) Sincronização sempre protege contra exclusão acidental.
- D) Backup exige obrigatoriamente internet.
  Questão 22. Na tríade de segurança, integridade significa:
- A) Acesso apenas por pessoas autorizadas.
- B) Dados disponíveis quando necessários.
- C) Proteção contra alteração ou destruição indevida.
- D) Criação automática de senhas.
  Questão 23. A autenticação tem por finalidade:
- A) Definir as permissões do usuário.
- B) Verificar a identidade alegada pelo usuário.
- C) Registrar o histórico de impressão.
- D) Realizar cópia de segurança.
  Questão 24. O princípio do menor privilégio determina que:
- A) Todos os usuários tenham acesso administrativo.
- B) Cada usuário receba somente os acessos necessários à sua função.
- C) As senhas sejam compartilhadas pela equipe.
- D) O acesso aos dados seja sempre público.
  Questão 25. Segundo a LGPD, dado pessoal sensível inclui:
- A) Número aleatório sem possibilidade de associação.
- B) Dado sobre saúde vinculado a pessoa natural.
- C) Qualquer informação pública sobre órgão.
- D) Nome de empresa, necessariamente.
  Questão 26. Na LGPD, o agente que toma decisões referentes ao tratamento de dados pessoais é o:
- A) Titular
- B) Controlador
- C) Operador
- D) Destinatário
  Questão 27. A diferença entre dado e informação é que:
- A) Dado é sempre sigiloso.
- B) Informação é dado contextualizado e organizado.
- C) Informação não pode apoiar decisões.
- D) Dado e conhecimento são sinônimos.
  Questão 28. Em banco de dados relacional, a chave primária:
- A) Identifica unicamente cada registro da tabela.
- B) É sempre uma senha.
- C) Permite registros duplicados sem restrição.
- D) Substitui todas as tabelas.
  Questão 29. Transparência ativa ocorre quando:
- A) O órgão divulga informações independentemente de pedido.
- B) O cidadão protocola pedido e aguarda resposta.
- C) O órgão elimina dados públicos.
- D) A informação é fornecida apenas por telefone.
  Questão 30. Um documento nato-digital é aquele que:
- A) Foi impresso e depois escaneado.
- B) Foi criado originalmente em formato digital.
- C) É necessariamente um PDF assinado.
- D) Não pode ser preservado eletronicamente.
14. Gabarito comentado
1. B — A RAM é memória volátil, utilizada durante a execução de programas. HD e SSD são meios não voláteis.
2. C — ODS é o formato OpenDocument de planilhas. XLSX é associado ao Excel; PPTX a apresentações; EXE a executáveis do Windows.
3. B — Copiar cria outra ocorrência; mover transfere o item; renomear altera o nome.
4. B — pwd mostra o caminho do diretório atual. ls lista itens; mkdir cria diretório; rm remove.
5. C — O cifrão antes da coluna e da linha fixa ambas ao copiar a fórmula.
6. B — CONT.SE conta ocorrências que satisfazem uma condição. SOMASE, por sua vez, soma valores que atendem a um critério.
7. C — A função SE avalia uma condição e retorna um resultado para verdadeiro e outro para falso.
8. B — O filtro restringe a exibição. Não equivale a excluir os registros ocultados.
9. B — O justificado ajusta o texto às duas margens, distribuindo espaços entre palavras.
10. B — O controle de alterações registra edições para que possam ser analisadas, aceitas ou rejeitadas.
11. A — Transições ocorrem na passagem de um slide a outro; animações são aplicadas aos elementos do slide.
12. B — Intranet é uma rede privada interna. Extranet oferece acesso controlado a usuários externos.
13. B — DNS realiza a resolução de nomes. SMTP envia e-mails; FTP transfere arquivos; POP3 recebe mensagens.
14. B — HTTPS protege a comunicação com TLS. Não garante que o site seja honesto ou legítimo.
15. A — Cache armazena temporariamente recursos. Histórico registra páginas visitadas; cookies guardam informações de sessão/preferências.
16. B — Cco é cópia oculta. Não é, por si só, um mecanismo de criptografia.
17. C — SMTP é usado para envio; POP3 e IMAP são protocolos de recebimento/acesso.
18. B — IMAP sincroniza pastas e estado das mensagens com o servidor, facilitando acesso em vários dispositivos.
19. B — Phishing usa engano, frequentemente por mensagens ou páginas falsas, para obter credenciais ou induzir ações.
20. B — Editor pode modificar o conteúdo. Isso não transfere automaticamente a propriedade.
21. B — Uma exclusão pode ser sincronizada para outros dispositivos; por isso, sincronização não substitui backup independente.
22. C — Confidencialidade restringe acesso; integridade protege exatidão e completude; disponibilidade assegura acesso quando necessário.
23. B — Autenticação verifica identidade; autorização define permissões; auditoria registra atividades.
24. B — O menor privilégio reduz riscos ao limitar permissões ao estritamente necessário.
25. B — Dados referentes à saúde são dados pessoais sensíveis, nos termos da LGPD.
26. B — Controlador decide sobre o tratamento; operador trata dados em nome do controlador.
27. B — Dado é registro bruto; informação é dado contextualizado; conhecimento envolve interpretação e aplicação.
28. A — A chave primária identifica unicamente um registro. Uma chave estrangeira referencia chave de outra tabela.
29. A — Transparência ativa é divulgação espontânea; passiva decorre de solicitação do interessado.
30. B — Nato-digital nasce digital. Digitalizado é a conversão de documento originalmente físico.
15. Revisão de véspera: o que memorizar
Hardware	RAM é volátil; HD/SSD são não voláteis; CPU executa instruções.
Arquivos	DOCX/XLSX/PPTX; ODT/ODS/ODP; PDF; TXT; ZIP; EXE.
Windows	Win+E Explorador; Win+L bloquear; Win+I Configurações; Alt+Tab alternar.
Linux	pwd atual; ls lista; cd muda; mkdir cria; cp copia; mv move/renomeia; rm remove; sudo eleva privilégios.
Excel	A1 relativa; $A$1 absoluta; $A1/A$1 mistas; CONT.SE conta; SOMASE soma por critério; SE testa condição.
Word	Justificado alinha às duas margens; controle de alterações registra edições; mala direta personaliza documentos.
Apresentações	Transição entre slides; animação em objetos.
Redes	DNS resolve nomes; DHCP distribui configuração; TCP confiável; UDP sem conexão; IP endereça; HTTPS protege comunicação.
E-mail	SMTP envia; POP3 recebe/baixa; IMAP sincroniza; Cco oculta destinatários.
Nuvem	Leitor visualiza; comentador comenta; editor altera; sincronização não substitui backup.
Segurança	Confidencialidade, integridade e disponibilidade; autenticação, autorização e auditoria são conceitos diferentes.
LGPD	Dado pessoal; dado sensível; titular; controlador; operador; encarregado; princípios e bases legais.
Administração pública	Transparência ativa divulga sem pedido; passiva responde solicitação; nato-digital nasce digital.