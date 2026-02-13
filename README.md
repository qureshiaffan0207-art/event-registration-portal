# 🎯 Event Registration Portal

**Multi-Page Event Registration Form with Payment Gateway Integration**

## 📋 Overview

A comprehensive 3-page event registration system with dynamic form fields, multiple payment gateway integrations, and modern UI/UX design. Built as part of my web development journey during the Apex Planet Internship.

## ✨ Features

### Page 1: Personal Information
- ✅ Full name, email, phone validation
- ✅ College/organization and year selection
- ✅ City information
- ✅ Referral code system (10% discount)
- ✅ Real-time form validation

### Page 2: Event Details
- ✅ Dynamic event selection from mock API
- ✅ Event-specific fields based on category:
  - **Workshops**: Track selection, experience level, laptop requirements
  - **Competitions**: Team name, size, project category
  - **Conferences**: Session preferences, dietary restrictions, accommodation
- ✅ T-shirt size selection
- ✅ Special requirements textarea

### Page 3: Review & Payment
- ✅ Complete registration summary
- ✅ Document upload with validation (PDF, JPG, PNG - max 5MB)
- ✅ Multiple payment methods:
  - 💳 Credit/Debit Card
  - 📱 UPI Payment
  - 👛 Digital Wallet (Paytm, PhonePe, Google Pay, Amazon Pay)
  - 🏦 Net Banking

### Payment Features
- ✅ Dedicated payment page for each method
- ✅ Live card preview for credit/debit cards
- ✅ UPI QR code & 10-minute timer
- ✅ Wallet selection with multiple providers
- ✅ Bank selection for net banking
- ✅ Payment processing animation
- ✅ Order confirmation with generated IDs

## 🎨 Design Highlights

- Modern gradient background (Blue to Purple theme)
- Card-based layout with subtle shadows
- Smooth page transitions and animations
- Progress bar with step indicators
- Neumorphic design elements
- Fully responsive (mobile + desktop)
- Interactive hover effects

## 💻 Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Design**: Custom CSS animations, gradients, neumorphic UI
- **Validation**: Client-side form validation
- **Storage**: LocalStorage for referral codes (mock data)

## 🛠️ Installation & Usage

1. **Clone the repository**
```bash
git clone https://github.com/qureshiaffan0207-art/event-registration-portal.git
cd event-registration-portal
```

2. **Open in browser**
```bash
# Simply open the HTML file
open task2.html
# or
start task2.html
```

3. **Test Features**
- Try valid referral codes: `EVENT10`, `STUDENT24`, `TECH2024`, `SAVE10`
- Test different event types to see dynamic fields
- Upload documents (PDF/JPG/PNG only, max 5MB)
- Try all payment methods

## 📁 Project Structure

```
event-registration-portal/
│
├── event-registration-enhanced.html   # Main application file
├── README.md                          # Project documentation

```

## 🎯 Key Learnings

- Advanced form validation techniques
- Dynamic field rendering based on user selection
- Payment gateway flow implementation
- File upload validation (type & size)
- Responsive design principles
- State management in vanilla JavaScript
- User experience optimization

## 🔮 Future Enhancements

- [ ] Backend integration with Node.js/Express
- [ ] Database storage (MongoDB/PostgreSQL)
- [ ] Real payment gateway API integration (Stripe/Razorpay)
- [ ] Email confirmation system
- [ ] Admin dashboard for event management
- [ ] QR code generation for tickets
- [ ] Social media sharing

## 👨‍💻 Author

**Your Name**
- GitHub: (https://github.com/qureshiaffan0207-art)
- LinkedIn:(https://linkedin.com/in/affan-qureshi-b090113a5)
- Email: your.email@example.com

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Apex Planet Internship** for the opportunity and guidance
- Unsplash for placeholder images
- Community for inspiration and support

---

⭐ **If you found this project helpful, please give it a star!** ⭐

**Part of:** Apex Planet Internship Program  
**Task:** 2 - Multi-Page Event Registration Form  
**Date:** February 2024
