# Abdool Data App

Abdool Data App is a platform that allows users to authenticate, purchase data, airtime, and manage transactions securely using Paystack for payments.

## Features

- **User Authentication**: Secure login and sign-up system.
- **Purchase Data/Airtime**: Users can buy mobile data and airtime directly within the app.
- **Paystack Integration**: Payments handled via Paystack for secure transactions.
- **Referral Program**: Users can earn rewards by referring others to use the app.

## Getting Started

To get started with the app, follow the steps below:

### Prerequisites

Before you can run the app, ensure you have the following:

- A Paystack account for API keys.
- An internet connection to interact with Paystack API.

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/abdool-data-app.git
    ```

2. **Set up Paystack keys:**
   - Replace the **public** and **secret** keys in the script section with your **Paystack** keys.

   ```javascript
   key: 'pk_live_fefa4cab21e99bd551e0979a445038b389d9cfea',  // Live Public Key
   secret: 'sk_live_d376cf9690cd746cd9ffd6ab6b38cd1a03ccd642', // Live Secret Key
