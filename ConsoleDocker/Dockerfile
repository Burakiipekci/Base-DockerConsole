FROM mcr.microsoft.com/dotnet/runtime:5.0  #from komuduyla image nerden alýcamýzý söylüyoruz
WORKDIR /App   #Bu komutla aldýðýmýz ýmage içinde dosya oluþturuyoruz.
COPY  bin/Release/net5.0/publish app/   # Verdiðimiz yola gidip o dosyadakileri kopyalýyým app dosyasýna aktarýyoruz
ENTRYPOINT ["dotnet","ConsoleDocker.dll"]
#Bir imageden bir container ayaða kalktýðý zaman çalýþacak olan kodu belirliyoruz.
#( Containerlar imagelerin çalýþan instancelarýdýr)
