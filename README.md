# diggems-legal

DigGems (找到萌宠 / Find Cute Pets) App Store / Play legal + marketing pages — hosted on Cloudflare Pages at `https://diggems.lx06.com`.

Modeled after [pick10-legal](https://github.com/lixiao90s/pick10-legal).

## Pages

| File | URL | App Store 用途 |
|------|-----|----------------|
| index.html | / | 游戏官网首页 |
| support.html | /support | **Support URL** |
| privacy.html | /privacy | **Privacy Policy URL** |
| terms.html | /terms.html | 用户协议 |
| legal.html | /legal.html | 法律文档索引 |
| app-ads.txt | /app-ads.txt | AdMob 验证 |

## App Store Connect 填写

| 字段 | URL |
|------|-----|
| Privacy Policy URL | https://diggems.lx06.com/privacy |
| Support URL | https://diggems.lx06.com/support |

## Deploy — GitHub + Cloudflare Pages

1. Push this repo to GitHub (`lixiao90s/diggems-legal`)
2. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git
3. Select `diggems-legal`
4. Build settings: Framework preset **None**, Build command empty, Output directory `/`
5. Custom domains → `diggems.lx06.com`

## Local preview

```bash
cd diggems-legal
python -m http.server 8080
# open http://localhost:8080
```
