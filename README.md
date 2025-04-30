

## 本地部署

测试：

```bash
git clone https://github.com/void2eye/msqh.git

cd msqh

npm install

npm run dev
```

编译

```bash
npm run build
npm run start
```

推荐使用pm2进行托管

```bash
npm install -g pm2

pm2 start npm -- start
```

----

## docker部署

```bash
docker build -t msqh-app .

docker run -p 3000:3000 msqh-app
```

------



