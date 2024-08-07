# Sistemas_Operacionais

Roteiro do Laboratório Inicial com miniOS
Objetivo:
Introduzir os alunos ao miniOS, permitindo que eles compreendam a configuração básica, navegação e realização de operações fundamentais no sistema operacional. As tarefas práticas serão realizadas e os resultados devem ser salvos e enviados ao professor.

Preparativos:
Preparação do Pendrive:

Baixe a imagem do miniOS (liveCD) e crie um pendrive bootável usando uma ferramenta como Rufus ou balenaEtcher.
Certifique-se de que o pendrive está corretamente configurado para inicializar o miniOS.
Configuração do Ambiente Virtual:

Caso os alunos não tenham acesso a um computador físico, configure um ambiente virtual (VM) com o miniOS se necessário.
Passo a Passo do Laboratório:
Introdução ao miniOS:

Explique o que é o miniOS e seus principais objetivos.
Apresente a interface e os recursos básicos disponíveis no liveCD.
Inicialização do miniOS:

Peça aos alunos para inicializarem o computador a partir do pendrive.
Demonstre como verificar a inicialização correta do sistema e a interface inicial.
Exploração da Interface:

Oriente os alunos a explorar a interface gráfica ou linha de comando do miniOS.
Mostre como navegar pelos diretórios e utilizar comandos básicos.
Tarefas Práticas:

a. Criação e Manipulação de Arquivos:

Criação de Arquivo:
Comando: touch arquivo.txt
Edição de Arquivo:
Edite o arquivo com nano arquivo.txt, adicione algum texto e salve as alterações.
Exclusão de Arquivo:
Comando: rm arquivo.txt
b. Gerenciamento de Diretórios:

Criação de Diretório:
Comando: mkdir novo_diretorio
Navegação entre Diretórios:
Comando: cd novo_diretorio
Remoção de Diretório:
Comando: rmdir novo_diretorio
c. Exploração de Recursos do Sistema:

Informações do Sistema:
Comandos: uname -a, df -h, free -m
Visualização de Processos:
Comandos: ps, top
Verificação de Conexão de Rede:
Comandos: ping, ifconfig
d. Gerenciamento de Permissões:

Visualização de Permissões:
Comando: ls -l
Alteração de Permissões:
Comando: chmod 644 arquivo.txt
e. Criação e Execução de Scripts Simples:

Criação de Script:
Crie um arquivo script.sh com o comando nano script.sh e adicione um script simples (por exemplo, echo "Olá Mundo").
Execução do Script:
Torne o script executável com chmod +x script.sh e execute com ./script.sh.
f. Visualização e Edição de Logs:

Visualização de Logs:
Comandos: cat /var/log/syslog (se disponível), tail -n 10 /var/log/syslog
Registro e Envio das Informações:

Coleta de Dados:
Os alunos devem registrar todas as operações realizadas, incluindo comandos usados, resultados obtidos e quaisquer observações.
Salvamento das Informações:
Salvar os registros em um arquivo de texto ou documento (por exemplo, resultados.txt).
Envio para o Professor:
Enviar o arquivo contendo os registros por e-mail ou através de uma plataforma de envio designada pelo professor.
Encerramento da Sessão:

Oriente os alunos sobre como encerrar a sessão de forma segura e reiniciar o sistema.
Discussão e Reflexão:

Realize uma breve discussão sobre o que foi aprendido.
Responda a dúvidas e peça feedback sobre a atividade.
Materiais Necessários:
Computadores com suporte para boot via pendrive.
Pendrives com miniOS liveCD.
Ferramentas para criar pendrives bootáveis (Rufus, balenaEtcher).
Observações:
Certifique-se de que todos os alunos conseguem inicializar o sistema a partir do pendrive e acessar o ambiente miniOS.
Adapte o roteiro conforme o nível de familiaridade dos alunos com a linha de comando e sistemas operacionais.
Esse roteiro deve cobrir uma introdução completa ao miniOS e fornecer uma base sólida para atividades práticas futuras. Se precisar de mais detalhes ou ajustes, estou aqui para ajudar!
