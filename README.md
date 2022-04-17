# MS-OFFICE-ODT
ProPlus2021Retail.img ( Microsoft Office Professional Plus 2021 Particial, Costumized Installation)

## Steps 
### Clone files to your computer or download them as zip, and extract to folder (config.xml,setup.exe,install.cmd)
1.  Download img file from this link : [ProPlus2021Retail.img tr-TR](https://officecdn.microsoft.com/db/492350f6-3a01-4f97-b9c0-c7c6ddf67d60/media/tr-TR/ProPlus2021Retail.img)
2.  Right clik img file and mount
3.  Copy the path of the img file you mounted (On my computer it is mounted as G:)
4.  Rigt click config.xml and open with notepad (text editor)
5.  Paste the path you copied in step 3 to the source path in config.xml
6.  OfficeClientEdition="64" >> OfficeClientEdition="32" You can change it to 32 bit
7.  You can change the language for english Language ID='en-US'
8.  Exclude apps you don't want to install with ExcludeApp ID='Appname'
9.  Run install.cmd (note that all three files are in the same folder.)


# MS-OFFICE-ODT
ProPlus2021Retail.img ( Microsoft Office Professional Plus 2021 Kısmi, Özelleştirilmiş Kurulum)
## Adımlar
### Dosyaları bilgisayarınıza klonlayın veya zip olarak indirin ve klasöre çıkarın (config.xml,setup.exe,install.cmd)
1. img dosyasını bu bağlantıdan indirin: [ProPlus2021Retail.img tr-TR](https://officecdn.microsoft.com/db/492350f6-3a01-4f97-b9c0-c7c6ddf67d60/media/tr-TR/ProPlus2021Retail.img)
2. img dosyasına sağ tıklayın ve bağlayın
3. Bağladığınız img dosyasının yolunu kopyalayın (Bilgisayarımda G: olarak takılı)
4. config.xml'e sağ tıklayın ve not defteri ile açın (metin düzenleyici) 3. adımda kopyaladığınız yolu config.xml içindeki SourcePath="" yapıştırın
6. OfficeClientEdition='64' OfficeClientEdition='32' 32 bit olarak değiştirebilirsiniz
7. English Language ID='en-US' için dili değiştirebilirsiniz.
8. Yüklemek istemediğiniz uygulamaları ExcludeApp ID='Appname' ile hariç tutun
9. install.cmd'yi çalıştırın (üç dosyanın hepsinin aynı klasörde olduğunu unutmayın.)
