# Social Profile Dashboard

A React-based social profile dashboard application built with Vite, featuring user profiles, friend lists, and transaction history components.

## Features

- **User Profile Display**: Shows user statistics, avatar, and personal information
- **Friend List**: Displays user's friends with online/offline status
- **Transaction History**: Presents a table of user transactions with detailed information

## 🚀 Technologies Used

- React
- Vite
- CSS Modules
- Modern JavaScript (ES6+)

## 📦 Installation

1. Clone the repository:

```bash
git clone [your-repository-url]
```

2. Navigate to the project directory:

```bash
cd goit-react-hw-01
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

## 🏗️ Project Structure

```
src/
├── components/
│   ├── Profile/
│   │   ├── Profile.jsx
│   │   └── Profile.module.css
│   ├── FriendList/
│   │   ├── FriendList.jsx
│   │   ├── FriendListItem.jsx
│   │   └── FriendList.module.css
│   └── TransactionHistory/
│       ├── TransactionHistory.jsx
│       └── TransactionHistory.module.css
├── App.jsx
└── main.jsx
```

## 🧩 Components

### Profile

Displays user profile information including:

- Profile picture
- Username
- Tag
- Location
- Statistics (followers, views, likes)

### FriendList

Shows a list of friends with:

- Avatar
- Name
- Online/offline status indicator

### TransactionHistory

Presents a table of transactions including:

- Type
- Amount
- Currency

## 🛠️ Available Scripts

- `npm run dev` - Starts development server
- `npm run build` - Creates production build
- `npm run lint` - Runs ESLint
- `npm run preview` - Preview production build locally

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
