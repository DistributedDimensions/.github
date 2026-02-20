# Hi there 👋

We build open-source tools for Minecraft server infrastructure.

## DistributedDimensions

A plugin system that splits a Minecraft world across **one Paper server per dimension**, coordinated by a Velocity proxy — with a seamless vanilla-like experience for players.

```
[Player] ──► [Velocity Proxy]
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
  [Overworld]  [Nether]   [End]
```

Portals, inventory, XP, hunger, gamemode and chat are preserved across servers in real time. Entities (mobs, minecarts, items…) are transferred through portals just like in vanilla — with no gameplay drawbacks.

→ [`DistributedDimensions`](https://github.com/your-org/DistributedDimensions)

---

Built with [Paper](https://papermc.io) · [Velocity](https://papermc.io/software/velocity) · Java 21
