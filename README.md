# Topological Graph Neural Network

I am building a **Topological Graph Neural Network (topological-gnn)** from the ground up. Most GNNs fail to capture global structures (like large cycles or voids) because they rely on local message passing. This project integrates **Persistent Homology (PH)** into the GNN architecture to give the model "topological sight."

**The goal:** A full-stack ecosystem including a custom AI engine, a Next.js visualization dashboard, and a Flutter mobile interface.

## The Roadmap

- [ ] Phase 1: Research and Math (current)
- [ ] Phase 2: Implementing the Core Engine
- [ ] Phase 3: Deployment and API
- [ ] Phase 4: Interface and Visuation
  - Web app (Next.js)
  - Mobile app (Flutter)

## Technical Stack (Target)

- **AI:** Python, PyTorch, Gudhi (TDA), PyTorch Geometric
- **Backend:** FastAPI (or Flask if needed, I'm not sure, haha!), Docker
- **Frontend:** Next.js 16+, Three.js for visualization
- **Mobile:** Flutter

### Why a Dev Log?

I am documenting every step of this journey, from the math I'm reading to the bugs I'm fixing. I believe great engineering is the outcome of a careful, interesting journey. So, please check the [LOGS.md](./LOGS.md) for the latest update.

**License:** MIT
[ByGanesh.com](https://byganesh.com)
