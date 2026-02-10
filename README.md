# Epic Strategy

A large-scale JavaScript-based strategy game featuring real-time gameplay, unit management, resource gathering, AI opponents, multiplayer support, and dynamic map systems.

## Features

- **Real-time Gameplay**: Experience dynamic, fast-paced strategy battles
- **Unit Management**: Command diverse units with unique abilities and strengths
- **Resource Gathering**: Manage resources to build, upgrade, and sustain your empire
- **AI Opponents**: Challenge intelligent computer opponents with adaptive strategies
- **Multiplayer Support**: Battle against other players in competitive matches
- **Dynamic Maps**: Play on varied terrain with strategic advantages and challenges
- **Campaign Mode**: Engage in a story-driven single-player experience
- **Customization**: Create custom games with adjustable rules and settings

## Technology Stack

- **Language**: JavaScript (ES6+)
- **Graphics**: Pixi.js (WebGL-based 2D renderer)
- **Architecture**: Modular component-based design
- **Server**: Node.js with WebSocket support for multiplayer

## Project Structure

```
epic-strategy/
├── src/
│   ├── core/
│   │   ├── Game.js
│   │   ├── GameState.js
│   │   └── GameLoop.js
│   ├── entities/
│   │   ├── Unit.js
│   │   ├── Building.js
│   │   └── Resource.js
│   ├── map/
│   │   ├── Map.js
│   │   ├── Tile.js
│   │   └── MapGenerator.js
│   ├── ui/
│   │   ├── UIManager.js
│   │   ├── HUD.js
│   │   └── Menu.js
│   ├── ai/
│   │   ├── AIPlayer.js
│   │   ├── Strategy.js
│   │   └── Pathfinding.js
│   ├── multiplayer/
│   │   ├── NetworkManager.js
│   │   └── Synchronizer.js
│   └── index.js
├── assets/
│   ├── images/
│   ├── audio/
│   └── data/
├── public/
│   └── index.html
├── tests/
├── docs/
├── package.json
├── webpack.config.js
└── README.md
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/viktorijaaleknaite5-crypto/epic-strategy.git
cd epic-strategy
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:8080`

## Development

For development with hot reload:
```bash
npm run dev-build
```

For production build:
```bash
npm run build
```

## Game Mechanics

### Resource System
- **Gold**: Currency for building and unit recruitment
- **Wood**: Material for construction
- **Food**: Required for unit upkeep and population growth
- **Stone**: Material for fortifications

### Unit Types
- **Infantry**: Basic melee units
- **Archers**: Ranged damage dealers
- **Cavalry**: Fast mobile units
- **Mages**: Special ability units
- **Siege Units**: High damage, slow movement

### Buildings
- **Barracks**: Train military units
- **Resource Generators**: Produce resources
- **Defenses**: Towers and walls for protection
- **Tech Lab**: Research upgrades and new units

## Contributing

Feel free to submit issues and enhancement requests!

## License

MIT License - See LICENSE file for details

## Roadmap

- [ ] Single-player campaign
- [ ] Multiplayer matchmaking
- [ ] Advanced AI strategies
- [ ] 3D graphics upgrade
- [ ] Mobile version
- [ ] Spectator mode
- [ ] Tournament system

## Credits

Created by viktorijaaleknaite5-crypto

Enjoy the game! 🎮