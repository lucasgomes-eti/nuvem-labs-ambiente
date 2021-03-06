# Configuração do Ambiente

* baixar e instalar android studio (https://developer.android.com/studio)
* baixar e instalar Xcode (Apple Store )
* instalar o gerenciador de pacotes brew (https://brew.sh/index_pt-br)
* instalar o nodejs (brew install node)
* instalar o cli do react native (npm install @react-native-community/cli -g)
* instalar o cli do react (npm install create-react-app -g)
* instalar o docker (brew install docker)
* instalar o cli da heroku (brew tap heroku/brew && brew install heroku)
* instalar mysql workbench (https://dev.mysql.com/downloads/workbench ou brew install cask mysqlworkbench)
* criar conta no Github (https://github.com)
* criar conta na Figma (https://www.figma.com)
* criar conta na Heroku (https://heroku.com)

Docker Scripts

* docker run -e MYSQL_ALLOW_EMPTY_PASSWORD=true --name mariaDB-localhost -d -p 3306:3306 mariadb:10.3
* docker run -d --hostname my-rabbit --name rabbitMQ-localhost -p 15672:15672 -p 5672:5672 -p 25676:25676 rabbitmq:management

Caso tenha algum problema com o Xcode ao tentar executar o aplicativo em react native no iOS tente usar o seguinte comando: `sudo xcode-select --switch /Applications/Xcode.app` em seguida dentro da pasta ios execute o `pod install` novamente. Esse erro parece acontecer porque em um dos updates o Xcode CLI Tools foi setado em um caminho incorreto. Fonte: https://stackoverflow.com/a/58934023