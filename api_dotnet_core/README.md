# Example - Project API .Net Core

## Create a new project 

1.	Launch Visual Code and open a Terminal

	Ouvrez le Visual Code et allez dans l'option "Terminal"

	Abra o Visual Code e vá na opção "Terminal"
![Terminal](./images/terminal.png)

2. 	Go to folder of your project

	Allez sur le dossier de votre projet

	Abra a pasta do seu projeto

![Folder](./images/folderproject.png)

3. 	Run the command

	Éxecutez la command ci-dessous

	Execute o comando 

```
dotnet new webapi -o "nameofproject"
```

* nameofproject 

	Enter the name of your project 

	Informez le nom de votre projet 

	Indique o nome do seu projeto

![Project](./images/createproject.png)

4. 	Open your project with Visual Code
	
	Ouvrez votre projet avec Visual Code
	
	Abra o projeto com o Visual Code

![OpenProject](./images/openproject.png)

![Project Visual Code](./images/vscode.png)

5. 	Run your project for the first time
	
	Éxecutez votre projet pour la première fois
	
```
dotnet run
```

![Run Project](./images/dotnetrunproject.png)

6. 	Open Postman application or other platform for API Development
	Ouvrez l'application Postman ou une autre application pour tester votre API.
	Abrir o Postman ou uma outra aplicação para testar a API.
	
```
https://localhost:5001/WeatherForecast
```

> Postman Download: https://www.postman.com/