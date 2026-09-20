# Checklist: Upgrade System

**Feature:** Level up buildings/heroes/skills by spending resources.

## ✅ Core Checks
- [ ] Upgrade button appears when resources are sufficient
- [ ] Upgrade button is greyed out when resources are insufficient
- [ ] Resources decrease by the correct amount
- [ ] Building level increases by 1
- [ ] Upgrade effect stats are correct

## 💰 Costs
- [ ] Cost increases according to the formula (check first 5 levels)
- [ ] Cost does not overflow at high levels
- [ ] Cost differs per building type

## 🐛 Edge Cases
- [ ] Rapidly tapping Upgrade does not cause negative resources
- [ ] Upgrading with exactly enough resources succeeds
- [ ] Upgrading while an event popup is open does not crash
