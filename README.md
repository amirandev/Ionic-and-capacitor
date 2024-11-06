# Ionic-and-Capacitor - პროექტის გამართვა

ამ ინსტრუქციით შეგიძლიათ დაიწყოთ Ionic და Capacitor პროექტი და მოამზადოთ Android აპკისთვის.

## პროექტის შექმნა

პროექტის საწყისი კონფიგურაციისთვის გამოიყენეთ შემდეგი ბრძანება:

```bash
ionic start
```

1. **open wizard**: არ ჩართოთ (no)
2. **choose stack**: აირჩიეთ Angular, React ან Vue

შემდეგ, გახსენით პროექტი VS Code-ში:

```bash
code ./myapp
```


## კონფიგურაცია

### აპლიკაციის სახელი და ID
1. დააყენეთ აპლიკაციის სახელი და ID ფაილში `capacitor.config.json`.

2. კონფიგურაციის ცვლილებების შემდეგ, სინქრონიზაციისთვის გაუშვით:

   ```
   npx cap sync
   ```



## პლატფორმის დამატება

1. Android პლატფორმის დასამატებლად, გაუშვით შემდეგი ბრძანებები:

   ```bash
   npm install @capacitor/android
   npx cap add android
   ```

---

## პროექტის აგება (Build)

1. პროექტის ასაშენებლად:

   ```
   ionic build
   npx cap sync
   ```

2. გახსენით Android Studio:

   ```bash
   npx cap open android
   ```

   შემდეგ აირჩიეთ **Android** და დააჭირეთ Enter.

3. **Android Studio-ში**:
   - შედით `File > Build > Build App Bundles / APKs` მენიუში.

**და ეს ყველაფერი!** პროექტი დაიბილდება APK ფაილად. 
```

---

This README provides clear instructions in Georgian for setting up and building an Ionic project, including creating, configuring, and building the project for Android deployment.
