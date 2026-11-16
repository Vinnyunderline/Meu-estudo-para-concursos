# Informática para a banca examinadora IDIB

[📥 Baixar Apostila de Informática - IDIB (PDF)](Apostila_Informatica_IDIB.pdf)


# Revisão de Informática – Banca IDIB
**Fonte:** [Aula no YouTube - Prof. Alan Souza](http://www.youtube.com/watch?v=f4Cb_67mArc)

---

## 1. Segurança da Informação e Extensões de Arquivos [00:10:00]

### Identificação de Arquivos [00:13:07]
Um arquivo é identificado por três elementos:
* **Ícone:** Elemento gráfico que indica o programa padrão associado.
* **Nome:** Definido livremente pelo usuário.
* **Extensão:** Sufixo após o ponto (ex.: `.docx`, `.exe`) que indica o **tipo provável** do arquivo e auxilia o sistema operacional a escolher o programa adequado para abri-lo [00:50:49].

> **Atenção:** A extensão **não garante segurança nem autenticidade**, pois pode ser alterada manualmente para disfarçar programas maliciosos (*malwares*) [00:50:13].

### Principais Extensões Cobradas [00:15:58]
* **Imagens:**
  * `.jpg` / `.jpeg`: Padrão de fotografias; não aceita fundo transparente [00:16:17].
  * `.png`: Aceita fundo transparente [00:18:42].
  * `.gif`: Formato de imagem (não é vídeo) que aceita transparência e animações [00:19:20].
  * `.bmp` (Bitmap) e `.svg` [00:19:48].
* **Documentos e Áudio:** `.docx` (Word), `.mp3` (áudio) [00:15:18].
* **Executáveis:** `.exe` — representa um **programa executável** [00:20:16].

### Conduta Segura com Dispositivos Removíveis [00:22:03]
Ao receber um pen drive ou anexo suspeito (por exemplo, um arquivo supostamente de imagem com extensão `.exe`):
1. **Nunca execute** o arquivo diretamente.
2. Submeta o dispositivo e o arquivo à verificação de um **antivírus atualizado**.
3. Siga os procedimentos institucionais de segurança.

---

## 2. Gerenciamento de Arquivos e Pastas [00:24:11]
Para evitar perdas, duplicidades e dificuldade na localização de documentos em ambientes corporativos ou públicos [00:27:44]:
* Organize os arquivos em **pastas hierárquicas** (ex.: por ano, tipo de ocorrência e data).
* Aplique **nomenclatura padronizada** e precisa.
* Realize **cópias de segurança (*backups*)** regularmente.
* **Evite:** acumular arquivos na Área de Trabalho [00:26:12] ou alterar extensões manualmente (o que pode inutilizar o arquivo) [00:28:42].

---

## 3. Editores de Texto (Microsoft Word / LibreOffice Writer) [00:29:45]
* **Cabeçalho:** Texto inserido no **topo** da página que se repete automaticamente em todas as páginas [00:31:41].
* **Rodapé:** Texto inserido na **base** (parte inferior) das páginas [00:31:47].
* **Margens:** Espaço em branco entre a borda da folha e a área de digitação (configurado na guia *Layout*) [00:33:48].
* **Numeração de Páginas:** Inserida de forma automática junto aos recursos de cabeçalho/rodapé [00:32:52].

---

## 4. Navegação na Internet: URL vs. Link [00:36:42]
* **URL (*Uniform Resource Locator*):** É o **endereço** completo de um recurso na rede (ex.: `https://www.google.com`) [00:38:30]. Segue uma estrutura padronizada: `protocolo` + `serviço` + `domínio` [00:40:38].
* **Link (ou Hiperlink):** É um **elemento clicável** (texto, botão ou imagem) dentro de uma página que serve como ponte, direcionando o usuário para outro conteúdo ou página [00:42:56].

---

## 5. Protocolos de E-mail (Correio Eletrônico) [00:59:22]
Para o funcionamento do correio eletrônico, utilizam-se servidores intermediários e três protocolos principais:

| Protocolo | Função Principal | Características |
| :--- | :--- | :--- |
| **SMTP** | **Envio** de e-mails [01:05:43] | Transfere a mensagem do remetente ao servidor e entre servidores (*"Sua Mensagem Tá Partindo"*). |
| **POP / POP3** | **Recebimento** (Download) [01:06:52] | **Puxa** os e-mails da caixa de entrada para o dispositivo local e, por padrão, **apaga** do servidor. Não permite sincronismo [01:10:31]. |
| **IMAP** | **Recebimento** (Sincronizado) [01:08:47] | **Mantém** os e-mails no servidor, permitindo acesso simultâneo em múltiplos dispositivos e visualização de todas as pastas [01:10:51]. |

---

## 6. Arquitetura TCP/IP e Camadas de Rede [01:12:48]
O modelo TCP/IP divide a comunicação em rede em camadas (etapas) padronizadas [01:18:35]:

1. **Camada de Aplicação:** Onde atuam os protocolos ligados aos programas do usuário — `HTTP`, `HTTPS`, `SMTP`, `POP`, `IMAP`, `FTP` (transferência de arquivos), `DNS` (nomes de domínio), `DHCP`, `SNMP` [01:20:06].
2. **Camada de Transporte:** Prepara os dados para envio — `TCP`, `UDP`, `SCTP` [01:21:11].
3. **Camada de Rede (ou Internet):** Endereçamento lógico e roteamento entre redes — `IP`, `ICMP`, `RIP` [01:22:29].
4. **Camada de Acesso à Rede (Enlace + Física):** Transmissão física via cabo (`Ethernet`) ou sem fio (`Wi-Fi`) [01:21:48].

---

## 7. Internet, Intranet e Extranet [01:25:05]
Todas utilizam a **mesma infraestrutura e a mesma pilha de protocolos (TCP/IP)** [01:25:45]. A diferença está no **público e na restrição de acesso** [01:32:38]:

| Rede | Tipo de Acesso | Quem Acessa |
| :--- | :--- | :--- |
| **Internet** | **Público** e global [01:27:09] | Qualquer pessoa no mundo. |
| **Intranet** | **Privado** e **interno** [01:28:18] | Funcionários/colaboradores dentro da organização. Utiliza controles rigorosos de segurança (como *Firewall* e *IPS*). |
| **Extranet** | **Privado** e **externo** [01:30:10] | Funcionários fora da empresa (*home office*), clientes, parceiros e fornecedores mediante autenticação (login/senha) e ferramentas como **VPN** (criptografia e tunelamento) [01:42:20]. |

---

## 8. Sistema Operacional Linux (Ubuntu / Debian) [01:35:35]
* **Software Livre / *Open Source*:** Código-fonte aberto (licença **GPL**), permitindo estudo, modificação e distribuição [01:35:44].
* **Usuário Comum vs. Administrador:** Usuários comuns têm permissões limitadas. O administrador é chamado de **superusuário** ou **`root`** [01:44:59].

### Comandos Essenciais de Terminal [01:39:32]
* `ls`: Lista arquivos e pastas do diretório atual [01:39:56].
* `cd [pasta]`: Entra em um diretório específico [01:40:17].
* `mkdir [nome]`: Cria uma nova pasta [01:40:36].
* `sudo apt install [pacote]`: Instala um pacote/programa no Ubuntu/Debian [01:46:20]:
  * `sudo`: Executa o comando com privilégios de administrador (`root`) [01:44:06].
  * `apt` (*Advanced Package Tool*): Gerenciador/instalador de pacotes [01:45:55].
  * `install`: Ação de instalação [01:43:20].

---

## 9. Planilhas Eletrônicas (Excel / LibreOffice Calc) [01:46:48]

### Função `PROCV` (Procura Vertical) [01:50:07]
Busca um valor na **primeira coluna à esquerda** de uma tabela (identificando a **linha**) e retorna um dado correspondente na mesma linha a partir de uma **coluna específica** [02:03:19].

**Sintaxe:**
```excel
=PROCV(valor_procurado; matriz_tabela; num_indice_coluna; [procurar_intervalo])

