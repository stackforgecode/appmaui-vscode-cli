# Criando um aplicativo NetMAUI usando Visual Studio Code - Parte 2

Nesta segunda parte do tutorial sobre como criar um aplicativo NetMAUI usando o Visual Studio Code, iremos explorar a criação de elementos de interface do usuário e formulários.

## Adicionando elementos de interface do usuário 🖌️

1. Abra o arquivo `MainPage.xaml` localizado na pasta `App`.

2. Dentro da tag `<ContentPage>`, adicione os elementos de interface do usuário que deseja exibir. Por exemplo, vamos adicionar um `Label` e um `Button`:
   ```xml
   <ContentPage xmlns="http://schemas.microsoft.com/dotnet/2021/maui"
                xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
                x:Class="MeuAppNetMAUI.App.MainPage">
       <StackLayout>
           <Label Text="Bem-vindo ao Meu App NetMAUI!" FontSize="20" HorizontalOptions="Center" VerticalOptions="CenterAndExpand" />
           <Button Text="Clique aqui" Clicked="HandleButtonClick" HorizontalOptions="Center" />
       </StackLayout>
   </ContentPage>
   ```

3. Agora, vamos adicionar a lógica para manipular o evento de clique do botão. No arquivo `MainPage.xaml.cs`, adicione o seguinte código:
   ```csharp
   void HandleButtonClick(object sender, EventArgs e)
   {
       // Lógica para manipular o evento de clique do botão
   }
   ```

## Criando formulários 📝

1. Para criar um formulário, adicione um elemento `StackLayout` dentro da página e adicione os elementos de entrada de dados desejados, como `Entry` e `Picker`:
   ```xml
   <StackLayout>
       <Label Text="Formulário de Cadastro" FontSize="20" HorizontalOptions="Center" />
       
       <Entry Placeholder="Nome" />
       <Entry Placeholder="E-mail" Keyboard="Email" />
       <Picker Title="Gênero">
           <Picker.ItemsSource>
               <x:Array Type="{x:Type x:String}">
                   <x:String>Feminino</x:String>
                   <x:String>Masculino</x:String>
                   <x:String>Outro</x:String>
               </x:Array>
           </Picker.ItemsSource>
       </Picker>
       
       <Button Text="Enviar" Clicked="HandleSubmitButton" HorizontalOptions="Center" />
   </StackLayout>
   ```

2. Adicione a lógica para manipular o evento de clique do botão "Enviar":
   ```csharp
   void HandleSubmitButton(object sender, EventArgs e)
   {
       // Lógica para processar os dados do formulário
   }
   ```

Agora você tem um formulário básico em seu aplicativo NetMAUI.

## Conclusão 📝

Nesta segunda parte do tutorial, aprendemos como adicionar elementos de interface do usuário e criar formulários em um aplicativo NetMAUI usando o Visual Studio Code. Você pode explorar diferentes elementos e personalizá-los de acordo com suas necessidades.

Na próxima parte, veremos como estilizar e personalizar a aparência do aplicativo NetMAUI.

Continue acompanhando o tutorial para aprender mais sobre o desenvolvimento de aplicativos NetMAUI usando o Visual Studio Code.

## Referências 📚

- [Documentação do .NET MAUI](https://docs.microsoft.com/pt-br/dotnet/maui/)
- [

Visual Studio Code](https://code.visualstudio.com/)
- [SDK do .NET 6](https://dotnet.microsoft.com/download/dotnet/6.0)

Divirta-se explorando a criação de elementos de interface do usuário e formulários no seu aplicativo NetMAUI! 🚀
