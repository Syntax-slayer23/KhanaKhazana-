<img width="1500" height="966" alt="image" src="https://github.com/user-attachments/assets/68cc9a9f-c9e9-4d6e-91d3-d093850f4686" />

# KhanaKhazana  
 KhanaKhazana is a **food ordering and delivery web application** that streamlines the meal ordering
 process for users and restaurants. It allows customers to explore restaurant menus, add dishes to a cart,
 and place orders with secure payments via **Cash on Delivery (COD), UPI, or card payments through
 Stripe integration**. On the vendor side, the platform provides an Admin Panel for restaurants to manage
 their menu items, handle incoming orders in real time, and update order statuses. The application is built
 with a Node.js and Express backend, uses MongoDB for data persistence, and integrates Stripe for payment
 processing – providing a complete end-to-end solution for online food ordering 

<img width="500" height="800" alt="Food Ordering App Flowchart" src="https://github.com/user-attachments/assets/47ca2475-9621-4fa2-ba83-e0975047fb59" />


## Features  
### User Side
- Browse and search for food
- View dish details (description, price, etc.)  
- Add items to cart and place orders  
- Multiple payment options: COD, UPI, or Card (Stripe)  
- Secure **login & authentication** system
  <img width="1500" height="966" alt="image" src="https://github.com/user-attachments/assets/bbc15783-871c-435f-bb4a-83f37e20ac93" />


### Vendor / Admin Panel
- Add new food with description and price  
- Update or remove existing dishes  
- View, accept, and update order statuses  
- Manage overall menu efficiently
  <img width="1500" height="966" alt="image" src="https://github.com/user-attachments/assets/f6533e9e-5345-4cdf-b789-aa1c391c3105" />
  <img width="1500" height="966" alt="image" src="https://github.com/user-attachments/assets/07c96c9b-50a9-440f-9057-e041c76502fb" />



<img width="300" height="600" alt="Online Order Payment Process Flowchart" src="https://github.com/user-attachments/assets/3f109be2-9f7a-446f-ad48-fc4916511e46" />


## Tech Stack  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Payment Integration:** Stripe  

## Folder Structure  
 ```
KhanaKhazana/
├── admin/          # Admin panel (vendor dashboard for managing dishes & orders)
├── backend/        # Node.js + Express backend code
├── frontend/       # Static frontend (HTML, CSS, JS)
├── public/         # Public assets (images, icons, etc.)
├── package.json    # Project dependencies & scripts
├── vite.config.js  # Vite configuration 
└── README.md       # Project documentation
 ```
## Getting Started  
### Prerequisites  
Make sure you have installed:  
- [Node.js](https://nodejs.org/) (v14+)  
- [MongoDB](https://www.mongodb.com/)  
- Stripe account (for payment gateway setup)  

### Installation  
1. Clone the repo  
   ```bash
   git clone https://github.com/Syntax-slayer23/KhanaKhazana-.git
   cd KhanaKhazana-
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Setup environment variables  
   Create a `.env` file in the root directory and add:  
   ```
   MONGO_URI=your_mongodb_connection_string
   STRIPE_SECRET_KEY=your_stripe_secret_key
   STRIPE_PUBLIC_KEY=your_stripe_public_key
   PORT=5000
   ```

### Running the App  

Start the backend server:  
```bash
npm start
```

If frontend is separated, you can run it with:  
```bash
npm run dev
```

The app will be available at:  
`http://localhost:5173`  

## Payment Gateway
**Stripe Integration:** The app uses Stripe to handle online payments (supporting card transactions
 and UPI through Stripe’s interface). Ensure your Stripe API keys are correctly set in the 
.env file to
 enable this functionality. 
**Testing Payments:** You can test payment flows in development using Stripe’s provided test card
 numbers and UPI ids. Stripe offers various 
test cards that can be used to simulate successful or
 failed transactions. For example, using the test Visa card number 
4242 4242 4242 4242 with any
 future expiry date and any CVV will result in a successful payment in test mode. This allows you to
 safely verify the payment integration without real transactions. 
- Test payments can be made using [Stripe test cards](https://stripe.com/docs/testing)
<img width="1500" height="966" alt="image" src="https://github.com/user-attachments/assets/54d45fe7-dcf3-4f75-b956-8317da04ffb4" />
<img width="1500" height="966" alt="image" src="https://github.com/user-attachments/assets/83eba085-197d-42de-8d3a-cad331901d9c" />
<img width="1500" height="966" alt="image" src="https://github.com/user-attachments/assets/050ca2ee-ef42-4b56-8ec9-6408334147f2" />

## Contributing  
1. Fork the project  
2. Create a new branch (`feature/YourFeature`)  
3. Commit your changes (`git commit -m "Add new feature"`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request  

## Author  
**Syntax-slayer23**  
- GitHub: [@Syntax-slayer23](https://github.com/Syntax-slayer23)  
