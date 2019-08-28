# dotnet core
- dotnet new console  #创建dotnetcore console项目
- dotnet new mvc #创建.net core mvc项目
- dotnet run #运行
- dotnet publish -c release  #发版，生成到release文件

- Properties\launchSettings.json   配置端口文件


# centos 安装.net core
- rpm -Uvh https://packages.microsoft.com/config/rhel/7/packages-microsoft-prod.rpm
- yum update
- yum install libunwind libicu
- yum install dotnet-sdk-2.1.202