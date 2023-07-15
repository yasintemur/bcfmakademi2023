# bcfmakademi2023
#BCFM Akademi 2023 Case

##CASE AMACI VE İSTENİLEN
Bu case ile app.py dosyasını image haline getirip container oluşturarak web ortamında "{"msg":"BC4M"}" çıktısının alınması amaçlanıştır.

![image](https://github.com/yasintemur/bcfmakademi2023/assets/33574304/00bb5e40-ad90-4bb3-9bbf-a8576e851e40)

##DOCKERFİLE DOSYASINI OLUŞTURMA VE IMAGE OLUŞTURMA
"app.py" dosyasının bulunduğu dizine IDE yardımıyla (Örn:VS Code) Dockerfile dosyası oluşturulur ve Alpine image sistemi baz alınarak "app.py" image içerisine yerleştirilecek şekikde komutlar yazılır. En son image varsayılan dosyası olarak "app.py"ayarlanır ve image oluşturulur.

##CONTAİNER OLUŞTURMA
Oluşturduğumuz Image'den container oluşturarak "{"msg":"BC4M"}" çıktısını elde edebiliriz.

--
docker container run --name test -p 80:5000 yasintemur/uygulama
--
