## Pull image
docker run -it microsoft/dotnet:latest


## Initialize some code
mkdir hello_world
cd hello_world
dotnet new

## Run the application
dotnet restore
dotnet run
