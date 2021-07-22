FROM mcr.microsoft.com/dotnet/aspnet:3.1
COPY bin/Release/net5.0/publish/ App/
WORKDIR /App
EXPOSE 8080
ENTRYPOINT ["dotnet", "InAndOut.dll"]