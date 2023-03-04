# Installation

docker, docker-compose сервисүүд нээлттэй ажиллаж байх шаардлагатай. 

```
cd ~/
git clone https://github.com/myagmarsurensedjav/local-stack.git

cd local-stack
./init
```

Дээрх жишээнд `~/` хавтасны оронд хүссэн directory сонгон суулгах боломжтой юм. `./init` ийн тусламжтай `alias` командууд, hosts тохиргоо, docker network зэрэг автоматаар тохирох юм.

 Terminal аа хаагаад нээсний дараа alias командууд идэвхжих болно.

# Aliases

Дараах alias бүхий командуудыг ашиглах боломжтой.
- `mysql` - Mysql container-т команд ажиллуулах
- `mysqlroot` - Mysql cli аар root хэрэглэгчээр нэвтрэн орох
- `local-cd` - local-stack суусан directory луу орох
- `local-up` - local-stack сервисүүдийг docker-compose-т асаах
- `local-stop` - docker-compose сервисүүдийг унтраах
- `local-links` - Холбоос болон хоост, порт-н мэдээлэл харах
- `local-pma` - PHPMyadmin browser-т нээх
- `local-mail` - Mailhog browser-т нээх
