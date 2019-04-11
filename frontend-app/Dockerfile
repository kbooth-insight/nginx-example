FROM mcr.microsoft.com/dotnet/core/sdk:2.2

COPY frontend-app /etc/frontend-app
WORKDIR /etc/frontend-app
RUN dotnet build

CMD ["dotnet", "run"]