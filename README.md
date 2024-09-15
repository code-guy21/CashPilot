# CashFlow

CashFlow is a mobile app that automates personal finance management by splitting users' paychecks into key categories such as debts, bills, savings, and investments. The app securely links to users' bank accounts via the Plaid API, tracks transactions in real-time, and allocates funds according to preset financial goals. CashFlow helps users manage cash flow, track bills, automate debt payments, and provides a clear financial overview through detailed reports and visualizations.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [License](#license)
- [Contact](#contact)

## Features

- **Paycheck Allocation**: Automatically divides income into debts, bills, savings, and investments based on user-defined goals.
- **Bill & Debt Management**: Tracks bills and debts, offering reminders and automated payments.
- **Financial Reports**: Provides interactive charts and real-time reports on budgets, savings, and debt progress.
- **Real-Time Notifications**: Alerts users on upcoming bills, payments, and financial milestones.
- **Secure Authentication**: Protects sensitive financial data with OAuth 2.0 and two-factor authentication (2FA).

## Tech Stack

### Front-End

- **React Native**: For building a cross-platform mobile application on iOS and Android.
- **TypeScript**: For type safety and better developer experience.
- **Redux Toolkit**: For managing complex state such as user accounts, transaction history, and financial reports.
- **React Navigation**: For managing navigation and routing within the app.
- **D3.js** or **Recharts**: For creating interactive and insightful financial charts and visualizations.

### Back-End

- **Node.js** with **TypeScript**: For server-side scripting and type safety.
- **NestJS**: For structured and modular application architecture.
- **GraphQL** with **Apollo Server**: For flexible and efficient data querying and real-time updates.
- **PostgreSQL** with **TypeORM**: For relational data handling and complex queries.
- **Plaid API**: For secure bank account linking and real-time transaction monitoring.

### API Integration

- **Plaid API**: For securely connecting to users' bank accounts and tracking transactions.
- **Stripe** or **PayPal**: For handling direct payment processing or subscriptions if needed.

### Notifications

- **Firebase Cloud Messaging (FCM)**: For real-time push notifications on upcoming bills and payment reminders.

### CI/CD and Deployment

- **GitHub Actions**: For automated testing, building, and deployment.
- **Docker**: For consistent environment setup and deployment.
- **AWS**:
  - **Elastic Beanstalk**: For backend deployment and auto-scaling.
  - **RDS (Relational Database Service)**: For managing the PostgreSQL database.
  - **S3**: For secure storage of user-generated content if needed.

### Security

- **AWS KMS** or **Vault**: For managing sensitive data and encryption keys.
- **Helmet.js** and **Rate Limiting**: For securing the API endpoints against common attacks.

### Testing

- **Jest**: For unit and integration testing of both backend and frontend.
- **React Native Testing Library**: For testing mobile UI components.
- **Cypress**: For end-to-end testing of user workflows.

## Usage

1. **Link Bank Account**: Securely link your bank account via Plaid to start tracking your transactions.
2. **Set Financial Goals**: Define how you want your income to be allocated across debts, bills, savings, and investments.
3. **Manage Bills**: Track your bills and debts, set reminders, and automate payments.
4. **Monitor Finances**: Use interactive dashboards to view your financial health and track progress towards your goals.
5. **Receive Notifications**: Get real-time alerts on upcoming bills, payments, and financial milestones.

## License

CashFlow is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

Alexis San Javier - [ucfknight2017@gmail.com](mailto:ucfknight2017@gmail.com)

- **Website**: [alexissj.net](https://www.alexissj.net)
- **LinkedIn**: [linkedin.com/in/alexissj](https://linkedin.com/in/alexissj)
