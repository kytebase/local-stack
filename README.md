# Host-н тохиргоо

/etc/hosts файлд шаардагдах hostname үүдийг docker localhost (127.0.0.1) рүү заасан байхаар тохируулж өгнө.

Дараахь командыг ажиллуулаад хэрэглэгчийн нууц үгээ оруулахад нэмэгдэх болно.

```
sudo sh -c "echo 127.0.0.1 local-stack mysql redis rabbitmq mailhog minio >> /etc/hosts"
```