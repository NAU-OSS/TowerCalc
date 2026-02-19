# TowerCalc
A combat simulation and DPS calculator for Anime World Tower Defense.  
Designed for theorycrafting, optimization, and analyzing complex passive and leader skill interactions.
---
## Features

- Accurate DPS calculations

- Support for damage-over-time passives (burn, bleed, stacking effects)

- Multi-placement damage modeling

- Filter and compare units by category, element, and passive

- Extensible design for future combat simulation features

---

## Purpose

This project aims to provide a transparent and flexible damage calculation engine for Tower Defense players who want to:

- Compare units objectively

- Optimize team compositions

- Understand passive stacking behavior

- Theorycraft leader skill synergies

## Planned Features

- Full combat simulation (wave-based modeling)

- Enemy resistance & defense scaling

- Team composition optimizer

- Web or GUI interface

- Data import/export tools
---
## 📖 Usage Example

Below is a conceptual example of how the calculator will be used:

```python
from awtd_combat_sim import Unit, LeaderSkill, calculate_dps

gojo = Unit(
    name="Gojo",
    base_damage=12000,
    attack_speed=1.5,
    placements=3,
    passive="Void"
)

leader = LeaderSkill(
    category="Sorcerer",
    damage_bonus=0.25  # 25% damage boost
)

dps = calculate_dps(unit=gojo, leader_skill=leader)

print(f"Total DPS: {dps}")
```
## 📦 Installation
```bash
git clone https://github.com/yourusername/AWTD-Combat-Sim.git
cd AWTD-Combat-Sim
```

## Contributing
Contributions are welcome!
If you'd like to add new passives, mechanics, or improve calculation accuracy, feel free to open an issue or submit a pull request.
(Setup instructions coming soon.)

🤝 Contributing

Contributions are welcome!
If you’d like to add new passives, mechanics, or improve calculation accuracy, feel free to open an issue or submit a pull request.
