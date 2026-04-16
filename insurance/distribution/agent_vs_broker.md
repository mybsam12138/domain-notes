# Agent vs Broker (Insurance) — Summary

## 1. Core Difference

| Aspect | Agent | Broker |
|------|------|--------|
| Represents | Insurance company | Customer |
| Works for | Insurer | Client |
| Product scope | Usually limited (one or few insurers) | Multiple insurers |
| Goal | Sell insurer’s product | Find best option for client |
| Typical form | Individual | Usually company (team-based) |

---

## 2. Simple Definitions

- **Agent**  
  → A salesperson who represents an insurance company and sells its products.

- **Broker**  
  → An independent advisor who represents the customer and helps choose the best insurance from multiple insurers.

---

## 3. Example 1 (Retail Scenario)

### Agent Case

John wants to buy health insurance.

John → Agent Alice → Ping An Insurance

- Alice only sells Ping An products  
- She recommends Ping An plan  

👉 Alice = Agent (represents insurer)

---

### Broker Case

John wants to compare multiple options.

John → Broker Bob → (Ping An / AIA / AXA)

- Bob compares multiple insurers  
- Recommends the best plan  

👉 Bob = Broker (represents customer)

---

## 4. Example 2 (Corporate Scenario)

Company A wants insurance for 500 employees.

### Using Agent

Company A → Agent → One insurer

- Limited options  
- Less comparison  

---

### Using Broker

Company A → Broker → Multiple insurers → Best plan selected

- Compares coverage, price, exclusions  
- Negotiates terms  

👉 Broker is more suitable for complex needs

---

## 5. Key Insight

Agent  → sells insurance  
Broker → advises on insurance

---

## 6. System Design Perspective (PAS)

### Policy Example

Policy P001  
Customer: John  
Agent: Alice  
Insurer: Ping An  

Policy P002  
Customer: Company A  
Broker: BrokerCorp  
Insurer: AXA  

---

### Modeling

- Agent and Broker are both **Party**
- Differentiated by **Role**

Party_Role:  
Alice → AGENT  
BrokerCorp → BROKER  

---

## 7. Final Summary

Agent   = represents insurer, sells products  
Broker  = represents customer, finds best option
