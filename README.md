## Todo
- [x] ~~Faça o círculo crescer no Android mais suave~~
- [x] ~~Adicionar animação ao voltar~~  
- [x]  ~~Adicionar botão voltar~~  
- [x]  ~~Corrigir circleGrow no Android~~  
- [x]  ~~API animada~~  
- [x]  ~~Navegador (react-native-router-flux)~~

## Instale no local

Abra o Terminal e digite o comando: 
> git clone https://github.com/dwicao/react-native-login-screen.git


Vá para a pasta do projeto:
> cd react-native-login-screen


Digite o seguinte comando: 
> npm install  

Você deve ter a variável de ambiente ANDROID_HOME, para verificar se você já possui, digite seu terminal:  
> echo $ANDROID_HOME  

Se estiver em branco, você poderá ler em [HERE](https://goo.gl/XSBmwE)  

Verifique se você já instalou o React Native globalmente executando este comando:  
> sudo npm install -g react-native-cli

Neste ponto, você deve poder executar o projeto.
Para executar seu projeto no seu dispositivo / emulador na configuração Debug, digite:
> npm run android-dev  

Ou se você deseja executar no simulador do iOS, execute:
> npm run ios-dev
 
Se você tiver uma mensagem de erro como `Execution failed for task ':app:dexDebug'.` execute isso no seu terminal :  
> npm run android-clean

Para criar o arquivo .apk, digite :  
> npm run android-release  

Você deve assinar .apk com keystore, para isso basta digitar seu terminal :  
> npm run android-signer

O arquivo .apk está localizado em `react-native-login-screen/android/app/build/outputs/apk/app-release-unsigned.apk`

##  Comando disponível  

| npm run ... | Description |
| --- | --- |
| adb-reverse | Reset port ADB to tcp:8081 |
| ios-dev| Run iOS project with Simulator set to "iPhone 5" |
| ios-bundle | Bundle with entry file index.ios.js |
| ios-build  | Run ios project with “Release” configuration |
| android-clean | Fix building android if preDexDebug error |
| android-build-debug | Build android .apk with “Debug” configuration |
| android-release  | Build android .apk with “Release” configuration  |
| android-signkey  | Generate keystore android  |
| android-signer | To sign app-release-unsigned.apk with random keystore |
| android-dev | Run android development-mode on simulator |
| android-bundle | Bundle with entry file index.android.js |
 

