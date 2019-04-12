FROM mcr.microsoft.com/dotnet/core/sdk:2.2

COPY . /etc/frontend-app
WORKDIR /etc/frontend-app
RUN dotnet build


CMD ["dotnet", "run", "--urls", "http://0.0.0.0:5000"]