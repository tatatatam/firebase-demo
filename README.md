# firebase-demo

## Project setup
```
yarn install
```

### Run development
```
yarn run serve
```

### Build file
```
yarn run build
```
หลังจาก Build จะได้ไฟล์ ใน folder dist

## Firebase deploy

### Initialize Firebase 
สร้าง Project ที่ Firebase Console <a href="https://console.firebase.google.com"   target="_blank" rel="noopener noreferrer"> Firebase Console</a>

```
yarn global add firebase-tools
firebase init
```
เลือก default กรณีเราต้องการ deploy web ขึ้น firebase
```
Select hosting
What do you want to use as your public directory? dist
```
### Deployment
```
yarn run build
firebase deploy
```