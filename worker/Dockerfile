FROM mcr.microsoft.com/dotnet/sdk:7.0

WORKDIR /app

COPY *.csproj ./
RUN dotnet restore

COPY . .

RUN dotnet build

CMD ["dotnet", "run"]