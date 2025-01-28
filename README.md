
 # 🎉 Event Organizer Smart Contract

## 🚀 Overview
The **EventContract** is your all-in-one decentralized solution for creating, managing, and attending events on the Ethereum blockchain. 🎟️✨

---

## 🌟 Features
1. **Create Events** 🗓️: Plan future events with ticket sales directly on-chain.
2. **Buy Tickets** 💳: Purchase tickets securely using Ether.
3. **Transfer Tickets** 🔄: Seamlessly transfer tickets to friends or family.

---

## 📜 Contract Highlights
### 🏗️ Structs
#### `Event`
- **Organizer**: Address of the event creator.
- **Name**: Event name.
- **Date**: Event date (timestamp).
- **Price**: Ticket price (Wei).
- **Tickets**: Total & remaining tickets.

### 🔑 Mappings
- `events`: Stores events by ID.
- `tickets`: Tracks user-owned tickets.

---

## ⚙️ Functions
### 1. **Create an Event** 🛠️
Organize future events with `name`, `date`, `price`, and `ticketCount`. Ensures valid dates and ticket availability.

### 2. **Buy Tickets** 🛒
Purchase tickets for an event by paying the exact Ether amount. Validates event existence and availability.

### 3. **Transfer Tickets** ✉️
Easily send tickets to another address before the event date.

---

## 🛠️ How to Use
1. **Create**: Call `createEvent` with event details.
2. **Buy**: Use `buyTicket` with the event ID and ticket quantity (send Ether).
3. **Transfer**: Call `transferTicket` with recipient details.

---

## 🔒 Security
- **Safe Transfers**: Prevents fraud with strict validation.
- **Ether Checks**: Ensures correct payments.

---

## 🌈 Future Enhancements
- 🛑 Event cancellation.
- 🔄 Secondary ticket resales.
- 📈 Dynamic ticket pricing.

--- 

🎉 Build and attend events with confidence! 🚀

