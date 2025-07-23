# NonRed Bus: Ticket-Booking
React Web App for booking bus. User have to provide boarding, dropping locations, with date. All available data will shown. User can book ticket and payment. PDF will be generate after payment done.

![NonRed Bus Website](https://res.cloudinary.com/gafrfdasdx/image/upload/v1618489835/portfolio/Completed%20Projects/NonRedBus_iphalz.png)

## 🛠️ Tech Stack

| Technology     | Description                    |
|----------------|--------------------------------|
| React.js       | Frontend framework             |
| Tailwind CSS   | Styling and responsive design  |
| React Router   | Client-side routing            |
| HTML & CSS     | Markup and custom styling      |
| JavaScript     | Frontend logic                 |
| jsPDF          | PDF generation for ticket      |

---

## 📁 Project Structure

nonred-bus-booking/
│
├── public/
│ └── index.html
├── src/
│ ├── components/ # UI components (BusList, SeatSelector, etc.)
│ ├── pages/ # Pages like Home, Booking, Payment, etc.
│ ├── App.jsx
│ └── main.jsx
├── README.md
└── package.json

## 🧪 How It Works

1. User selects:
   - Boarding location
   - Dropping location
   - Travel date

2. Available buses are shown with:
   - Bus name, timing, seat availability

3. User proceeds to:
   - Select seat(s)
   - Make payment
   - Receive PDF ticket

## 📌 Future Enhancements

- [ ] Backend integration with Node.js + MongoDB
- [ ] Authentication (login/register)
- [ ] Live seat tracking
- [ ] Razorpay or Stripe for real payments
- [ ] Admin panel for bus management
