FROM microsoft/dotnet:1.1-sdk

WORKDIR /app
COPY ./TaxTobinAspCore/TaxTobin/TaxTobin /app

ENV ASPNETCORE_URLS http://+:80
EXPOSE 80

RUN dotnet restore

ENTRYPOINT ["dotnet", "run"]
