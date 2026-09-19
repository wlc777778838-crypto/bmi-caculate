# BMI计算器网页版
纯前端静态网页，用于计算BMI身体质量指数。

## 使用方法
直接打开 index.html 输入身高体重，点击计算即可。

## Docker部署
```bash
docker build -t bmi-calc .
docker run -d -p 8081:80 --name bmi-app bmi-calc
