# vs_code
Document on setting up vs_code server

```
cp code-server.service /lib/systemd/system/code-server.service
sudo systemctl start code-server
```

![image](https://user-images.githubusercontent.com/755710/89652424-71d81480-d893-11ea-9656-e92b2ffe3063.png)


## Enable on reboot
```
sudo systemctl enable code-server
```