FROM microsoft/aspnetcore:1.1
WORKDIR /app
COPY bin/Debug/PublishOutput/mywebapp ./
ENTRYPOINT ["dotnet", "mywebapp.dll"]