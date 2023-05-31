# Criando um aplicativo NetMAUI usando Visual Studio Code - Parte 3

Na terceira parte deste tutorial sobre como criar um aplicativo NetMAUI usando o Visual Studio Code, iremos abordar a geração de executáveis para os sistemas operacionais Windows, Linux e MacOS, além da geração de APKs para dispositivos móveis iOS e Android.

## Gerando executáveis para Windows, Linux e MacOS 💻🐧🍎

1. Abra um terminal no diretório raiz do seu projeto.

2. Para gerar o executável para Windows, execute o seguinte comando:
   ```
   dotnet publish -r win-x64 --self-contained true /p:PublishSingleFile=true
   ```

3. Para gerar o executável para Linux, execute o seguinte comando:
   ```
   dotnet publish -r linux-x64 --self-contained true /p:PublishSingleFile=true
   ```

4. Para gerar o executável para MacOS, execute o seguinte comando:
   ```
   dotnet publish -r osx-x64 --self-contained true /p:PublishSingleFile=true
   ```

Os executáveis serão gerados na pasta `bin/Debug/net6.0/[sistema operacional]/[arquitetura]/publish`.

## Gerando APKs para Mobile iOS e Android 📱

1. Abra um terminal no diretório raiz do seu projeto.

2. Para gerar o APK para Android, execute o seguinte comando:
   ```
   dotnet build -t:PackageForAndroid
   ```

   O APK será gerado na pasta `bin/Debug/net6.0/android/bin/Debug`.

3. Para gerar o pacote para iOS, você precisará de um ambiente de desenvolvimento configurado no macOS e um dispositivo iOS conectado. Execute o seguinte comando:
   ```
   dotnet build -t:PackageForIOS
   ```

   O pacote será gerado na pasta `bin/Debug/net6.0/ios/bin/Debug`.

## Conclusão 📝

Nesta terceira parte do tutorial, aprendemos como gerar executáveis para os sistemas operacionais Windows, Linux e MacOS, além de gerar APKs para dispositivos móveis iOS e Android usando o Visual Studio Code e o .NET MAUI.

Agora você está pronto para distribuir e testar seu aplicativo NetMAUI em diferentes plataformas.

Na próxima parte, veremos como implantar e publicar seu aplicativo NetMAUI.

Continue acompanhando o tutorial para aprender mais sobre o desenvolvimento de aplicativos NetMAUI usando o Visual Studio Code.

## Referências 📚

- [Documentação do .NET MAUI](https://docs.microsoft.com/pt-br/dotnet/maui/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [SDK do .NET 6](https://dotnet.microsoft.com/download/dotnet/6.0)

Divirta-se gerando executáveis e APKs para seu aplicativo NetMAUI! 🚀 
