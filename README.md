# Blackjack Simulation with Gym

This repository contains a Blackjack game simulation using OpenAI Gym's `Blackjack-v1` environment. The simulation runs 500,000 episodes with a predefined strategy and records the win, lose, and draw statistics.

## 🃏 Project Overview
- Uses the **Gym Blackjack-v1** environment.
- Plays **500,000** games automatically.
- Records win, lose, and draw statistics.
- Handles multiple Gym API versions to ensure compatibility.

## 📌 Features
- **Automated Gameplay**: The agent plays based on a fixed strategy (always staying).
- **Performance Tracking**: Keeps count of wins, losses, and ties.
- **API Compatibility**: Works with both old and new Gym step/reset APIs.

## 🚀 Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/blackjack-simulation.git
cd blackjack-simulation
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

## 🛠️ Dependencies
- `gymnasium`
- `numpy`
- `tqdm`

To install manually, run:
```bash
pip install gymnasium numpy tqdm
```

## 📊 Expected Output
The script will print the final statistics:
```
Win: 192021  (38.40%)
Lose: 283702 (56.74%)
Even: 24277  (4.85%)
```

## 🏆 Strategy Used
- The agent **always chooses to stay (action = 0)**.
- This is a basic strategy for testing environment compatibility.
