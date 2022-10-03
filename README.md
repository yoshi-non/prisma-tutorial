# Prisma チュートリアル

Prismaを用いたCRUD操作

## 環境構築

```
npm init -y
```

```
npm i prisma express nodemon @prisma/client
```

Prisma初期化

```
npx prisma init
```

## マイグレーション

```
npx prisma migrate dev --name init
```

## スキーマ操作用WEBページの表示

```
npx prisma studio
```

## サーバ起動

```
npm start
```

## その他

追加推奨VSCode拡張機能:Prisma