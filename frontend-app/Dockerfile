FROM mcr.microsoft.com/dotnet/core/sdk:2.2

COPY frontend-app /etc/frontend-app
WORKDIR /etc/frontend-app
RUN dotnet build
EXPOSE 5000 5001
CMD ["dotnet", "run"]