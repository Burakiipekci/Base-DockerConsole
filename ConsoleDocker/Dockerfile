FROM mcr.microsoft.com/dotnet/runtime:5.0  #from komuduyla image nerden al?cam?z? s?yl?yoruz
WORKDIR /App   #Bu komutla ald???m?z ?mage i?inde dosya olu?turuyoruz.
COPY  bin/Release/net5.0/publish app/   # Verdi?imiz yola gidip o dosyadakileri kopyal?y?m app dosyas?na aktar?yoruz
ENTRYPOINT ["dotnet","ConsoleDocker.dll"]
#Bir imageden bir container aya?a kalkt??? zaman ?al??acak olan kodu belirliyoruz.
#( Containerlar imagelerin ?al??an instancelar?d?r)
