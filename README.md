# Online Charging System iOS Application

This project is an iOS application for an Online Charging System (OCS) integrated with APIs provided by AOM. The application displays user information dynamically and allows users to monitor their services in real-time.

## Features

- **User Login**: Users can log in by entering their phone number and security key.
- **User Details**: After logging in, users can view their name, package details (internet, SMS, call duration), and validity dates on a screen.
- **Remaining Usage Information**: Displays users' internet, SMS, and call duration information in visual card format.
- **Forgot Password**: Users can reset their password using their phone number and security key.

## Technologies

- SwiftUI: For user interface design
- Combine: For data management and API calls
- URLSession: For making API requests

## Usage

- **Log In**: Use the `SignInView` screen to log in with your phone number and password.
- **View User Details**: After logging in, view user information and remaining usage details on the `UserDetails` screen.
- **Reset Password**: Use the `ForgotPassword` screen to reset your password with your phone number and security key.

## Screenshots

**Sign In Screen:**

<img width="326" alt="Ekran Resmi 2024-08-16 15 51 07" src="https://github.com/user-attachments/assets/6dfb0fd5-7468-4a8b-821f-840fed744e9a">


**Sıgn Up Screen:**

<img width="330" alt="Ekran Resmi 2024-08-16 15 51 21" src="https://github.com/user-attachments/assets/d94d5995-05a7-46a2-bf05-012133193431">


**User Details Screen:**

<img width="327" alt="Ekran Resmi 2024-08-16 15 50 57" src="https://github.com/user-attachments/assets/5cf583f4-a4fe-4c0f-beed-76cb9696b34f">


**Forgot Password Screen:**

<img width="327" alt="Ekran Resmi 2024-08-16 15 51 42" src="https://github.com/user-attachments/assets/07c10910-ff7f-4c8d-9a1e-e5d155decdc4">


## API Integration

- **Login API**: `http://34.172.128.173/api/auth/login/{msisdn}/{password}`
- **Customer Information API**: `http://34.172.128.173/api/customer/getCustomerByMsisdn/{msisdn}`
- **Package Details API**: `http://34.172.128.173/api/package/getPackageDetailsByMsisdn/{msisdn}`
- **Remaining Usage API**: `http://34.172.128.173/api/balance/getRemainingCustomerBalanceByMsisdn/{msisdn}`

## Contributing

If you would like to contribute, please open a pull request or create an issue describing the problem.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

- **Developer**: [Engincan Gündüz](https://github.com/engincangunduz)
- **Email**: enqinn.78@gmail.com
