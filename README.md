# Delivery App

## Clone Repository
To clone this repository and its submodules, use the following command:

```bash
git clone --recursive https://github.com/ThuongDoo/delivery-app.git
```

## Setting up Delivery App

### 1. delivery-app-API
#### Create .env file
Navigate to the `delivery-app-API` directory and create a `.env` file with the following content:

```env
MONGO_URL={your_mongodb_database_link}
JWT_SECRET={your_secret_key_for_data_encryption}
JWT_LIFETIME=30d
```

#### Install Dependencies and Start
Open a terminal and run the following commands:

```bash
cd delivery-app-API
npm install
npm start
```

### 2. delivery-admin-v2
#### Install Dependencies and Start
Open a terminal and run the following commands:

```bash
cd delivery-admin-v2
npm install
npm start
```

### 3. delivery-client
#### Install Dependencies and Start
Open a terminal and run the following commands:

```bash
cd delivery-client
yarn install
yarn start
```

#### Run on Expo Go
After starting the client application, type 'a' in the terminal if you have an Android emulator, or open the Expo Go app on your mobile device and scan the QR code.

## License
This project is licensed under the [MIT License](LICENSE).
```

Lưu ý rằng bạn cần thay thế `{your_mongodb_database_link}` và `{your_secret_key_for_data_encryption}` bằng thông tin tương ứng của bạn.
