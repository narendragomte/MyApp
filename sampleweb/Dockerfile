[12:30 PM] Sunil Rawat (Digital,CORP)




FROM mcr.microsoft.com/dotnet/aspnet:6.0

WORKDIR /app

COPY --from=build /app ./

ENTRYPOINT ["dotnet", "sampleweb.dll"]
