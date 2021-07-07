# *O Que é Shell Script?*

- *Shell em computação é um interface de usu para acessar os serviços de um sistema operacional;* 
- *Script é uma linguagem de programação que executa no sistema em tempo de execução, muito utilizado para automação.

# *(cd) - Mudar diretório*

- *cd é um acrônimo da expressão inglesa change directory.*
- *cd / Abre o diretório raiz do sistema.*
- *cd ~ Abre o diretório do usuário corrente. o usuário logado naquele instante.*
- *cd .. Voltar o diretório.*

# *(ls, ls -l, ls -a, ls -s) Listando arquivos*

- *ls Lista o conteúdo*
- *ls -l Lista o conteúdo em coluna detalhada.*
- *ls -a Lista o conteúdo até os arquivos ocultos.*
- *ls -s Lista o conteúdo com tamanho alocado de cada arquivo, em bloco.*

# *Criar e Atualizar o Conteúdo (touch)*

- *(Touch) Usado para criar arquivos vazios ou alterar data e hora do arquivo*
- *Criar Múltiplos Arquivos* **touch file_name1.txt file_name2.txt file_name3.txt
- *Alterar Hora de acesso* **touch -a file_name.txt**
- *Alterar Hora da Modificão* **touch -m file_name1.txt
- *Alterar Hora de Acesso sem Criar um Novo Arquivo* **touch -c file_name.txt**
- *Definir Hora Específica de Acesso e Modificação Usando Touch* **touch -t 202012081047.30 file.txt**
- # *CCYYMMDDhhmm.ss*
- *CC -* **Os dois primeiros dígitos do ano.**
- *YY -* **Os dois dígitos subsequentes do ano.**
- *MM -* **O mês**
- *DD -* **O dia**
- *mm -* **O minuto**
- *ss -* **O segundo**

# *Visualizar Conteúdo do Arquivo (cat)*

- **(cat) concatenate (concatenar)**
- *Criar arquivos*
- *Unir arquivos*
- *Exibir arquivos*
- *Colocar o resultado em um outro arquivo **cat arq1 > arq_final** redirecionador de saída >*
- *Para parar a rolagem da tela e permitir a navegação use o pipe "|"*
- **More** *ou* **less**

# *Mover arquivos (mv)* 

- *mv -* Move arquivos e diretório e renomeia arquivos e diretórios.

# *Copiar arquivos (cp)*

- *cp -* **Permite copíar arquivos ou diretóris para outro local.**
- *Sem confirmação de existência ou não, exceto se usar a flag **-i** (interativo)*
- *Nenhuma saída será exibida, exceto se usar o flag opção **-v** (verbose)*

# *Criando Diretórios mkdir*

- **mkdir -** *Criar diretório*

# *Remover Arquivos (rm)*

- **rm -** *Remove arquivos*
- **-f -** *Remove os arquivos sem perguntar.*


