# Anotações Sobre Java
Anotações sobre os aprendizados dos estudos de Java

## Links Úteis
[Bootcamp Everis / Dio New Talents Java](https://web.digitalinnovation.one/track/everis-new-talents-java?tab=path)

Os passos abaixo com as instalações do Java, Ecipse e Git foram copiados de:
https://github.com/cami-la/curso-dio-dominando-ides-java/blob/master/README.md

Dominando IDEs Java
Sejam bem-vindos ao curso DOMINANDO IDEs JAVA oferecido gratuitamente pela plataforma de cursos online Digital Innovation One. 🧡💛
🚦 Guia
🔹 Começaremos passando rapidamente sobre o Java e algumas das suas características mais importantes
🔹 Em seguida, entraremos nas instalações do Java e das IDEs nos diferentes sistemas operacionais: Windows e Linux
🔹 E seguiremos até o final do curso explicando de uma forma leve e objetiva sobre umas das IDEs mais conhecidas para desenvolvimento Java: Eclipse IDE e IntelliJ IDEA IDE
⚠️ Lembrando que o foco do curso são as IDEs e não a linguaguem Java. Ok? ⚠️

🛑 Pré-requistos
 Sistema operacional (Windows e/ou Linux)

 Conta no GitHub

📚 Ementa
▪️ Instalação/Configuração do Java
✅ Um pouco da história do Java
✅ Diferença entre JRE e JDK
✅ Versões do Java
✅ Se não existisse IDE?

▪️ Ubuntu
✅ Instalação OpenJDK
✅ Configuração de variável de ambiente
✅ Instalação do Eclipse
✅ Configurando o ícone no Dock
✅ Instalação do IntelliJ

▪️ Windows
✅ Instalação OpenJDK
✅ Configuração de variável de ambiente
✅ Instalação do Eclipse
✅ Instalação do IntelliJ

▪️ IntelliJ 
✅ Diferenças entre versões
✅ Conhecendo um pouco por dentro da IDE
✅ Criando seu primeiro projeto Java no IntelliJ
✅ Atalhos e Produtividade
✅ Conectar seu projeto no GitHub

▪️ Eclipse 
✅ Diferenças entre versões
✅ Conhecendo um pouco por dentro da IDE
✅ Criando seu primeiro projeto Java no IntelliJ
✅ Atalhos e Produtividade
✅ Conectar seu projeto no GitHub

 ▪️ Outras Alternativas 
✅ Visual Studio Code



🪟 WINDOWS
🔺 Instalação JDK Zulu
Aqui no windows, vamos fazer o download do OpenJDK Zulu. As compilações do Azul Zulu do OpenJDK são compilações de código aberto, testadas pelo TCK e certificadas do OpenJDK. O Zulu Blue está disponível para uma ampla variedade de plataformas de hardware e sistemas operacionais. A documentação do Azul Zulu inclui notas de lançamento, um guia de instalação e licenças de terceiros.

🔹 1. Entre no SITE AZUL

🔹 2. Faça o download do arquivo .zip do JDK 11.0.11+9. No meu caso, o x86 64-bit

🔹 3. Vá no drive C://Arquivo de Programas

🔹 4. Caso não tenha um diretório com o nome Java, crie

🔹 5. Entre neste diretório e descompacte o download do zip JDK Zulu 11.0.11+9 neste diretório

🔹 6. Vamos configurar o ambiente JAVA_HOME:

​ 6.1 Menu iniciar -> Editar as varáveis de ambiente do sistema

​ 6.2 Irá abrir a janela Propriedades do Sistema, escolha a aba Avançado, em seguida clique em variáveis de Ambiente

​ 6.3 Na janela Variáveis de Ambiente, crie um novo Variáveis do sistema

​ 6.4 Abrirá uma jabela: Nova Variável de Sistema.

​ 6.5 Nome da variável: JAVA_HOME

​ 6.6 Valor da variável: em seguida OK.​ O valor da variável é o caminho do diretório que você descompactou o zip JDK Zulu 11.0.11+9 no passo 5

​ 6.7 Na mesma janela Variáveis do Sistema, localize a variável Path, selecione e clique a opção Editar...

​ 6.8 Clique na opção Novo e cole o mesmo caminho do passo 5 acrescentando \bin

​ 6.9 Continue com o path selecionado e clique na opção Mover para Cima até chegar no topo

🔹 7. Pronto, finalizada a configuração. Próximo passo é conferir se está instalado tudo certinho

🔹 8. Abra o Prompt de Comando: Menu iniciar -> cmd

🔹 9. Vamos conferir mais uma vez se o Java está instalado na nossa máquina

java -version
Créditos: DevSuperior


🔺 Instalação Eclipse
🔹 1. Acessar o site oficial do ECLIPSE

🔹 2. Fazer o download do instalador

🔹 3. Escolha segunda a opção: Eclipse IDE for Enterprise Java and Web Developers

🔹 4. Clique no folder da primeira opção (Java 11 + VM) e selecione o JDK que instalamos na nossa máquina

🔹 5. Mantenha as opções "create start menu entry" e "create desktop shortcut"

🔹 6. Install

🔹 7. Accept now

🔹 8. Launch

🔹 9. Pronto, intalação concluída


🔺 Instalação Git
🔹 1. Entre no site ofical do GIT

🔹 2. Escolha a opção Windows e o instalador será baixado automáticamente

🔹 3. Mantenha as opções pré selecionadas e siga com Next

🔹 4. Install

🔹 5. Antes de finaizar a instalação, selecione a opção Lauch Git Bash

🔹6. Ao finalizar o passo 5, irá abrir o Git Bash

🔹7. Agora vamos fazer as configurações iniciais:

🔹8. Confirme se o git realmente está instalado:

git --version
🔹9. Vamos começar as configurações iniciais:

​ 9.1 Configurar o nome de usuário

git config --global user.name "Seu nome"
​ 9.2 Configurar o endereço de e-mail:​ É de suma importância que o ENDEREÇO DE E-MAIL SEJA O MESMO DO GITHUB afim de evitar conflitos!

git config --global user.email seuemail@email.br
​ 9.3 Vamos conferir a lista de configurações:

git config --list
🔹10. Pronto, git instalado e configurado com sucesso!
