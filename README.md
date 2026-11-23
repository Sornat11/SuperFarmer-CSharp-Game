# SuperFarmer

> Console-based C# implementation of the classic Polish board game **Super Farmer** (*Hodowla zwierzątek*).

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Game](https://img.shields.io/badge/Type-Console_Game-orange?style=flat-square)

---

## Game Overview

SuperFarmer is a turn-based console strategy game where players compete to be the first to build a complete herd of animals (rabbit, sheep, pig, cow, and horse). The game models real board game mechanics including:
- **Dice Rolls:** Determining animal reproduction or losses each round.
- **Animal Trading:** Exchanging livestock with the main stock based on fixed exchange ratios.
- **Predator Attacks:** Wolves and foxes attacking herds unless players are protected by small or big dogs.
- **Victory Condition:** First player to acquire at least one of each main animal type wins.

---

## Project Architecture

- `Game.cs` - Core game loop and round management.
- `Player.cs` - Player state, inventory, and herd tracking.
- `Animal.cs` - Animal domain models and value types.
- `Die.cs` - 12-sided dice roll simulator with probabilities.
- `TradeTable.cs` - Trading table enforcing animal exchange rates.
- `AnimalStock.cs` - Main herd inventory pool management.
- `GameConsole.cs` - CLI presentation and user input handler.

---

## Getting Started

### Prerequisites

- [.NET Core 3.1+ / .NET 8 SDK](https://dotnet.microsoft.com/download)
- Any terminal/console

### Installation & Run

```bash
git clone https://github.com/Sornat11/SuperFarmer-CSharp-Game.git
cd SuperFarmer-CSharp-Game
dotnet run
```
