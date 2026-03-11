<div align="center">

# StrataCore
### Deterministic Portfolio Allocation Engine

<br>

<p align="center">
  <b>StrataCore is a deterministic portfolio allocation engine that converts probabilistic market scenarios into explainable portfolio weights using a constraint-based allocation system.</b>
</p>

</div>

---

## 📌 How It Works

StrataCore rejects traditional "black-box" approaches like Markowitz mean-variance optimization. Instead, it relies on a strict, pure-math pipeline that guarantees **100% determinism and explainability** for every percentage point allocated.

**The Pipeline:**

Scenarios (Bull / Base / Bear)
↓
Expected Value Calculation
↓
Confidence Scoring
↓
Structural Filtering
↓
Constraint-Based Allocation
↓
Portfolio Weights

---

## 💻 Tech Stack

The architecture focuses on absolute precision and high-performance determinism, exclusively utilizing the `Decimal` library to avoid floating-point drift.

*   **Python** (Core computational engine)
*   **FastAPI** (Async web layer)
*   **Pydantic** (Strict data validation)
*   **PostgreSQL** + **SQLAlchemy** (Persistence)
*   **Pure Math Engine** (No external dependencies like Numpy or Pandas)

---

## 📊 Project Status & Capabilities

Transparent overview of the current development phase:

✅ **Core Engine:** 100% complete. **Engine stress-tested across 20M iterations with deterministic outputs and zero memory leaks.**
✅ **Scaling:** Successfully stress-tested with universes of up to 1,000 algorithmic assets.
✅ **Resilience:** Formal verification against 10,000+ adversarial regimes (logic asphyxiation) with 0 invariant breaches.
🚧 **SaaS Interface:** Partially implemented (Next.js scaffolded, authentication & core dashboard concepts working). 
🚧 **Billing / User Management:** Stripe integration architecture modeled.

---

## 🖼️ Screenshots

### 1. The Allocation Dashboard
![Dashboard overview displaying portfolio performance, total cash, and AI narrative](https://via.placeholder.com/800x450?text=Dashboard+Screenshot)

### 2. Allocation Matrix & Results
![Matrix showing Bull/Base/Bear inputs side-by-side with final deterministic weights](https://via.placeholder.com/800x450?text=Allocation+Matrix+Screenshot)

### 3. Scenario & Universe Builder
![User interface for setting constraints and asset probabilities](https://via.placeholder.com/800x450?text=Scenario+Builder+Screenshot)
