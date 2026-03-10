<div align="center">

<br/>

# Q·mate

<img src="public/favicon.svg" width="72" height="72" alt="Qmate logo"/>

<br/><br/>

### *Your time is too valuable to spend standing in a queue.*

Qmate is a Kerala-based web app that connects people who need someone to hold their spot in a queue with local part-timers who earn money by standing in those queues on their behalf.

<br/>

**🌐 [qmateapp1.web.app](https://qmateapp1.web.app)**

<br/>

---

</div>

## 🤔 What Problem Does Qmate Solve?

Every day, thousands of people in Kerala waste hours standing in queues at banks, hospitals, government offices, and railway counters — time that could be spent working, resting, or with family.

**Qmate solves this in three steps:**

1. A **customer** opens the app and hires a nearby part-timer to stand in a specific queue
2. The **part-timer** heads to the queue and holds the spot
3. The customer arrives only when it's almost their turn — saving hours

No more wasted mornings. No more leaving work early just to get a token.

---

## 👥 Who Is It For?

### 🛒 Customers
Anyone who needs a queue spot held — working professionals, elderly people, parents, or anyone with a busy schedule who can't afford to waste time standing in line.

**Common use cases:**
- SBI / Canara / other bank queues
- Government offices — RTO, passport office, ration office
- Hospital OPD registration counters
- Railway / KSRTC reservation counters
- Any long queue where you just need a token or number

### ⚡ Part-timers
Local people looking to earn extra income on flexible hours. No office, no fixed schedule — just show up, stand in a queue, get paid.

**Who can be a part-timer:**
- College students with free time between classes
- Retired individuals
- Anyone looking for flexible part-time work
- People already near common queue locations

---

## 📱 Pages & What They Do

### 🔐 Login Page — `/login.html`

The entry point of the app. Both customers and part-timers sign in from the same page.

- Choose your role — **Customer** or **Part-timer**
- Sign in with **Email & Password** or **Google account**
- New users can **register** directly from this page
- Part-timers fill in extra details — hourly rate and specialty
- After login, you are automatically taken to the right dashboard for your role

---

### 🛒 Customer Dashboard — `/customer.html`

Everything a customer needs to find and hire a part-timer.

**What you can do here:**

**Browse Part-timers**
- See a list of all registered part-timers near you
- Each card shows their name, specialty, rating, number of jobs done, and hourly rate
- A green dot means they are currently available and ready to accept jobs
- Filter by — All / Available Now / Top Rated
- Search by name or specialty

**Send a Hire Request**
- Click **"Hire Now"** on any available part-timer
- Fill in three things:
  - Queue location (e.g. SBI Bank, MG Road, Ernakulam)
  - Estimated duration (30 min to 2+ hours)
  - Any special instructions (token number needed, counter details, etc.)
- Click **"Send Request"** — the part-timer is notified instantly

**Track Your Active Requests**
- Once a request is sent, it appears in the **"Your active requests"** section
- Status updates live — from **Pending** → **Accepted** → **Completed**
- No need to refresh the page — updates happen automatically in real time

**AI Support Chat**
- Click **"Chat"** in the top bar to open the AI assistant
- Ask anything — pricing, how tracking works, cancellations, how to hire
- Available 24/7, instant answers

---

### ⚡ Part-timer Dashboard — `/partimer.html`

Everything a part-timer needs to manage their work and earnings.

**Your Profile Card**
- Shows your name, specialty, total jobs done, star rating, and hourly rate
- **Available for Jobs** toggle — turn ON to start receiving requests, turn OFF when you are busy or unavailable
- **Share Live Location** toggle — when ON, your GPS location is visible to customers on the map

**Incoming Requests Inbox**
- All pending hire requests from customers appear here in real time
- Each request card shows:
  - Customer's name
  - Queue location
  - Duration needed
  - Your pay for the job
  - Any special instructions from the customer
  - How long ago the request was sent
- **Ring Popup** — when a new request comes in, a full-screen animated popup appears so you never miss a job
- Click **"Accept job"** to confirm — the customer is notified instantly
- Click **"Decline"** if you can't take it — the customer is notified to find someone else

**Active Job Panel**
- Once you accept a job, an active job panel appears at the top of your dashboard
- Shows the customer's name, queue location, duration, and your pay
- When you finish the job, click **"Mark as completed"** — your earnings and job count update automatically

**Earnings Tracker**
- Shows your earnings for today
- Progress bar toward your daily earnings goal (default ₹500)
- Recent job history — see completed and declined jobs with pay

---

## 💸 How Pricing Works

- Part-timers set their own hourly rate when they register (typically ₹60 – ₹120 per hour)
- Customers see the rate clearly on each part-timer's card before hiring
- The rate is agreed upon before the job starts — no surprises
- Payment is currently handled directly between customer and part-timer (cash or UPI)

---

## ⚡ How a Request Works — Step by Step

```
Customer opens the app
        ↓
Browses available part-timers nearby
        ↓
Clicks "Hire Now" on a part-timer
        ↓
Fills in queue location, duration, instructions
        ↓
Clicks "Send Request"
        ↓
Part-timer receives a ring popup instantly
        ↓
Part-timer clicks "Accept job"
        ↓
Customer's status updates to "Accepted" live
        ↓
Part-timer heads to the queue location
        ↓
Customer arrives when it's nearly their turn
        ↓
Part-timer clicks "Mark as completed"
        ↓
Job done — earnings updated, part-timer available again
```

---

## 🔒 Is It Safe?

- All users sign in with a verified Google account or email — no anonymous access
- Customers can see a part-timer's rating and number of completed jobs before hiring
- Every request is tied to both the customer's and part-timer's account
- Location data is only shared when the part-timer explicitly turns on location sharing
- All data is stored securely in Google's Firebase — industry-standard encryption

---

## 🌍 Where Is Qmate Available?

Qmate is currently serving **Kerala, India** — with a focus on:

- **Ernakulam / Kochi**
- **Thiruvananthapuram**
- **Kozhikode**
- **Thrissur**

Expansion to other districts and states is planned as the user base grows.

---

## 🗓️ Roadmap

Things coming in future versions:

- [ ] In-app UPI payment integration
- [ ] Real-time map showing part-timer's live location
- [ ] Rating and review system after job completion
- [ ] Customer notifications via WhatsApp or SMS
- [ ] Part-timer verification / ID badge system
- [ ] Admin panel to manage users and disputes
- [ ] Android & iOS apps

---

## ❓ Frequently Asked Questions

**Q: Is Qmate free to use?**
You pay the part-timer directly for their time. There is no platform fee right now.

**Q: What if the part-timer doesn't show up?**
You can decline and hire a different part-timer. A rating and dispute system is coming in a future update.

**Q: Can I cancel a request after sending it?**
Yes — you can cancel any request that is still in "Pending" status before the part-timer accepts it.

**Q: How do I know when it's my turn?**
The part-timer will notify you via phone call or message when you need to come. Always share your phone number in the instructions field when sending a request.

**Q: What queues does this work for?**
Any physical queue — banks, hospitals, government offices, railway counters, KSRTC reservations, ration shops, and more.

**Q: How do I become a part-timer?**
Go to [qmateapp1.web.app/login.html](https://qmateapp1.web.app/login.html) → click "Part-timer" → click "Register" → fill in your details → you're in.

---

## 👥 Built By

| Name | Role |
|---|---|
| **Rohith** | Design & Development |
| **Athul Albino** | Documentation |
| **Minha Rasheed** | Idea & Management |

---

<div align="center">

Made with ❤️ in Kerala &nbsp;·&nbsp; 2025 &nbsp;·&nbsp; Qmate

</div>
