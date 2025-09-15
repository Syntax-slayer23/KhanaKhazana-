<img width="399" height="159" alt="logo" src="https://github.com/user-attachments/assets/bea4080a-6cab-418c-acb9-af506a9dfd11" />


# KhanaKhazana  
KhanaKhazana is a **food ordering and delivery web application**.  
Users can explore menus, order their favorite food, and make secure payments through **Cash on Delivery (COD)**, **UPI**, or **Card payments via Stripe**.  
Vendors (via the **Admin Panel**) can manage food, handle incoming orders, and update order statuses seamlessly.  

<img width="1536" height="1024" alt="Food Ordering App Flowchart" src="https://github.com/user-attachments/assets/47ca2475-9621-4fa2-ba83-e0975047fb59" />


## Features  
### User Side
- Browse and search for food
- View dish details (description, price, etc.)  
- Add items to cart and place orders  
- Multiple payment options: COD, UPI, or Card (Stripe)  
- Secure **login & authentication** system  

### Vendor / Admin Panel
- Add new food with description and price  
- Update or remove existing dishes  
- View, accept, and update order statuses  
- Manage overall menu efficiently

  ![WhatsApp Image 2025-09-15 at 23 30 55_378f5315](https://github.com/user-attachments/assets/b3f4bb2f-9e11-4459-bab0-93be7d39ed32)
<img width="1024" height="1536" alt="Online Order Payment Process Flowchart" src="https://github.com/user-attachments/assets/3f109be2-9f7a-446f-ad48-fc4916511e46" />


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
├── vite.config.js  # Vite configuration (if used)
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
- **Stripe Integration** for card/UPI payments  
- Test payments can be made using [Stripe test cards](https://stripe.com/docs/testing)  

## Contributing  
1. Fork the project  
2. Create a new branch (`feature/YourFeature`)  
3. Commit your changes (`git commit -m "Add new feature"`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request  

## Author  
**Syntax-slayer23**  
- GitHub: [@Syntax-slayer23](https://github.com/Syntax-slayer23)  
