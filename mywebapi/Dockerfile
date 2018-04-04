FROM microsoft/aspnetcore:1.1
WORKDIR /app
COPY bin/Debug/PublishOutput/mywebapi ./
ENV ASPNETCORE_URLS http://+:9000
EXPOSE 9000
ENTRYPOINT ["dotnet", "mywebapi.dll"]