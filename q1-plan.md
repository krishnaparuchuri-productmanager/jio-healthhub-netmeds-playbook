# Q1 Launch Plan: JioHealthHub x Netmeds Integration (Apr–Jun)

## 🎯 Objective
Ship "Consult → Rx → Netmeds Delivery" MVP to 10M Jio users 
by end of June.

**North Star:** 1M consult-to-cart conversions @ 75% funnel completion.

---

## 📊 OKRs (Q1)

| Objective | Key Result | Target | Owner |
|-----------|------------|--------|-------|
| Grow acquisition | New JioHealth users | +10M | Growth PM |
| Improve retention | Week-2 retention | 35% | Product PM |
| Drive Netmeds GMV | Consult-to-cart conversions | 1M | Biz Dev |
| Reduce friction | Consult → Rx time | <5 min | Eng Lead |
| Boost revenue | Netmeds order value via Jio | ₹50Cr | Revenue PM |

---

## 📅 12-Week Timeline

### Phase 1: Foundation (Weeks 1–3)
| Week | Task | Owner | Status |
|------|------|-------|--------|
| W1 | Jio–Netmeds API handshake + auth (SSO) | Eng | 🔵 Planning |
| W1 | Discovery: 20 user interviews Hyderabad | PM | 🔵 Planning |
| W2 | Rx JSON schema finalized (JioHealth → Netmeds) | Arch | 🔵 Planning |
| W2 | Netmeds cart API testing (POST /cart/add) | Eng | 🔵 Planning |
| W3 | JioPay integration: Netmeds order flow | Payments | 🔵 Planning |
| W3 | AI Triage v1: Symptom → Urgency score | AI Team | 🔵 Planning |

### Phase 2: Build MVP (Weeks 4–7)
| Week | Task | Owner | Status |
|------|------|-------|--------|
| W4 | Post-consult Rx → Netmeds 1-tap cart | Eng | ⚪ Not Started |
| W5 | Netmeds stock check + ETA API (realtime) | Netmeds | ⚪ Not Started |
| W6 | JioPay 10% cashback logic for health orders | Payments | ⚪ Not Started |
| W6 | AI symptom → drug recommendation v1 | AI | ⚪ Not Started |
| W7 | Digital Rx storage in JioHealth locker | Backend | ⚪ Not Started |
| W7 | Internal QA + bug bash | QA | ⚪ Not Started |

### Phase 3: Launch & Iterate (Weeks 8–12)
| Week | Task | Owner | Status |
|------|------|-------|--------|
| W8 | Beta: 10K Jio corporate users | PM | ⚪ Not Started |
| W9 | A/B test: 1-tap cart vs manual entry | Growth | ⚪ Not Started |
| W10 | Fix top-3 drop-off points in funnel | Eng | ⚪ Not Started |
| W11 | Push notif: "Your Rx is ready on Netmeds" | Marketing | ⚪ Not Started |
| W12 | Full rollout 10M users | All | ⚪ Not Started |

---

## 🔄 Core User Flow (MVP Scope)

Jio User Opens App
↓
AI Symptom Checker (Fever/Headache → HIGH urgency)
↓
Video Consult (Avg 5 min wait, JioMeet infra)
↓
Doctor creates Digital Rx (Paracetamol 500mg x 10)
↓
Rx JSON → POST /netmeds/cart/add (auto-populated)
↓
Stock Check (Netmeds API → 45min ETA Hyderabad)
↓
JioPay 1-tap checkout (10% cashback)
↓
Realtime delivery tracking → Reorder button


---

## 📦 MVP Scope (Must-Have vs Nice-to-Have)

| Feature | Priority | Why |
|---------|----------|-----|
| Rx → Netmeds 1-tap cart | 🔴 Must | Core value prop |
| Realtime stock + ETA | 🔴 Must | Conversion driver |
| JioPay cashback | 🔴 Must | Acquisition hook |
| AI symptom triage | 🟡 Nice | Retention driver |
| Reorder reminder push | 🟡 Nice | Week-2 retention |
| Lab test integration | 🟢 V2 | Post-MVP |
| Chronic disease Rx refill | 🟢 V2 | Scale feature |

---

## ⚠️ Risks & Mitigations

| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|------------|
| Netmeds API latency | Medium | High | Cache stock data, async ETA |
| Doctor Rx format mismatch | High | High | Standardize Rx JSON schema W1 |
| JioPay drop-off | Medium | Medium | Pre-fill cart, 1-tap UX |
| DPDP compliance (2025 law) | High | High | No Rx data stored without consent |
| Low doctor adoption | Low | High | Incentive program + training |

---

## 🏆 Success Metrics (End of Q1)

| Metric | Baseline | Q1 Target |
|--------|----------|-----------|
| Consult-to-cart rate | 0% | 75% |
| New users (Jio → JioHealth) | 1M DAU | 10M DAU |
| Netmeds GMV via Jio | ₹0 | ₹50Cr |
| Rx delivery time (urban) | N/A | <45 min |
| Week-2 retention | 20% | 35% |
| NPS post-consult | 32 | 50+ |

---
