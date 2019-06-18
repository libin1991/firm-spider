# 🚀 Koa 爬虫

🚀🕷️👂一只坚强的蜘蛛

## 🚗 安装

```html
npm i
```

## 📖 目录介绍

```
config.js 全局配置

app.js 入口

src 下是爬虫

lib 是封装的通用类库

model 是各种模型和格式化数据处理，为 mongo 预留位置

data 下为抓取的数据，也作为向外开发 api 时读取数据入口
```

## 🕷️ 爬虫

```
抓取的所有数据写在本地 data 目录下

掘金文章： npm run start:juejin
小红书： npm run start:redBook
电影天堂： npm run start:movie
简书： npm run start:jianshu
pixabay： npm run start:pixabay
豆瓣：npm run start:douban

```

## 💻 api

```
npm run start

/juejin/front  掘金文章
/movie/:type  电影（type 在电影爬虫脚本里有配置）
/redBook/travel 小红书
/pixabay  pixabay 网站的高清图片
/douban   豆瓣评分前 500 的电影
```

## ⌛️ TODO

```
接入 mongodb 数据库
```