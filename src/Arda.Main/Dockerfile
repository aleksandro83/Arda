FROM microsoft/aspnetcore:1.1.0-preview1
ENTRYPOINT ["dotnet", "Arda.Main.dll"]
ARG source=.
WORKDIR /app
EXPOSE 80 443
COPY $source .
