# Criando um aplicativo NetMAUI usando Visual Studio Code

Neste artigo, vamos explorar como criar um aplicativo NetMAUI (Multi-platform App UI) usando o Visual Studio Code. O NetMAUI é uma tecnologia de interface de usuário multiplataforma que permite desenvolver aplicativos para iOS, Android e Windows usando uma única base de código.

Vamos seguir as etapas abaixo para configurar o ambiente de desenvolvimento e criar o aplicativo NetMAUI.

## Pré-requisitos 📋

- [Visual Studio Code](https://code.visualstudio.com/) instalado em sua máquina.
- [SDK do .NET 6](https://dotnet.microsoft.com/download/dotnet/6.0) instalado em sua máquina.
- Extensões do VS Code:
  - [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
  - [Maui](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.maui)

## Configurando o ambiente de desenvolvimento 🛠️

1. Instale as extensões do VS Code mencionadas acima. Você pode instalá-las a partir da guia "Extensions" (Extensões) no VS Code. Pesquise pelos nomes das extensões e clique em "Install" (Instalar) para cada uma delas.

2. Verifique se o SDK do .NET 6 está instalado corretamente em sua máquina executando o seguinte comando no terminal:
   ```
   dotnet --version
   ```
   Certifique-se de que a versão exibida seja 6.0 ou superior.

3. Crie uma nova pasta para o seu projeto NetMAUI e navegue até ela usando o terminal do VS Code:
   ```
   mkdir MeuAppNetMAUI
   cd MeuAppNetMAUI
   ```

4. Crie um novo projeto NetMAUI executando o seguinte comando no terminal:
   ```
   dotnet new maui
   ```

5. Abra a pasta do projeto no VS Code:
   ```
   code .
   ```

## Desenvolvendo o aplicativo NetMAUI 🚀

A estrutura do projeto NetMAUI é semelhante à do projeto Xamarin.Forms. Você encontrará os arquivos de código-fonte, como MainPage.xaml e MainPage.xaml.cs, na pasta `App`.

Para desenvolver o aplicativo NetMAUI, você pode usar os mesmos conceitos e técnicas que está familiarizado ao trabalhar com Xamarin.Forms.

## Executando o aplicativo 🏃‍♀️

Para executar o aplicativo NetMAUI no VS Code, siga as etapas abaixo:

1. Abra o terminal no VS Code.

2. Execute o seguinte comando para iniciar o aplicativo no emulador ou dispositivo:
   ```
   dotnet maui run
   ```

Isso iniciará o aplicativo NetMAUI e abrirá o emulador ou dispositivo selecionado para testar o aplicativo.

## Conclusão 📝

Neste artigo, exploramos como criar um aplicativo NetMAUI usando o Visual Studio Code. Aprendemos a configurar o ambiente de desenvolvimento, criar um projeto NetMAUI e executar o aplicativo em um emulador ou dispositivo. Agora, você pode começar a desenvolver seus próprios aplicativos NetMAUI usando o VS Code.

Espero que este artigo tenha sido útil e que você tenha adquirido uma compreensão básica do desenvolvimento

 de aplicativos NetMAUI. Continue explorando a documentação oficial e os recursos adicionais para aprofundar seus conhecimentos.

## Referências 📚

- [Documentação do .NET MAUI](https://docs.microsoft.com/pt-br/dotnet/maui/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [SDK do .NET 6](https://dotnet.microsoft.com/download/dotnet/6.0)

Divirta-se criando aplicativos incríveis com o NetMAUI e o Visual Studio Code! 🎉
